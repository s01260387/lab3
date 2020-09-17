# lab3
using System;

class MainClass {
  public static void Main (string[] args) {

  
        Console.Write("Enter the temperature in celsius: "); 
        int celsius = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Fahrenheit = {0}", celsius * 18 / 10 + 32);
        if (celsius < 0)
        {
          Console.WriteLine("This temperature is below freezing of 32 degrees Farenheit");
        }
        if (celsius > 100)
        {
          Console.WriteLine("This temperature is above boiling point of 212 degree Farenheit");
        }
      


  
    


  }
}
