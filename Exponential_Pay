//Rodrigo Espinoza


/*Initial:1
Each day a person works is doubled*/
//import java scanner
//ask user the number of days they worked
/*use while loop if user inputs less than 1
and ask them again until condition breaks*/
//create for loop(inital; boolean expression; update)
//let initial be 1 and update by 1
//counter must be less than or equal to # days worked
/*equation in loop
(2^n)/2 due to exponential growth and taking into acount 1
total=amount+total*/
//print pay of each day worked in seprate lines
//loop closes
//print total amount made
//close scanner

import java.util.Scanner;

public class Exponential_Pay
{
    public static void main(String[] args)
    {
        try(Scanner daddy=new Scanner(System.in))
        {
        int days;
        int count;
        double amount=0;
        double total=0;
        System.out.println("How many days have you worked?");
        days=daddy.nextInt();
        while(days<1)
        {
            System.out.println("PLease enter a value greater than or equal to 1.");
            days=daddy.nextInt();
        }
        for (count=1;count<=days;count++)
        {
            amount=Math.pow(2,count)/2; //2^(count)/2 converted to integer
            System.out.printf("Pay for Day "+count+":$%.2f\n", amount);
            total=amount+total; //amount is inside and not a variable
        }
        System.out.printf("Total Pay For "+days+" Days:$%.2f", total);
        } //try loop brace
    }
}
