# LeapYear

package leapyear;

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		int year;
		
		Scanner input = new Scanner(System.in);
		
		System.out.println("Enter the year you want to calculate:");
        year = input.nextInt();
		
		if (year%4 == 0 && year%100 != 0 || year%400 == 0) {
			System.out.println("It is a leap year.");
		}
		else {
			System.out.println("It is not a leap year.");
		}

	}

}
