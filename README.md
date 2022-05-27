# ArkadasSayilar

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

       int num1=220;
       int num2=284;
       int toplam1=0;
       int toplam2=0;

       for (int i=1 ; i < num1 ;i++){
            if (num1%i==0){
                toplam1=toplam1+i;
            }
        }
        for (int i=1 ; i < num2;i++){
            if (num2%i==0){
                toplam2=toplam2+i;
            }
        }
        if (num1==toplam2 && num2==toplam1){
            System.out.println("Bu ik sayı arkadaştır");
        }else{
            System.out.println("Bu iki sayı arkadaş sayı değildir.");
        }
          }
}
