# the-greater-of-the-two-numbers
import java.util.Scanner;

public class loops {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("enter the 1st number");
        int x = s.nextInt();
        System.out.println("enter the 2nd number");
        int y = s.nextInt();
        if(x>y){
            System.out.println(x);
        }
        else{
            System.out.println(y);
        }
        
        }

    }
