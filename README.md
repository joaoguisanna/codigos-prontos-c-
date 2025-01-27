# codigos-prontos-c-

/*
 * Created by SharpDevelop.
 * User: Aluno_Manha
 * Date: 27/01/2025
 * Time: 10:09
 * 
 * To change this template use Tools | Options | Coding | Edit Standard Headers.
 */
using System;

namespace aula
{
	class Program
	{
		public static void Main(string[] args)
		{
			int numero = 20;
			double preco = 15.99;
			char letra = 'R';
			bool verificacao = true;
			string nome = "Rodolfo";
			
			Console.WriteLine(numero);
			Console.WriteLine(preco);
			Console.WriteLine(letra);
			Console.WriteLine(verificacao);
			Console.WriteLine(nome);
			
			numero = 55;
			preco = 8.55;
			letra = 'B';
			verificacao = false;
			nome = "Quexin";
			
			Console.WriteLine(numero);
			Console.WriteLine(preco);
			Console.WriteLine(letra);
			Console.WriteLine(verificacao);
			Console.WriteLine(nome);
			
			int meuInt = 15;
			double meuFrac = 7.25;
			bool meuBool = false;
			
			Console.WriteLine(Convert.ToString(meuInt));
			Console.WriteLine(Convert.ToDouble(meuInt));
		    Console.WriteLine(Convert.ToInt32(meuFrac));
		    Console.WriteLine(Convert.ToString(meuBool));
		    
		    Console.WriteLine("Qual seu nome?");
		   
		    string usuario = Console.ReadLine();
		                      
		    Console.WriteLine("Meu nome é" + usuario);
		    
		    Console.WriteLine("Digite um numero inteiro:");
		    int meuNumero = Convert.ToInt32(Console.ReadLine());
		    Console.WriteLine("Seu numero é: " + meuNumero);
		    
		    int meuInt = 15;
			double meuFrac = 7.25;
			bool meuBool = false;
			
			Console.WriteLine(Convert.ToString(meuInt));
			Console.WriteLine(Convert.ToDouble(meuInt));
		    Console.WriteLine(Convert.ToInt32(meuFrac));
		    Console.WriteLine(Convert.ToString(meuBool));
		    
		    Console.WriteLine("Pressione algo para fechar . . . ");
			Console.ReadKey(true);
			
		}
	}
}
