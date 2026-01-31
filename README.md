// Java 17 is my weapon of choice, powered by Spring Boot
// Pseudocode representation of my professional profile

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
            "continuous-learning"
        ));

        Skills skills = Skills.builder()

            // Programming languages
            .languages(List.of(
                "Java 17",
                "JavaScript"
            ))

            // Markup and style
            .markupAndStyle(List.of(
                "HTML5",
                "CSS3"
            ))

            // Frameworks and libraries
            .frameworks(List.of(
                "Spring Boot",
                "Spring Security",
                "Spring Cloud OpenFeign",
                "Hibernate/JPA"
            ))

            // Databases
            .databases(List.of(
                "PostgreSQL",
                "MongoDB",
                "MySQL"
            ))

            // Architectural knowledge
            .architecture(List.of(
                "Microservices",
                "BFF Pattern",
                "Layered Architecture",
                "REST APIs"
            ))

            // Tools I already use
            .tools(List.of(
                "Git & GitHub",
                "Maven",
                "Postman",
                "JWT"
            ))

            // Engineering practices
            .practices(List.of(
                "SOLID",
                "Clean Code",
                "Global Exception Handling"
            ))

            // Currently studying
            .learning(List.of(
                "Docker",
                "JUnit & Mockito",
                
            ))
            .build();

        BackendDeveloper developer =
            new BackendDeveloper(joao, skills);

        /*
         * Featured Project - Task Scheduler Microservices
         *
         * User Service
         * - PostgreSQL
         * - JWT Authentication with Spring Security
         *
         * Task Service
         * - MongoDB
         * - Full CRUD
         *
         * Integration
         * - Spring Cloud OpenFeign
         * - BFF communication pattern
         *
         * Quality
         * - Layered architecture
         * - Global exception handling
         *
         * github.com/vsalescode/usuario
         */

        try {

            while (developer.hasEnergy()) {

                developer.deliver(List.of(
                    "Secure REST APIs with JWT",
                    "Microservices communication via OpenFeign",
                    "PostgreSQL and MongoDB persistence",
                    "Organized layered architecture"
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

            developer.takeBreak();
            developer.study("System Design");
            developer.comeBackStronger();

        }
    }
}

// Education
@Entity
class Education {

    @Id
    String degree = "Engenharia de Software";

    String institution = "UNINTER - Fortaleza, CE";

    String status = "Em andamento (07/2025 -> )";

}

// Languages
enum Languages {

    PORTUGUESE("Nativo"),
    ENGLISH("Intermediário"),
    SPANISH("Básico");

    private final String level;

    Languages(String level) {
        this.level = level;
    }

}

/*
 * Contact
 * Email: vsalescode@gmail.com
 * LinkedIn: linkedin.com/in/vsalescode
 * GitHub: github.com/vsalescode
 *
 * Focus: Backend with Java & Spring
 * Looking for internship opportunity
 */
