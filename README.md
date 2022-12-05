# Comp6.2

import java.util.Scanner;

public static void main(String[] args) {
            String s;
	    int len,i=0;
	    char ch;
	    Scanner sc = new Scanner(System.in); //read the input

	    System.out.println("Enter a string of characters:"); //print statement
	    s = sc.nextLine(); //read a string

	    len=s.length(); //length of the input string

	    for( i=0;i<len;i++) //for loop
	    {

	        ch=s.charAt(i); //reading char at a position i
	        System.out.println(ch); //printing that character
	      }

	        i=0;
	    }
	}
