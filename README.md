# cift_dort_kati

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int num, total=0;


        Scanner input = new Scanner(System.in);

        do{
            System.out.println("Please enter a number : ");
            num = input.nextInt();

            if(num%4==0){
                total=total+num;
            }
        } while(num%2==0);
        System.out.println("total is : " + total);
    }
}
