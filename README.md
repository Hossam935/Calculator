# Calculator


package com.HossamSabry;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        System.out.print("Enter First Integer : ");

        int x = input.nextInt();

        System.out.println();

        System.out.println("Enter Second Integer : ");
        int y = input.nextInt();

        System.out.println(" choose the number to proceed the operation :");

        System.out.println(" 1. ( + )");
        System.out.println(" 2. ( - )");
        System.out.println(" 3. ( * )");
        System.out.println(" 4. ( / )");

        int i = input.nextInt();

        if ( i == 1)
            System.out.println("The Result is = "  +(x+y));

        if ( i == 2)
            System.out.println("The Result is = " + (x-y));

        if ( i == 3)
            System.out.println("The Result is = " + (x*y));

        if ( i == 4)
            System.out.println("The Result is = " + (x/y));




    }


}
