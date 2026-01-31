```java
// Java 17 is my weapon of choice

Developer joao = new Developer(
    "João Victor Sales",
    "vsalescode@gmail.com",
    "github.com/vsalescode"
);

joao.installMindset(List.of(
    "backend-passion",
    "clean-code",
    "coffee-dependency",
    "problem-solving"
));

Skills mySkills = new Skills(

    List.of(
        "Java 17",
        "JavaScript",
        "HTML5",
        "CSS3"
    ),

    List.of(
        "Spring Boot",
        "Spring Security",
        "OpenFeign",
        "Hibernate/JPA",
        "Swagger"
    ),

    List.of(
        "PostgreSQL",
        "MongoDB",
        "MySQL"
    ),

    List.of(
        "Git",
        "Maven",
        "Postman",
        "JWT",
        "Docker"
    ),

    List.of(
        "Microservices",
        "BFF",
        "REST APIs"
    )
);

BackendDeveloper developer =
    new BackendDeveloper(joao, mySkills);

try {

    while (developer.hasEnergy() ||
           developer.hasCoffee()) {

        developer.code();
        developer.documentWithSwagger();
        developer.containerizeWithDocker();

    }

} catch (BurnoutException e) {

    developer.takeBreak();
    developer.comeBackStronger();

}

```
