# absolute-value
import java.lang.Math;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
     Scanner sc=new Scanner(System.in);
     int n=sc.nextInt();
     if(n<0){
       int absn=(n-n)-(n);
       System.out.println("the absolue value of "+n+" is "+absn);
     }
     else{
       System.out.println(n);
     }
  }
}
