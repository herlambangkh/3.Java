package com.soal3;
import java.util.*;
public class Main {
    public static void main(String[] args) {

        System.out.println("==================STRING=====================");
        Scanner inputt = new Scanner(System.in);
        System.out.print("masukkan kata: ");
        String inputKata = inputt.next();   // Kata yang ingin dibandingkan
        System.out.print("masukkan kata pembanding: ");
        String pembandingKata = inputt.next(); // Kata pembanding

    boolean cek1 = inputKata.equals(pembandingKata);

    if (cek1) {
        System.out.println("Hasil : " + cek1);
    } else {
        System.out.println("Hasil : " + cek1);
    }
        System.out.println("\n\n\n============INTEGER===================");


    Scanner input1 = new Scanner(System.in);
        System.out.print("masukkan angka : ");
        int angka = input1.nextInt();
        System.out.print("masukkan angka pembanding: ");
        int angkaPembanding = input1.nextInt();
        System.out.println(angka == angkaPembanding);


        System.out.println("\n\n\n============FLOAT===================");

        Scanner input3 = new Scanner(System.in);
        System.out.print("masukkan angka : ");
        float angka3 = (float)input3.nextFloat();
        System.out.print("masukkan angka pembanding: ");
        float angkaPembanding3 = (float)input3.nextFloat();
        System.out.println(angka3 == angkaPembanding3);

        System.out.println("\n\n\n============DOUBLE===================");

        Scanner input2 = new Scanner(System.in);
        System.out.print("masukkan angka : ");
        double angka2 = input2.nextDouble();
        System.out.print("masukkan angka pembanding: ");
        double angkaPembanding2 = input2.nextDouble();
        System.out.println(angka2 == angkaPembanding2);



    }

}
