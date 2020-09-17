# TestPlatform
Песочница для запуска консольных Java-программ под Android

![screenshot](screenshot.png)

**Ограничения:**

Главный класс должен располагаться в корне (пример - MyProgram.java) запуск `"Run with coverage"`

![tree](tree.png)

Пример консольной программы
```java
import java.util.Scanner;
public class MyProgram{
    public static void main(String[] args){
        Scanner in = new Scanner(System.in);
        System.out.println("Enter two numbers");
        int x = in.nextInt(), y = in.nextInt();
        int sum = x + y;
        System.out.println("Their sum is " + sum);
    }
}
```