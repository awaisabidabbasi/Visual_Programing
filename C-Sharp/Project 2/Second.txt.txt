using System;

class DataTypeLimits
{
    static void Main()
    {
        
        Console.WriteLine($"int (Int32) range: {int.MinValue} to {int.MaxValue}");
        
        
        Console.WriteLine($"long (Int64) range: {long.MinValue} to {long.MaxValue}");
        
        
        Console.WriteLine($"double range: {double.MinValue} to {double.MaxValue}");
        Console.WriteLine($"double Epsilon: {double.Epsilon}"); // Smallest positive value
        
        
        Console.WriteLine("\nString information:");
        Console.WriteLine($"Empty string: \"{string.Empty}\"");
        Console.WriteLine($"Max theoretical length: {int.MaxValue} chars");
        
        
        Console.WriteLine("\nAdditional C# Types:");
        Console.WriteLine($"decimal range: {decimal.MinValue} to {decimal.MaxValue}");
        Console.WriteLine($"DateTime range: {DateTime.MinValue} to {DateTime.MaxValue}");
    }
}