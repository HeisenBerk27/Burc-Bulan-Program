# Bur-Bulan-Program
www.patika.dev
-------------------


import java.util.Scanner;

public class Burç {
	
public static void main(String[] args) {
	
int ay, gün;


    Scanner scanner = new Scanner(System.in);
    System.out.print("Doğum Ayınızı Giriniz : ");
    ay = scanner.nextInt();
    System.out.print("Doğum Gününüzü Giriniz : ");
    gün = scanner.nextInt();

    if(ay == 1){
        if(gün >= 1 && gün <= 21){
            System.out.println("Oğlak Burcu");
        }else{
            System.out.println("Kova Burcu");
        }
    }else if(ay == 2){
        if(gün >= 1 && gün <= 19){
            System.out.println("Kova Burcu");
        }else{
            System.out.println("Balık Burcu");
        }
    }else if(ay == 3){
        if(gün >= 1 && gün <= 20){
            System.out.println("Balık Burcu");
        }else{
            System.out.println("Koç Burcu");
        }
    }else if(ay == 4){
        if(gün >= 1 && gün <= 20){
            System.out.println("Koç Burcu");
        }else{
            System.out.println("Boğa Burcu");
        }
    }else if(ay == 5){
        if(gün >= 1 && gün <= 21){
            System.out.println("Boğa Burcu");
        }else{
            System.out.println("İkizler Burcu");
        }
    }else if(ay == 6){
        if(gün >= 1 && gün <= 22){
            System.out.println("İkizler Burcu");
        }else{
            System.out.println("Yengeç Burcu");
        }
    }else if(ay == 7){
        if(gün >= 1 && gün <= 22){
            System.out.println("Yengeç Burcu");
        }else{
            System.out.println("Aslan Burcu");
        }
    }else if(ay == 8){
        if(gün >= 1 && gün <= 22){
            System.out.println("Aslan Burcu");
        }else{
            System.out.println("Başak Burcu");
        }
    }else if(ay == 9){
        if(gün >= 1 && gün <= 22){
            System.out.println("Başak Burcu");
        }else{
            System.out.println("Terazi Burcu");
        }
    }else if(ay == 10){
        if(gün >= 1 && gün <= 22){
            System.out.println("Terazi Burcu");
        }else{
            System.out.println("Akrep Burcu");
        }
    }else if(ay == 11){
        if(gün >= 1 && gün <= 21){
            System.out.println("Akrep Burcu");
        }else{
            System.out.println("Yay Burcu");
        }
    }else if(ay == 12){
        if(gün >= 1 && gün <= 21){
            System.out.println("Yay Burcu");
        }else{
            System.out.println("Oğlak Burcu");
        }
    }else{
        System.out.println("Geçersiz bir ay girdiniz !");
    }
}
}
