import java.util.Scanner;



public class Main
{
    public static void problemOne()
    {
        Scanner scan = new Scanner(System.in);


        System.out.println("Enter v1: ");
        int v1 = scan.nextInt();
        System.out.println("Enter t1: ");
        int t1 = scan.nextInt();
        System.out.println("Enter v2: ");
        int v2 = scan.nextInt();
        System.out.println("Enter t2: ");
        int t2 = scan.nextInt();

        int d1 = v1 * t1;
        int d2 = v2 * t2;

        if(d1 > d2)
        {
            System.out.println("The distance between d1 and d2 is: " + (d1 - d2));
        }
        else if (d2 > d1)
        {
            System.out.println("The distance between d2 and d1 is: " + (d2 - d1));
        }
        else
        {
            System.out.println("The distances are equal.");
        }
    }

    public static boolean problemTwo(int num)
    {
        if (num < 0) {
            return false; // לא ייתכן שפלינדרום יהיה מספר שלילי
        }

        int copied_num = num;
        int reversed_num = 0;

        while (num > 0) {
            int digit = num % 10;
            reversed_num = reversed_num * 10 + digit;
            num /= 10;
        }

        return (copied_num == reversed_num);
    }

    public static void main(String[] args)
    {
        Scanner scan = new Scanner(System.in);
        
//        problemOne(); // שאלה 1

        System.out.println("Enter num: "); //שאלה 2
        int num = scan.nextInt();

        if(problemTwo(num))
        {
            System.out.println("The number is a palindrome.");
        }

        else
        {
            System.out.println("The number isn't a palindrome.");
        }
    }
}
