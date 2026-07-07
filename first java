// Change made directly on GitHub for Jenkins test

import java.util.Scanner;

public class PalindromeCheck {
    public static boolean isPalindrome(int num) {
        String original = String.valueOf(num);
        String reversed = new StringBuilder(original).reverse().toString();
        return original.equals(reversed);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        if (isPalindrome(number)) {
            System.out.println(number + " is a palindrome");
        } else {
            System.out.println(number + " is not a palindrome");
        }

        sc.close();
    }
}
