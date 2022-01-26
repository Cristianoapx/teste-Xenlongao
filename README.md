# teste-Xenlongao
Teste Avanade
using System;
using System.Collections.Generic;
using System.Text;

namespace Dio
{
    class Xenlongao
    {
      
      // Exemplo de Entrada	
      //1
      ///7	
      
      //Exemplo de Saída
      //5
      
        static void Main(string[] args)
        {
            var testes = int.Parse(Console.ReadLine());

            for (int i = 0; i < testes; i++)
            {
                var esferas = int.Parse(Console.ReadLine());

                Console.WriteLine(esferas - Math.Floor(Math.Sqrt(esferas)));
            }
        }
    }
}
