import java.util.Scanner;

public class Powtorenie {
    public Powtorenie() {
    }

    public static void main(String[] args) {
        Scanner bebra = new Scanner(System.in);
        System.out.print("Введите текст: ");
        String a = bebra.nextLine();
        System.out.println("Текст: " + a);
        System.out.print("Введите число: ");
        int b = bebra.nextInt();
        System.out.println("Число: " + b);
        if (b > 0) {
            for(int i = 1; i <= b; ++i) {
                System.out.println(a);
            }
        } else {
            System.out.println(a);
        }

    }
}
