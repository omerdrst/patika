import java.util.Scanner;

public class Main {
    static int usHesabi(int sayi1, int sayi2)
    {
        int sonuc = 1;
        
        for (int i = 1; i <= sayi2; i++)
        {
            sonuc = sonuc * sayi1;
        }


        return sonuc;
    }

    public static void main(String[] args) {
        int taban, usSayisi;
        Scanner scan = new Scanner(System.in);

        System.out.print("Taban Sayisini Giriniz : ");
        taban = scan.nextInt();

        System.out.print("Us Olacak Sayiyi Giriniz : ");
        usSayisi = scan.nextInt();

        System.out.println(taban + " Ussu " + usSayisi + " : " + usHesabi(taban,usSayisi));
    }
}
