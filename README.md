# java-area-perimeter
---------------------java-------------------
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Input length and breadth of the ground
        int length = scanner.nextInt();
        int breadth = scanner.nextInt();

        // Calculate perimeter for rope
        int perimeter = 2 * (length + breadth);

        // Calculate area for carpet
        int area = length * breadth;

        System.out.println(perimeter);
        System.out.println(area);
    }
}
