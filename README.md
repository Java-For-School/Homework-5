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
##### Exercise 30:

```java
import java.util.Scanner;
import java.lang.Math;
class Main {
    public static void main(String[] args) {
        boolean first, second;
        int firstAge, secondAge;
        
        Scanner scanner = new Scanner(System.in);
        
        first = Character.compare(scanner.next().charAt(0), 'm') == 0 ? true : false;
        second = Character.compare(scanner.next().charAt(0), 'm') == 0 ?  true : false;
        
        firstAge = scanner.nextInt();
        secondAge = scanner.nextInt();
    
        if (first ^ second && Math.abs(firstAge - secondAge) <= 5) System.out.println("The match is accepted");
        else System.out.println("The math is unacceptable");
    }
}
```
##### Exercise 31:

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        double first, second, third;
        Scanner scanner = new Scanner(System.in);
        
        first = scanner.nextDouble();
        second = scanner.nextDouble();
        third = scanner.nextDouble();
        
        if (first + second <= third || third + second <= first || first + third <= second) System.out.println("Invalid triangle");
        
        else System.out.println("Valid triangle");
    }
}
```
