import java.util.*;
class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int a = scan.nextInt();
        if(a>0){
            System.out.println(a+ "this is positive number");
        }
        else if(a==0){
              System.out.println(a+ "this is zero");
        }
        else{
              System.out.println(a+"this is negative number");
        }
    }
}
