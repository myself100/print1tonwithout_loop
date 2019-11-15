# print1tonwithout_loop

import java.util.Scanner;
public class print1ton {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		print(n);
	}
	public static void print(int n) {
		if(n==1) {
			System.out.print("1 ");
			return;
		}
		else {
			print(n-1);                                                /////calling print function for recursion
			System.out.print(n + " ");                                 ////print 1 to n through recursion

		}
	}
}
