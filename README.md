# Automorphic-Number
check a given number is Automorphic number or not
import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int n,n1,d=0,c=0,s;
	    System.out.print("enter the value of n:");
	    n=sc.nextInt();
	    n1=n;
	    while(n!=0)
	    {
	        d=n%10;
	        c++;
	        n=n/10;
	    }
	    s=n1*n1;
	    if(s%(int)Math.pow(10,c)==n1)
	    {
	        System.out.print("it is a automorphic number");
	    }
	    else
	    {
	        System.out.print("it is not a automorphic number");
	    }
	}
}
