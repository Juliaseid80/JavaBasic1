
import java.util.Scanner;

public class Person {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter pls your date of birth: ");
        int date = sc.nextInt();

        sc.nextLine();

        System.out.print("Enter your name: ");
        String name = sc.nextLine();

        System.out.print("Enter your surname: ");
        String surname = sc.next();

        System.out.println("Your full name is " + name + " " + surname);
    }
}
