### Hi there 👋

```java
import java.util.List;
import java.util.Arrays;

public class AspiringLearner {
    private String name = "Rykon";
    private LocalDate dateOfBirth = LocalDate.of(1997, 3, 9);
    private String currentResidency = "Ho Chi Minh City, Vietnam";
    private String role = "Aspiring Learner";
    private List<String> spokenLanguages = Arrays.asList("vi_VN");
    private String[] languagesBeingLearned = {"Java", "C#", "JavaScript", "HTML", "CSS"};
    private String[] hobbies = {"Music", "Cooking", "Travelling", "Meditating"};

    public void sayHi() {
        System.out.println("Hello there! I am an aspiring learner from Ho Chi Minh city! I am learning a lot about programming and the English language, I hope to become a developer one day!");
    }
}

public class Main {
    public static void main(String[] args) {
        AspiringLearner me = new AspiringLearner();
        me.sayHi();
    }
}
