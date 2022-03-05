# Factorial

// Online C# Editor for free
// Write, Edit and Run your C# code using C# Online Compiler
using System;
public class HelloWorld{
    
    public static void Main(String[] args){
      int n = int.Parse(Console.ReadLine());
      int fact = factorial(n);
      Console.WriteLine(fact);
    }
    
    public static int factorial(int n){
        if( n == 0 || n == 1){
            return 1;
        }
        int fact = factorial(n - 1) * n ;
        return fact;
    }
    
}
