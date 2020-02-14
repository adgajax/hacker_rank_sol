import java.util.*;
import java.lang.*;
import java.io.*;

class Solution
{
    public static void main (String[] args) throws java.lang.Exception
    {
         
        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
        try{
        int n = Integer.parseInt(reader.readLine());
        System.out.println(fib(n));
        }catch(Exception e) {
            
        }
    }
    
    public static long fib(int n){
        long [] arrFib  = new long [3];
        arrFib[0] = 0;
        arrFib[1] = 1;
        int cntr = 0;
         
        while (cntr < n) {
         arrFib[2] = arrFib[0] + arrFib[1];
         arrFib[0] = arrFib[1];
         arrFib[1] = arrFib[2]; 
             
        if (arrFib[2] % 2 == 0){
            cntr++;
                     
        }  
             
        }
        
        return arrFib[2];
    
    }
}
