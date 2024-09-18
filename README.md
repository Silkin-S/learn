import java.util.Scanner;

public class two {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.print("Введите десятичное число (-128 до 127): ");

        int a = scanner.nextInt();

        if (a < -128 || a > 127) {
            System.out.println("Ошибка: число должно быть в диапазоне от -128 до 127.");
        }
        else {

            String binary = Integer.toBinaryString(a);

            System.out.println("Знаковая двоичная запись: " + binary);
        }
        scanner.close();
    }
}
# learn
