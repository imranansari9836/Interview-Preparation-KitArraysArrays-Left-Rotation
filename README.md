import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class Result {
    public static void main(String []args)
    {
       Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();//5
        int d=sc.nextInt();//4
        int arr[]=new int [n];
        for(int i=0;i<n;i++)
        {
            if(d>i)//4>0
            {
                arr[n-d+i]=sc.nextInt();//5-4+0
            }
            else{
                arr[i-d]=sc.nextInt();
            }
        }
        for(int i=0;i<n;i++)
        {
            System.out.print(arr[i]+" ");
        }
    }
}


    

