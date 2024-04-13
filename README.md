# javaday2
//basic understanding
import java.util.Scanner;
public class javadaytwo {
  public static void main(String[] args){
    System.out.println("Starting");
    Scanner sc =new Scanner(System.in);
    
    // if(k>l && k>m){
    //   System.out.println("k");
    // }
    // else if(l>m && l>k){
    //   System.out.println("l");
    // }
    // else{
    //   System.out.println(m);
    // }
    // use max fuction to solve 
int a=0;
int b=1;
int c=0;
Scanner ssc=new Scanner(System.in);
int k=ssc.nextInt();
int temp=0;
int t=0;
   for(int i=k;i>0;i=i/10){
     temp=i%10;
     t=t*10+temp;

   }
   System.out.println(t);
  }

  
}

 
