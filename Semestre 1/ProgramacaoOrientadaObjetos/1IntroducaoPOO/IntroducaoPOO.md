# Introdução a POO

## Programação estrutural x Programação orientada a objetos  

### Programação estrutural:
- Dados;  
- Funcoes;  
- Enfase nos procedimentos;  
- Implementação em blocos estruturados;  
- Comunicação entre procedimentos implementados em blocos estruturados.  

### POO:
- Objetos;  
 	- Atributos(dados)  
 	- Métodos(funções/procedimentos)  
- Informação encapsulada;  
- Reduz tempo para adaptar um sistema existente;  
- Reduz esforço, complexidade e custos das mudanças;  

- POO = necessário verificar somente o objeto em caso de alteração do sistema;  
- Estrutural = necessário verificar todo o código se houve alguma alteração.  

## Partes de um projeto:

### Análise:
- Define "o que";  
- Entender o domínio do problema;  
- Definir a estrutura estática da aplicação;  
- Criar vocabulário comum de conceitos.  

### Projeto:
- Define "o como";  
- Apresentar a melhor solução para o problema;  
- Definir a estrutura dinamica da aplicação;  
- Fazer especificação.  

### Implementação:
- Construção do software;
- Construir a aplicação em conformidade com as especificações;  
- Fazer testes e validações;  
- Fazer sua implementação.  

## Analise e Projeto Orientado a Objeto (APOO / OOA&D)
- Definição visual comum que permite as pessoas compartilharem conhecimento sobre sistema;  
- Processo;  
- Notação;  
- Regras.  

## Principais conceitos:

### Classe:
- "Grupo ou divisão de objetos que apresenta caracteristicas semelhantes"
- Nome;  
- Atributos;  
- Metodos;

### Objeto:
- Os dados que provem da classe;  

## Notação UML

### Notação das classes:
**Nome da classe**
- Primeira letra sempre em maiúsculo

### Notação dos atributos:
- Atributo: int  
(+) => Acesso público  
(-) => Acesso privado - somente funções da classe tem acesso  
(#) => Acesso protegido - atributo privado porem classes derivadas tem acesso

### Notação dos metodos:
+ Metodo(): void  
(+ - #) => mesmo que os atributos

**OBS.: NEM TODA CLASSE È INSTANCIA DE UM OBJETO**