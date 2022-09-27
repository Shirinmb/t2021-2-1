# t2021-2-1
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
