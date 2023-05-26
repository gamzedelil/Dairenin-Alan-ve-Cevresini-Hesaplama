# Dairenin-Alan-ve-Cevresini-Hesaplama

import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        int r;
        double pi = 3.14; 
        double alan, cevre; 
        
        Scanner input = new Scanner(System.in);
        System.out.print("Dairenin yaricapini girin:");
        r = input.nextInt();
    
        alan = (pi*r*r);
        cevre = (2*pi*r);
        System.out.println("Dairenin alani:" +alan);
        System.out.println("Dairenin cevresi:" +cevre);
         alan = input.nextDouble();
        cevre = input.nextDouble();
        
    }
}
