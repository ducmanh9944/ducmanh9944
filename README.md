```java
class Person {
    private String name;
    private String title;
    private int age;
    private String school;
    public Person(String name, String title, int age, String school) {
        this.name = name;
        this.title = title;
        this.age = age;
        this.school = school;
    }
    public void introduce() {
        System.out.println("Hi, my name is " + name + ", I'm a " + title + " studying at " + school +".");
    }
}
public class Main {
    public static void main(String[] args) {
        Person person = new Person("Manh", "Mobile Developer", 19, "PTIT");
        person.introduce();
    }
}
```
```java
run:
Hi, my name is Manh, I'm a Mobile Developer studying at PTIT.
BUILD SUCCESSFUL (total time: 0 seconds)
```
