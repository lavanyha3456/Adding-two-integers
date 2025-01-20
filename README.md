# Adding-two-integers
import java.util.Scanner;

public class AddTwoIntegers {

    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the first integer
        System.out.print("Enter the first integer: ");
        int first = scanner.nextInt();

        // Prompt the user to enter the second integer
        System.out.print("Enter the second integer: ");
        int second = scanner.nextInt();

        // Calculate the sum
        int sum = first + second;

        
        System.out.println("The sum of " + first + " and " + second + " is: " + sum);
    }
}


package add.two.integers;
public class AddTwoIntegers {

    public static void main(String[] args) {
      
        int first=10;
        int second=20;
        int sum=first+second;
        System.out.println(sum);  
    }
    
}

Output:
30
BUILD SUCCESSFUL (total time: 0 seconds)
