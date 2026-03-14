# java-test-0001-final-12170-pratiksha
Final Project Assignment - This repository contains the complete final project code and documentation.
public class DiamondPattern {
    public static void main(String[] args) {
        int n = 5;

        for (int i = 1; i <= 2*n-1; i++) {
            int row = (i <= n) ? i : 2*n - i;

            for (int s = 1; s <= n-row; s++)
                System.out.print(" ");

            for (int j = 1; j <= 2*row-1; j++) {
                if (j == 1 || j == 2*row-1)
                    System.out.print("*");
                else
                    System.out.print(" ");
            }
            System.out.println();
        }
    }
}
