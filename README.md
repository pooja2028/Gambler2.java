# Gambler2.java
import java.util.*;
public class Gambleruc2
{
        public static void main(String[] args)
        {
                int Stake_Day=100;
                int Bet_per=1; 
                Random random=new Random();		
                int bet=random.nextInt();

                System.out.println("You can bet in a day" +Stake_Day);
                System.out.println("You can bet per game" +Bet_per);
		if(bet==1)
		System.out.println("win");
		else
		System.out.println("lose");

        }
}
