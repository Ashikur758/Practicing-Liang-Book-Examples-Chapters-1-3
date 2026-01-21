import java.util.Scanner;

public class LiangPractice {

    public static void main(String[] args) {

        // Chapter 1: Output
        System.out.println("Welcome to Java Programming");
        System.out.println("----------------------------");

        // Chapter 2: Input, Variables, Operators
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = sc.nextLine();

        System.out.print("Enter your marks: ");
        int marks = sc.nextInt();

        // Chapter 3: Decision Making
        System.out.println("\nStudent Name: " + name);

        if (marks >= 80) {
            System.out.println("Grade: A+");
        } else if (marks >= 70) {
            System.out.println("Grade: A");
        } else if (marks >= 60) {
            System.out.println("Grade: A-");
        } else if (marks >= 50) {
            System.out.println("Grade: B");
        } else {
            System.out.println("Grade: Fail");
        }

        sc.close();
    }
}
