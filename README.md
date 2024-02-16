import java.util.Scanner;

public class calculator {
    public static void main(String[]args){
        int a,b,c,ch;
        System.out.print("enter any two number");
        Scanner s=new Scanner(System.in);
        a=s.nextInt();
        b=s.nextInt();
        System.out.print("enter your choice");
        ch=s.nextInt();
        switch(ch)
        {
            case 1: c=a+b;
            System.out.print("addition"+c);
            break;
            case 2: c=a-b;
            System.out.print("substraction"+c);
            break;
            case 3: c=a*b;
            System.out.print("multiplication"+c);
            break;
            case 4: c=a/b;
                System.out.print("division"+c);
                break;
            case 5: c=a%b;
                System.out.print("remeinder"+c);
                break;
            default:
                System.out.print("invalid choice.....");



        }
    }
}
