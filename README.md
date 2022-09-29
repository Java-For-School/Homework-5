# Assignment 5:

##### Exercise 29:

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        double first, second, third;
        Scanner scanner = new Scanner(System.in);
        
        first = scanner.nextDouble();
        second = scanner.nextDouble();
        third = scanner.nextDouble();
        
        if (first * first + second * second == third * third) System.out.println("Pythagorean triple");
        else if (first * first + third * third == second * second) System.out.println("Pythagorean triple");
        else if (third * third + second * second == first * first) System.out.println("Pythagorean triple");
        else System.out.println("Not a pythagorean triple");
    }
}
```
