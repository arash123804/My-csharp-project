# My-csharp-project
For school
using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter a number: ");
        string input = Console.ReadLine();

        int number;
        if (int.TryParse(input, out number))
        {
            int result = number * 2;
            result *= 5;
            result += 10;
            result /= 10;
            result -= 1;

            Console.WriteLine("Final result: " + result);
        }
        else
        {
            Console.WriteLine("Invalid input.");
        }
    }
}

