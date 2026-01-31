// ☕ Java 17 is my weapon of choice, powered by Spring Boot 
// 🚀 Pseudocode 

public class JoaoVictorSales {

    public static void main(String[] args) {

        Developer joao = Developer.builder()
            .name("João Victor Sales")
            .email("vsalescode@gmail.com")
            .location("Pacatuba, CE - Brasil")
            .github("github.com/vsalescode")
            .linkedin("linkedin.com/in/vsalescode")
            .goal("Backend Java Internship")
            .build();

        joao.installMindset(List.of(
            "backend-passion",
            "clean-code",
            "problem-solving",
            "coffee-driven-development"
        ));

        Skills skills = Skills.builder()

            // Linguagens de programação
            .languages(List.of(
                "Java 17",
                "JavaScript"
            ))

            // Marcação e estilo (não são linguagens de programação)
            .markupAndStyle(List.of(
                "HTML5",
                "CSS3"
            ))

            .frameworks(List.of(
                "Spring Boot",
                "Spring Security",
                "Spring Cloud OpenFeign",
                "Hibernate/JPA"
            ))

            .databases(List.of(
                "PostgreSQL",
                "MongoDB",
                "MySQL"
            ))

            .architecture(List.of(
                "Microservices",
                "BFF Pattern",
                "Layered Architecture",
                "REST APIs"
            ))

            .tools(List.of(
                "Git & GitHub",
                "Maven",
                "Docker",
                "GitHub Actions",
                "Postman",
                "JWT"
            ))

            .practices(List.of(
                "SOLID",
                "Clean Code",
                "Global Exception Handling",
                "Code Review"
            ))

            .learning(List.of(
                "JUnit & Mockito",
                "AWS",
                "RabbitMQ & Kafka",
                "Kubernetes"
            ))
            .build();

        BackendDeveloper developer = new BackendDeveloper(joao, skills);

        /*
         * 🎯 Projeto Destaque – Agendador de Tarefas (Microserviços)
         *
         * • User Service
         *   - PostgreSQL
         *   - Autenticação JWT com Spring Security
         *
         * • Task Service
         *   - MongoDB
         *   - CRUD completo
         *
         * • Integração
         *   - Spring Cloud OpenFeign
         *   - Padrão BFF
         *
         * • Qualidade
         *   - Arquitetura em camadas
         *   - Tratamento global de exceções
         *   - Docker + CI com GitHub Actions
         *
         * 🔗 github.com/vsalescode/usuario
         */

        try {
            while (developer.hasEnergy() || developer.hasCoffee()) {

                developer.deliver(List.of(
                    "APIs REST seguras com JWT",
                    "Comunicação entre microsserviços via OpenFeign",
                    "Persistência PostgreSQL + MongoDB",
                    "Aplicações dockerizadas"
                ));

                developer.code();
                developer.refactor();
                developer.commitWithMeaning();

                if (developer.foundBug()) {
                    developer.debug()
                             .fix()
                             .test();
                }
            }

        } catch (BurnoutException e) {
            developer.takeCoffeeBreak();
            developer.study("System Design");
            developer.comeBackStronger();
        }
    }
}

// 🎓 Educação
@Entity
class Education {

    @Id
    String degree = "Engenharia de Software";

    String institution = "UNINTER - Fortaleza, CE";

    String status = "Em andamento (07/2025 → )";
}

// 🌍 Idiomas
enum Languages {
    PORTUGUESE("Nativo 🇧🇷"),
    ENGLISH("Intermediário 🇺🇸"),
    SPANISH("Básico 🇪🇸");

    private final String level;

    Languages(String level) {
        this.level = level;
    }
}

/*
 * 📫 Contato
 * Email: vsalescode@gmail.com
 * LinkedIn: linkedin.com/in/vsalescode
 * GitHub: github.com/vsalescode
 *
 * 🚀 Foco: Backend com Java & Spring
 * 💡 Buscando estágio para evoluir e gerar impacto real
 */
