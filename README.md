# PositiveNegativecheck
Using this  code you can check numbers are positive or negative 
package mypackage;
import java.util.Scanner;
public class EvenorOdd{
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
  System.out.print("Enter  Number:");
    double n=sc.nextDouble();
    if(n>0) {
    	System.out.print("Positive Number :"+n);
    }else if(n==0) {
    	System.out.print("Zero:"+n);
    	
    }else {
    	System.out.print("Negative Number:");
    }
	}

	}
