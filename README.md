# alkfejl2 gyakorlati segédanyagok

## Első feladat: Módosítsd úgy a generált kódot, hogy üdvözölje a felhasználót:
`
using System;

namespace gy01
{
    class Program
    {
        static void Main(string[] args)
        {
			Console.WriteLine("What's your name?");
            string name = Console.ReadLine();
			//Console.WriteLine($"Your answer: {name}!");
			
			//Console.WriteLine("Hello " + name + "!");

        }
    }
}
`

### Hasznos linkek:
[dotnet new parancs paraméterei](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new)