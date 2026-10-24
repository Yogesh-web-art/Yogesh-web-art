public class Developer {
    String name        = "Yogeeshwar Jangam";
    String role        = "Java Full Stack Developer";
    String location    = "Hyderabad, India";
    String[] backend   = {"Java", "Spring Boot", "Spring Data JPA", "Hibernate", "REST APIs", "Maven"};
    String[] frontend  = {"JavaScript (ES6+)", "React", "HTML5", "CSS3", "Tailwind"};
    String[] database  = {"MySQL", "PostgreSQL"};
    boolean availableForHire = true;

    public void executeLifeCycle() {
        while (alive) {
            code();
            refactor();
            solveProblems();
            coffee.refill();
        }
    }
}
