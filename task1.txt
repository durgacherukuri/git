package task1;
import java.util.Scanner;

public class task1 {

	int invalidvalue;
	static int number;
	static final int GUESS_NUMBER =45;
	    public static void main(String[] args) {
boolean invalidvalue = true;
	        Scanner sc = new Scanner(System.in);
	        while (invalidvalue) {
	        	
	            System.out.println("Enter a number b/w 1-100: ");
	            number= sc.nextInt();
	            if (number == GUESS_NUMBER) {
	            	System.out.print("Congratulations, you guessed the number right!");  
	            }
	            else if(number<GUESS_NUMBER) {
	                System.out.println("your guess is too smaller than guess number");
	            }
	                else {
	                	 System.out.println("your guess is greater than guess number");
	            }
	        }
	    }