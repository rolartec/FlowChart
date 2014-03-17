FlowChart
=========

This file is x flow chart
// by Reina Olarte

import java.util.Scanner;

public class FlowChartHungry
{
    public static void main(String[] args)
    {
        Scanner input = new Scanner(System.in);
        String thirsty;
        String Breakfast;
        //Print out commands
        System.out.println("You are Hungry");
        System.out.println("Get in line");
        System.out.println("Buy Lunch");
        
        //Ask if they are thirsty
        System.out.println("If you are thirsty press Y for yes N for no: ");
        thirsty = input.nextLine().toUpperCase();
        
        
        if (thirsty.equals("Y"))
            {
                //Ask if they have had Breakfast
                System.out.println("Have you had Breakfast press Y for yes N for no: ");
                Breakfast = input.nextLine().toUpperCase();
                    
                    if(Breakfast.equals("Y"))
                    {
                        System.out.println("\nBuy a Diet Coke");
                    }
                    else
                    {
                        System.out.println("\nBuy a Coke");
                    }
            
            }
        else
        {
            System.out.println("Buy a water");
        }

        System.out.println("Eat your Lunch");
        System.out.println("Return Tray");
        System.out.println("Your are full you may leave");
    }

}

