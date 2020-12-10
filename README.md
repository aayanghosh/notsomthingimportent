# notsomthingimportent

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		for (int n = 1;n<=10;n++)   
        {
            System.out.println(n);
        }
        
        int sum = 0;
        for(int a=1; a<=10; a++)
        {
            sum += a;
        }
        
        System.out.println("Sum: " + sum);
        
        
        Scanner console = new Scanner(System.in);
        int num;
        
        System.out.print("Enter any + number: ");
        num = console.nextInt();
                
        System.out.println("Multiplication Table of " + num);
        
        for(int i=1; i<=12; i++)
        {
            System.out.println(num +" x " + i + " = " + (num*i) );
        }
        
        
	}
}

