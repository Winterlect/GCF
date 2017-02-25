# GCF
Just a javascript WIP code for finding the GCF of 2 integers. Heavily inspired by practice USACO problems.
echo "# GCF" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Winterlect/GCF.git
git push -u origin master

import java.util.Scanner;

public class main {

	public static void main(String[] args) throws Exception {
		// TODO Auto-generated method stub
	       String N;
	       int sum = 0;
	       Scanner in = new Scanner(System.in);
	 
	       // Reads a single line from the console 
	       // and stores into name variable
	       N = in.nextLine();
	       
	       int result = Integer.parseInt(N);
	 
	       // Reads a integer from the console
	       in.close();         
	       
	       for(int i = 0; i < result; i++){
	    	   sum += i;
	    	   
	       }
	       
	 
	       // Prints sum to the console
	       System.out.println(sum);
	}

}
