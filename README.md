# Program-to-Validate-given-numbes-can-form-Triangle-or-not-in-Java.
Program to Validate given numbes can form Triangle or not in Java.




import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);
        System.out.println("Enter Three Sides of a Triangle: ");
        int Side1=console.nextInt();
        int Side2=console.nextInt();
        int Side3 = console.nextInt();
       
        // Validation of Triangle:
        if((Side1+Side2>Side3)&&(Side1+Side3>Side2)&&(Side3+Side2>Side1)){
            System.out.println("Triangle is Valid...");
        }else {
            System.out.println("Not a Valid Triangle...");
        }

    }
}
