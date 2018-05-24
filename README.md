import java.util.Scanner;

public class Game {
    
public static void main(String[] args) {
Scanner input = new Scanner(System.in);
String yes, name, capital;
yes = "yes"; 	
System.out.println("Enter your name");
name= input.nextLine();
System.out.println("Welcome to ‘Buy or Not’!");
System.out.println("You are starting out with $0. For every question you get right, you will receive $100. Use only uppercase letters.");
System.out.println("Is the capital of New Jersey ‘Trenton’?");
capital=input.nextLine();
if (capital=="yes")
{
	System.out.println("You are correct! You have gained $100");
}
else
{
	System.out.println ("Sorry. You lost $100");
}

    }
}
