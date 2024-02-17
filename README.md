//# PrAcJava
//course Java in Prog Academy. Second hometask. Calculator.


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        var scanner = new Scanner(System.in);

        System.out.println("What is car's speed (km/h)?");
        var speed = scanner.nextDouble();

        System.out.println("How long is car's time in the way (h)?");
        var time = scanner.nextDouble();

        var result = speed * time;
        System.out.println("Distance of the way is: = " + result);
    }
}
