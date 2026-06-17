
```Java
// Oi! Meu nome e Daniel!
// Em constante evolução para me tornar um grande desenvolvedor 😀

public class Desenvolvedor {
    private final String nome = "Daniel Gabriel";
    private final String cargo = "Back-end Developer";
    private final List<String> techStack = Arrays.asList("Java",
                                                         "Python",
                                                         "JavaScript",
                                                         "Spring Boot",
                                                         "Docker",
                                                         "Linux");

    public void exibirPerfil() {
        System.out.println("Dev: " + nome + " | Cargo: " + cargo);
        
        // Demonstração de Lambda e Streams (Java 8+)
        System.out.print("Stack: ");
        techStack.stream()
                 .filter(tech -> !tech.equals("Linux"))
                 .forEach(tech -> System.out.print(tech + " "));
    }
}

 ```
