# t2021-2-1

#Program.java -1

import java.util.Scanner;

public class Calci {

	public static void main(String[] args)
	{   
	    String operator;
	    Double num1,num2,result;
        Scanner scan=new Scanner(System.in);
        System.out.println("Choose an operator: Addition,Subtraction,Multiplication,Division");
        operator=scan.next();
        
        System.out.println("Enter first number : ");
        num1=scan.nextDouble();
        
        System.out.println("Enter the second number : ");
        num2=scan.nextDouble();
        
        switch(operator)
        {
        case "Addition":
        	result=num1+num2;
        	System.out.println(num1+" Addition "+num2+" = "+result);
        	break;
        case "Subtraction":
        	result=num1-num2;
        	System.out.println(num1+" Subtraction "+num2+" = "+result);
        	break;
        	
        case "Multiplication":
        	result=num1*num2;
        	System.out.println(num1+" Multiplication "+num2+" = "+result);
        	break;
        	
        case "Division":
        	result=num1/num2;
        	System.out.println(num1+" Division "+num2+" = "+result);
        	
        Default:
        	System.out.println("Invalid Opreator..!!");
        break;
        }
        System.out.println();
	}

}


# Program.java--4



import java.util.*;
import java.util.HashMap;

class Program
{
    private static int value;

    public static void main(String[] args)
    {
        ArrayList<Integer> arr=new ArrayList<Integer>(Arrays.asList(1,2,8,9,12,46,76,82,15,20,30));
        HashMap<Integer,Integer> res =new HashMap();

        for(int i=1;i<=9;i++)
        {
            res.put(i,value:0);
        }
        for(Integer a:arr)
        {
            for(int i=1;i<=9;i++)
            {
                if(a%i==0)
                {
                    res.put(i,res.get(i)+1);
                }
            }
            System.out.print(res);
        }
    }
}









































