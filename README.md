# H.W17.12.2020
package com.company;

import java.util.Random;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner S = new Scanner(System.in);
        Random r = new Random();


        // 1. write for-loop which prints the numbers from 100 to 1000 in 100 steps: 100, 200, 300, .... 1000

        {
            System.out.println();
            for (int index1 = 100; index1 <= 1000; index1 = index1 + 100) {
                System.out.println(index1);
            }

            // write for-loop which prints numbers from 5 to -10 (minus)
        }
        System.out.println();
        for (int index = 5; index >= -10; index--) {
            System.out.println(index);
        }
        // *etar: use for-loop to print the power of 2: 1, 2, 4, 8, 16, 32, 64, ... 2048
        // generate random number from 1-3
        //use switch-case to print the number in hebrew.
        //for exmaple if 1 was generated -> print "ehad", 2 -> print "shtaim" , 3 -> print "shalosh"
        {
            System.out.println();
            for (int index2 = 1; index2 <= 2048; index2 *= 2)
                System.out.println(index2);
        }

        int random_number = r.nextInt(2) + 1;
        switch (random_number) {
            case 1:
                System.out.println("ehad");
                break;
            case 2:
                System.out.println("shtaim");
                break;

        }


    }
}











