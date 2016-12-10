# Java-01


===========================================

01. "Hello, Java!"

public class NewStart {
    public static void main(String[] args){
        System.out.println("Hello, Java!");
    }
}

===========================================

===========================================

02. Expression

public class ex02_Expression {
    public static void main(String[] args) {
        System.out.println((3522 + 52353) * 23 - (2336 * 501 + 23432 - 6743) * 3);
    }
}

===========================================

===========================================

03. Numbers from 1 to 20

public class ex03_Nums_1_To_20 {
    public static void main(String[] args) {
        for (int i = 1; i <= 20; i++) {
            System.out.println(i);
        }
    }
}

===========================================

===========================================

04. Triangle of 55 stars

public class ex04_Triangle_Of_Stars {
    public static void main(String[] args) {
        for (int i = 1; i <= 10; i++) {
            for (int j = 0; j < i; j++) {
                System.out.print("*");
            }
            System.out.println();

===========================================

===========================================

05. Rectangle area

import java.util.Scanner;

public class ex05_Rectangle_Area {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);
        int a = Integer.parseInt(console.nextLine());
        int b = Integer.parseInt(console.nextLine());

        int area = a * b;
        System.out.println(area);
    }
}

===========================================

===========================================

06. Square of stars

import java.util.Scanner;

public class ex06_Square_Of_Stars {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);
        int num = Integer.parseInt(console.nextLine());

        // top part
        for (int i = 0; i < num; i++) {
            System.out.print("*");
        }
        System.out.println();
        // middle part
        for (int i = 0; i < num - 2; i++) {
            System.out.print("*");
            for (int j = 0; j < num - 2; j++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }
        // bottom part
        for (int i = 0; i < num; i++) {
            System.out.print("*");
        }
    }
}

===========================================