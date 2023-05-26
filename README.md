# Dairenin-Alan-ve-Cevresini-Hesaplama

import java.util.Scanner;

class Main {
    public static void main(String[] args) {
       
       
        int r;
        double pi = 3.14; 
        double alan, cevre, aci, formul; 
        
        
        Scanner input = new Scanner(System.in);
        System.out.print("Dairenin yaricapini girin:");
        r = input.nextInt();
         System.out.println(" Merkez aciyi girin: ");
         aci = input.nextDouble();
         
        alan = (pi*r*r);
        cevre = (2*pi*r);
        formul =  (pi * (r*r) * aci) / 360;
        System.out.println("Dairenin alani:" +alan);
        System.out.println("Dairenin cevresi:" +cevre);
        System.out.println(" Merkez aciyla hesaplanan alan:"+formul);
         alan = input.nextDouble();
        cevre = input.nextDouble();
        formul = input.nextDouble();
        
    }
}
    }
}
