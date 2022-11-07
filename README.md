# NotOrtalamasi

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int mat,fiz,tar,kim,tür,muz;
        Scanner inp=new Scanner(System.in);
        System.out.println("Mat not:");
        mat=inp.nextInt();
        System.out.println("fiz not:");
        fiz=inp.nextInt();
        System.out.println("tar not:");
        tar=inp.nextInt();
        System.out.println("kim not:");
        kim=inp.nextInt();
        System.out.println("tür not:");
        tür=inp.nextInt();
        System.out.println("Muz not:");
        muz=inp.nextInt();
        double ortalama;
        ortalama=(mat+fiz+tar+kim+tür+muz)/6;
        boolean kosul = ortalama>= 60;
        String str =(kosul) ? "Geçti" : "Kaldı";
        System.out.println(str);
