package haftabes;

import java.util.Scanner;

public class okangelirvergisi {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		// veri yarat
		double gelir;
		int statü;
		System.out.println("Statü giriniz");
		// statüsü sor
		Scanner input = new Scanner (System.in);
		statü = input.nextInt();
		System.out.println("Gelirinizi giriniz");
		gelir = input.nextDouble();
		if(statü == 1 ) {
			if(gelir <= 8350) {
				System.out.println("oranı %10");
			} else if ( gelir <= 33950) { 
			System.out.println("oranı %15");
			} else if  ( gelir <= 82250) {
				System.out.println("oranı %25");
			} else if (gelir <= 171550){
				System.out.println("oranı %28");
			} else if (gelir<= 372950){
			System.out.println("oranı %33");
			} else {
				System.out.println("oranı %35");
			}
		}
	}
}

