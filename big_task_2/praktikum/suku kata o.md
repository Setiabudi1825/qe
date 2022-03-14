import java.util.Scanner;
public class test2
{
    public static void main (String[ ] args)
    {
        Scanner in = new Scanner(System.in);
        System.out.println("Masukkan kata : ");
        String teks = in.nextLine();
        System.out.println("Masukkan suku kata : ");
        String kata = in.nextLine();
        int jumlah = 0;
        int indeks;
        indeks = teks.indexOf(kata);
        while (indeks >= 0)
        {
            ++ jumlah;
            indeks += kata.length();
            indeks = teks.indexOf(kata, indeks);
        }
        System.out.println("Teks berisi kata " + kata + " sebanyak " + jumlah + ".");
    }
}