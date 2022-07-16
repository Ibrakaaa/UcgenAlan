# UcgenAlan
## Java-101 Ucgen Alan ve Cevre Hesaplama
 [](www.patika.dev)


import java.util.Scanner;

public class UcgenCevre {
    public static void main(String[] args) {

        double a,b,c;


        Scanner girdi=new Scanner(System.in);


        System.out.print("1.kenarı giriniz : ");
        a=girdi.nextInt();

        System.out.print("2.kenarı giriniz : ");
        b=girdi.nextInt();

        System.out.print("3.kenarı giriniz : ");
        c=girdi.nextInt();


        double u,cevre;
        double alan;

        u = (a+b+c)/2;
        cevre = 2*u;
        alan = Math.sqrt(u*(u-a)*(u-b)*(u-c));

        System.out.println("Üçgenin çevresi : "+cevre+ "\nÜçgenin alanı : "+alan);

      



    }
    }
