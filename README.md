# Largest-among-Three-numbers

  import java.util.*;
  public class Main{
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
	    System.out.println("entrt thr number 1: ");
	     int a=sc.nextInt();
	     System.out.println("entrt thr number 2: ");
	     int b=sc.nextInt();
	     System.out.println("entrt thr number 3: ");
	     int c=sc.nextInt();
	     if(a>b&&a>c){
	         System.out.println(a);
	     }
	     else if(b>c) {
	    	 System.out.println(b);
	    	 
	     }
           else{
	     System.out.println(c);
	}
}
	
