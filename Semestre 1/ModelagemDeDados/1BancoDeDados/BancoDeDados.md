# Banco de dados

## Evolução historica

### 1960:
Surgimento dos primeiros bancos de dados eletronicos.  
IMS(BD hierarquico) da IBM foi um dos mais relevantes.   
Também nessa década apareceu os primeiros sistemas de banco de dados de redes.  

### 1970:
Surgimento do modelo de BD relacional - modelo mais comum e utilizado no mercado hoje em dia.

### 1980:
Criação do SQL (Strutured Query Language) - linguagem de comunicação de dados que se tornou padrão para BD relacionais.   
Surgimento de BD orientado a aplicações.

### 1990:
Data Mining  
Data Warehousing  
BD multimidia  
BD para web  
Primeiros prototipos de BD Orientados a Objetos.

### 2000:
Gerenciamento de dados de fluxo e mineracao  
Tecnologia web:  
- XML;  
- Integração de dados;  
- Redes sociais;  
- Computação em nuvem;  
- SIG.  

## Conceito de BD
- Um BD é uma sequencia de planilhas fisicas, um fichario, uma lista de telefone, mas no conceito da disciplina, seriam os eletronicos.  
- Vantagem: resgate e manipulação de dados rápido e intuitivo.

### SGBD/CGBD: 
- Sistema que o analista irá manipular o BD.

## Tipos de BD
### modelo hierarquico
- Estrutura logica representada por uma árvore de cabeça pra baixo;  
- Contem níveis ou segmentos;  
- Segmento = Tipo de registro de um sistema de arquivos;  
- Conjunto de relações 1 para muitos, sendo 1 o "pai" e muitos os "filhos";  
- Exemplos: IMS e System 2000;   
+ Simplicidade conceitual;  
+ Segurança e integridade dos dados;  
+ Independencia dos dados  
+ Eficiencia em lidar com uma grande base de dados
- Implementação complexa;  
- Dificil gerenciamento - Necessário conhecer todos os "pais";  
- Falta de independencia estrutural;  
- Limitações de implementação;  
- Falta de normas e padrões bem definidos.

### modelo de rede
- Não é muito usual;  
- Conjunto de relções n para n;  
- Dificil gerenciamento - Necessário conhecer todos os nós;  
- Nascimento do conceito de linguagem de manipulação de esquema do BD (select, inserir, tabelas, etc);  
- Subesquema;  
- Data Manipulation Language(DML) e Data Definition Language(DDL);  
+ Simplicidade conceitual;  
+ Gerenciamento em grande escala;  
+ Flexibilidade de acesso a dados
- Falta de independencia entre as entidades.  

### modelo relacional
- modelo mais utilizado no mercado;  
- SQL Server, Oracle, MySql;  
- Independencia Estrutural;  
- Simplicidade em modelar o BD;  
- Facil de ser implementado;  
- Desvantagem: Necessário ter um bom servidor para rodar bem;  

### modelo Orientado a objeto
- Trabalha com classes;  
- Apresentação visual bem significativa;  
- Independencia estrutural;  
- Desvantagem: Normas e padroes tem diferentes normas.  

## Importancia do BD
- 70% de uma empresa são seus dados;  
- Colabora na tomada de decisão dos empreendedores.