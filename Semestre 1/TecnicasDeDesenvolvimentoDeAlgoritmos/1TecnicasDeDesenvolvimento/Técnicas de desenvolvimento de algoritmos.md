# Técnicas de desenvolvimento de algoritmos

### Processamento de dados: 
"Receber dados por um dispositivo de entrada, realizar operações com esses dados e gerar uma resposta que será exibida em um dispositivo de saída." - ASCENIO.	

## Etapas de desenvolvimento de software:
- Análise - Estudo de projeto com o stackholder, definindo o processamento de dados;  
- Algoritmo - descrição do problema de forma narrativa da logica do sistema, fluxogramas ou português estruturado;  
- Codificação - Transformar a logica em linguagem de programação.  

### definições de algoritmo
- "Sequencia de passos que visa atingir um objetivo bem definido" - FORBELLONE;  
- "Descrição de uma sequencia de passos que deve ser seguida para a realização de uma tarefa." - ASCENIO;  
- "Conjunto de regras para a solução de um problema" - FURLAN DE SOUZA;  
- "Processo de calculo matematico ou de resolução de um grupo de problemas semelhantes" - MANZANO;  
- "Descrição de um conjunto de comandos que, obedecidos, resultam numa sucessão finita de ações" - FARRER.

### Etapas da construção de um algoritmo
- Compreender o problema a ser resolvido;  
- Definir dados de entrada;  
- Definir o processamento dos dados;  
- Definir os dados de saída;  
- Construir o algoritmo;  
- Testar o algoritmo.

### Tecnicas de desenvolvimento de algoritmos
- Descrição narrativa - descrição com uma linguagem natural;  
- Fluxograma - analisar o problema utilizando simbolos pre definidos;  
- Pseudocódigo - comandos parecidos com uma linguagem de programação.

## EXERCÍCIO: 
### tente fazer um algoritmo para calcular a diferença entre dois números e mostrar a mensagem de resultado POSITIVO, NEGATIVO ou ZERO.

### Descrição narrativa:
Passo 1 - Receber dois números quaisquer;  
Passo 2 - Realizar a subtração desses dois números;
Passo 3 - Caso o resultado seja 0, escrever "ZERO", caso seja maior que zero, escrever "POSITIVO", se não, escrever "NEGATIVO".

### Algoritmo em fluxograma:

### Pseudocódigo utilizando Portugol:

	programa
	{
	funcao inicio()
	{
	    real a, b
	
		escreva ("Digite o primeiro número: ")
		leia(a)
	
		escreva ("Digite o segundo número: ")
		leia(b)
	
		real c = a - b
	
		se (c > 0) 
		escreva ("POSITIVO")
	
	    senao se (c == 0)
	    escreva ("ZERO")
	
		senao
		escreva ("NEGATIVO")
	}
	}

### Bonus: C#

    using System;
    
    namespace desafios
    {
        class Program
        {
            static void Main(string[] args)
            {
            Console.WriteLine("Digite o primeiro número: ");
            double a = double.Parse(Console.ReadLine());
            Console.WriteLine("Digite o segundo número: ");
            double b = double.Parse(Console.ReadLine());
    
            double c = a - b;
    
            if(c == 0)
                Console.WriteLine("ZERO");
    
            else if (c > 0)
                Console.WriteLine("POSITIVO");
    
            else
                Console.WriteLine("NEGATIVO");
            }
        }
    }
