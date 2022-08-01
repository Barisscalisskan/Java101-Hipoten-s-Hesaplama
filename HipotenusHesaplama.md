//Hipotenüs Hesaplayan Program

import java.util.Scanner;

public class kdvTutarHesaplama {

public static void main(String[] args) {

Scanner girdi = new Scanner(System.in);

int a,b;
double c;

System.out.print("1. Kenarı Gİrin :");

a = girdi.nextInt();

System.out.println("2. Kenarı Girin :");

b = girdi.nextInt();

c = Math.sqrt((a * a) + (b * b));

System.out.println("Hipotenüs :" + c);