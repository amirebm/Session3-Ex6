# Session3-Ex6

// ب ن ک درجه سانتیگراد را از ورودی گرفته و فارنهاینت آن را محاسبه کند


package com.personal.ex6;

import java.util.Scanner;

public class ex6 {

	public static void main(String[] args) {

		Scanner sc= new Scanner(System.in);
		System.out.println("Enter a the Santigerad degree");
		int degree= sc.nextInt();
		double faren= (degree * 1.8)+ 32;
		System.out.println("santigerade " + degree + " mishavad : " + faren);

}

}
