# Multiplication-table
import java.util.Scanner;
public class MultiplicationTable {
    public static void main(String[] args) {
Scanner scanner = new Scanner(System.in);
// Prompt the user to enter a number
System.out.print("Enter a number to print its multiplication table: ");
int number = scanner.nextInt();
// Print the multiplication table
System.out.println("Multiplication Table of " + number + ":") ;
for (int i = 1; i <= 10; i++) {
            System.out.println(number + " x " + i + " = " + (number * i));
}
  scanner.close();
    }
}

output-

Enter the number for the multiplication table: 5
Multiplication Table for 5:
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

