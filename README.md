# Hello-World
First program
First program

using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
    {
       // Console.WriteLine($"Number of command line args= {args.Length}");
             
        foreach (string s in args)
        {
            System.Console.WriteLine("Hello " + s);
        }
    }
    }
}
