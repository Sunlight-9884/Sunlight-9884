package CrazyRobot;

import java.util.InputMismatchException;
import java.util.Scanner;

public class CrazyRobot {

//Sai Nay Lin Htun
//This program is use IDE	
//15.Assignment_CrazyRobot	
	public static void main (String[] args)throws ClassNotFoundException  {
		Distionary d = new Distionary();
		d.distionary();
		
		throw new ClassNotFoundException("Thank , Again Test Program");
	}
}
		
		
class Distionary{
	public void distionary() throws ClassNotFoundException {

	try (Scanner sc = new Scanner(System.in)){
			System.out.println("Hello! My name is Robot Bot."); 
			System.out.println("..................");
			System.out.println("1.How are you?" );
			System.out.println(" 2.Who are you Owner?" );
			System.out.println(" 3.Where are You go Owner? " );
			System.out.println(" 4.When time attend Class?" );
			System.out.println(" 5.Hello! Mr.CrazyBot I am Tiring" );
			int Name=Integer.parseInt(sc.nextLine());
			switch(Name){
			case (1):
				System.out.println("I am Fine "
						+ "\n continue Key_Number(1,2..)");
			  Name = sc.nextInt();
		
			case (2):
				System.out.println("Mr. sai Nay Lin Htun"
						+ "\n continue Key_Number(1,2..)");
						
			 Name = sc.nextInt();
		
			case (3):
				System.out.println("Go to job or call phone - 09796363981"
						+ "\n continue Key_Number(1,2..)");
			 Name = sc.nextInt();
		
			case (4):
				System.out.println("7:30 or 8:00"
						+ "\n continue Key_Number(1,2..)"	);
			 Name = sc.nextInt();
		
			case (5):
				System.out.println("Oh! Bro, Fighing_you can do"
						+ "\n continue Key_Number(1,2..)");
			 Name = sc.nextInt();
			break;
			 default :
				 System.out.println("I am not Understand,Please help me!"
						 				+ "\n Learn Language...........	?");
			}
			Language.language();
			
	}	
			catch(InputMismatchException e) {
				
				System.out.println("Thank For use my Robot");				
			}
			catch(Exception e) {
				
				System.out.println("Thank For use my Robot");
			
								
	}
				
}
	
}
		


	
class Language extends CrazyRobot  {	
	public static void language( )throws ClassNotFoundException{
		try (Scanner sc = new Scanner(System.in)){
			System.out.println("I am not understand! please Teach me");
			System.out.print("Userinput :");
			String str =sc.nextLine();
			//System.out.println("Userinput :"+ str);
			System.out.print("Robot :");
			String str1 = sc.nextLine();
			//System.out.println("Robot Bot : "+ str1);
		}
			
}

		
	public static void output(String str,String str1) throws ClassNotFoundException {
		try {
			System.out.print("Robot :"+ str);
			System.out.println("Robot Bot : "+ str1);
		
				throw new  ClassNotFoundException ();

		
	}
	finally{
		System.out.println("Thanks,Have anice day");
	}

}
}	
	
	
	

					
	

		
	


	




	

	

	
	
 
 
 
		
