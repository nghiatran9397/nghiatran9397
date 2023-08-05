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
        System.out.println("Thanks for dropping by, have a safe and productive day!");
    }
}

public class Main {
    public static void main(String[] args) {
        AspiringLearner me = new AspiringLearner();
        me.sayHi();
    }
}
