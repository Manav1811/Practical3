# Practical3
package part1;
import java.util.*;

public class Practical3 {
	

	    public static void main(String[] args) {
	        Scanner sc=new Scanner(System.in);
	        System.out.println("Enter no of test case: ");
	        int t=sc.nextInt();
	        int n1,n2;
	        for(int i=0;i<t;i++)
	        {
	            n1=sc.nextInt();
	            n2=sc.nextInt();

	            if(n1%10 == n2%10)
	            {
	                System.out.println("true");
	            }
	            else{
	                System.out.println("false");
	            }
	        }

	    	//Created by Manav_21CE063.
	    }
	}
