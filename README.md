# String-Assignment
package com.company;
import java.util.Scanner;
public class Main {
    public static void main( String[] args )
    {
        Scanner keyboard= new Scanner(System.in);
        String name;
        String lastname;
        int age;
        System.out.print( " What is your name? " );
        name = keyboard.next();
        System.out.print( "What is your last name " + name + "? " );
        lastname=keyboard.next();
        System.out.print( "How old are you " + name+ "?");
        age=keyboard.nextInt();
        System.out.println( name + " is your first name "+ lastname + " is your last name " +  " and you are " + age );
    }
}
