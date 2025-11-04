# LatihanUKLSoalSedangNo1-Jasmine-Salsabila-F.-W.-XRPL2-
Fungsi dari program ini adalah untuk mengetahui faktorial dari bilangan bulat positif. Lalu cara kerjanya adalah dengan cara menginputkan bilangan oleh user.

Berikut adalah kode programnya:
    
    import java.util.Scanner;
    public class SoalSedangNo1 {
    
    static long faktorial(int n) {
        long hasil = 1;
        for (int i = 1; i <= n; i++) {
            hasil *= i;
        }
        return hasil;
    }

    public static void main(String[] args) {
        Scanner inputan = new Scanner(System.in);

        System.out.println("Masukkan Bilangan Bulat Positif: ");
        int bilanganFaktorial = inputan.nextInt();
        long hasil = faktorial(bilanganFaktorial);
        System.out.println("Faktorial dari "+ bilanganFaktorial +" adalah "+ hasil);

        inputan.close();
        }
    }
