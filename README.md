import java.util.*;
class Main 
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner (System.in);
         System.out.print("Enter n1 and n2 value");
        int n1 = sc.nextInt();
        int n2 = sc.nextInt();
        if(n1%10 > n2%10)
        {
            System.out.printf("%d %d",n2,n1);
        }
        if (n2%10 > n1%10)
        {
            System.out.printf("%d %d",n1,n2);
        }
        if (n1%10 == n2%10)
        {
            System.out.printf("%d %d",Math.max(n1,n2),Math.min(n1,n2));
        }
    }
}
