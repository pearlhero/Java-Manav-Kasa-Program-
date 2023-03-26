# Java-Manav-Kasa-Program-
Java-Manav Kasa Programı

import java.util.Scanner;
public class Baslangic {
    public static void main(String[] args) {
        double armut = 2.14, elma = 3.67, domates = 1.11, muz = 0.95, patlıcan = 5.0;
        int aKg, eKg, dKg, mKg, pKg;

        Scanner inp = new Scanner(System.in);
        System.out.print("Armut kaç kilo : ");
        aKg = inp.nextInt();

        System.out.print("Elma kaç kilo : ");
        eKg = inp.nextInt();

        System.out.print("Domates kaç kilo : ");
        dKg = inp.nextInt();

        System.out.print("Muz kaç kilo : ");
        mKg = inp.nextInt();

        System.out.print("Patlıcan kaç kilo : ");
        pKg = inp.nextInt();

        double toplamTutar = (aKg * armut) + (eKg * elma) + (dKg * domates) + (mKg * muz) + (pKg * patlıcan);
        System.out.print("Toplam tutar : " + toplamTutar);
    }
}
