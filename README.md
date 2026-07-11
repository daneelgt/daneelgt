<h1 align="center"> <img src="https://media3.giphy.com/media/l4FGr7tMjH3ajuwy4/giphy.gif" width="4%"><a href="https://daneelgt.me" target="_blank">daneelgt</a> github page <img src="https://media3.giphy.com/media/l4FGr7tMjH3ajuwy4/giphy.gif" width="4%"> </h1>

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
