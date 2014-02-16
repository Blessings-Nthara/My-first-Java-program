My-first-Java-program
=====================

//NumberCompare.java
//A program to test the if condition

import java.util.Scanner;
public class NumberCompare 
{//open class
	public static void main(String[] args)
	{//open method
		Scanner input = new Scanner(System.in);
		int number1;
		int number2;
		
		System.out.println("Enter first integer");
		number1 = input.nextInt();
		
		System.out.println("Enter second integer");
		number2 = input.nextInt();
		
		if(number1<number2)
			System.out.printf("%d is less than %d\n", number1,number2);
		if(number1>number2)
			System.out.printf("%d is greater than %d\n",number1,number2);
		if(number1==number2)
			System.out.printf("%d is equal to %d\n",number1,number2);
		if(number1!=number2)
			System.out.printf("%d is not equal to %d\n", number1,number2);
		if(number1<=number2)
			System.out.printf("%d is lesser or equal to %d\n", number1,number2);
		if(number1>=number2)
			System.out.printf("%d is greater or equal to %d\n", number1,number2);
		
		
		
	}//end method

}//end class
