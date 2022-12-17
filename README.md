# Exponential-Numbers
```
import java.util.Scanner;

public class ExponentialNumbers {
    public static void main(String[] args) {
        int a,b;

        Scanner input = new Scanner(System.in);

        System.out.print("Bir sayı giriniz: ");
        a = input.nextInt();

        System.out.print("Üs için bir sayı giriniz: ");
        b = input.nextInt();

        int total = 1;

        for (int i = 1; i <= b; i++) {
            total *= a;
        }
        System.out.println("Cevap: " + total);
    }
}
````
[Patika.dev](https://app.patika.dev/iremr)
