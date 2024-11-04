package pertemuan6;

/**
 *
 * @author Afra Syavina
 */
import java.util.Scanner;

public class PerbandinganDuaNilai {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String ulangi;

        do {
            System.out.println("=======Program Perbandingan Nilai=======");
            System.out.print("Masukkan nilai pertama : ");
            int nilaiPertama = scanner.nextInt();
            System.out.print("Masukkan nilai kedua : ");
            int nilaiKedua = scanner.nextInt();

            if (nilaiPertama > nilaiKedua) {
                System.out.println("Hasil : " + nilaiPertama + " Lebih besar dari " + nilaiKedua);
            } else if (nilaiPertama < nilaiKedua) {
                System.out.println("Hasil : " + nilaiPertama + " Lebih kecil dari " + nilaiKedua);
            } else {
                System.out.println("Hasil : " + nilaiPertama + " Sama dengan " + nilaiKedua);
            }

            System.out.println("========================================");
            System.out.print("Ulangi Aktifitas ? (Ya/Tidak) : ");
            ulangi = scanner.next();
        } while (ulangi.equalsIgnoreCase("Ya"));

        scanner.close();
    }
}

