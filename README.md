public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("первое ");
        int a = scanner.nextInt();
        System.out.print("второе ");
        int b = scanner.nextInt();
        System.out.print("действие ");
        char operation = scanner.next().charAt(0);

        if (operation == '+') {
            int result = a + b;
            System.out.print("результат " + result);
        }else if (operation == '-') {
            int result = a - b;
            System.out.print("результат " + result);
        }else if (operation == '*') {
            int result = a * b;
            System.out.print("результат " + result);
        }else if (operation == '/') {
            int result = a / b;
            System.out.print("результат " + result);
        }else if (operation == '%') {
            int result = a % b;
            System.out.print("результат " + result);
        }else {
            System.out.println("Указаная операция не поддерживается");
        }
    }
}
