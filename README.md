# Factorialcollege.java
com.java.college

package com.java.college;
import java.util.*;
public class Factorial {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		int x = input.nextInt();
		int temp = 1;
		for(int i=1; i<=x; i++) {
			temp = temp * i;
		}
		System.out.println("Factorial of" + x + "is" + "temp");

	}

}
