# ÖDEV
## Dördün Katlarını Toplayan Program
```
import java.util.Scanner;

public class denden {
    public static void main(String[] args) {
        int n, total = 0;
        Scanner scan = new Scanner(System.in);

        do {
            System.out.print("Bir Sayı Giriniz : ");
            n = scan.nextInt();
            if (n % 4 == 0) {
                total += n;
            }
        } while (n %2==0);
        System.out.print("Toplam : "+total);
    }
}
```
# Patika Profilim :
<a href='https://academy.patika.dev/profile'><u>Patika Profilim</u></a>