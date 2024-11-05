import java.util.*;
public class Main
{
	public static void main(String[] args) {
		int h;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the mark ");
		h=sc.nextInt();
		if (h<40)
		{
		System.out.println("fail");
		}
	    else if(h<=50)
	    {
	    System.out.println(" the grade is D");
	    }
	      else if (h<=60)
	    {
	    System.out.println("the grade is C");
	    }
	    else if(h<=75)
	    {
	    System.out.println("the grade is B");
	    }
	    else if(h<=85)
	    {
	    System.out.println("the grade is A");
	    }
	    else if(h>85)
	    {
	    System.out.println("outstanding");
	    }
	}
	}
