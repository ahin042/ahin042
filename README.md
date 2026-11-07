```java
public class ShowInfo {
    public static void main(String[] args) {
        BackendDeveloper ahin = BackendDeveloper.builder()
                .name("ahin")
                .school("Daegu Software Meister High School")
                .techStack(List.of("Java", "Spring Boot", "Python"))
                .tools(List.of("Git", "GitHub", "IntelliJ IDEA", "PyCharm", "Figma", "Expo GO"))
                .build();
        ahin.run();
    }
}
```
