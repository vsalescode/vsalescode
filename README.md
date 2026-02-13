```java
// Java 17 is my weapon of choice, and runs on coffee

Developer joao = new Developer(
    "João Victor Sales",
    "vsalescode@gmail.com",
    "linkedin.com/in/vsalescode",
    "portfolio-vsalescode.vercel.app/",
    "github.com/vsalescode"
);

joao.install(new LifePackageManager(List.of(
    "curiosity",
    "coffee-dependency",
    "debugging-skills"
)));

Skills mySkills = new Skills(
    List.of("Java 17", "JavaScript", "HTML/CSS", "Python"),
    List.of("Spring Boot", "Spring Security", "OpenFeign", "Swagger"),
    List.of("PostgreSQL", "MySQL", "MongoDB"),
    List.of("Git", "Maven", "Postman", "Docker")
);

BackendDeveloper developer =
    new BackendDeveloper(joao, mySkills);

try {

    while (developer.hasEnergy() ||
           developer.hasCoffee()) {

        developer.code();

    }

} catch (BurnoutException e) {

    developer.rest();
    developer.hydrate();
    developer.comeBackStronger();

}


```
