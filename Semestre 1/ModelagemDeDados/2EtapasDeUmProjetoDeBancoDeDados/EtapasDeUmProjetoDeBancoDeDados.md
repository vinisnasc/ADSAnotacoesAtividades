# Etapas de um projeto de Banco de dados

## Modelagem de dados

- Identificar os diferentes componentes de dados;  
- Identificar as relações entre os diferentes componentes de dados - associações;  
- Identificar os usos antecipados dos dados;  
- Identificar os pontos fortes e restrições de tecnologias para se usar no projeto;  
- Construir um modelo preliminar das entidades e suas relações, tentando manter o modelo independente de quaisquer usos específicos ou restrições de tecnologias.  

## Levantamento de requisitos

- Quem são os atores(cliente, equipe de desenvolvimento) do processo?  
- O que o analista deve buscar?  
- Como encontramos a informação?  
- A dinamica do levantamento e análise de requisitos.  

## Regras do negócio

- Objetivos que o projeto deve seguir. Exemplos:
- "Todo cliente deve estar cadastrado em nosso sistema";  
- "O CPF e e-mail devem ser campos obrigatórios no cadastro do cliente";  
- "Toda venda deve gerar um cupom fiscal".

## Níveis de modelagem: Tipos de modelos

### Modelo Conceitual
- Entidades importantes e as relações entre elas;  
- Nenhum atributo é especificado;  
- Nenhuma chave primária é especificada.
![ModeloConceitual](https://raw.githubusercontent.com/viniciusnasc/ADSAnotacoesAtividades/master/Semestre%201/ModelagemDeDados/2EtapasDeUmProjetoDeBancoDeDados/imagens/ModeloConceitual.PNG)

### Modelo lógico
-  Todas as entidades e relações entre elas;  
-  Todos os atributos para cada entidade são especificados;  
-  A chave primária para cada entidade é especificada;  
-  Especificadas as chaves estrangeiras;  
-  Normalização ocorre nesse nível. 
-  Etapas: Especificar as chaves primarias -> Encontrar as relações entre as entidades -> Encontrar todos os atributos de cada entidade -> Resolver relacionamentos (n,n) -> Normalização 
![ModeloLogico](https://raw.githubusercontent.com/viniciusnasc/ADSAnotacoesAtividades/master/Semestre%201/ModelagemDeDados/2EtapasDeUmProjetoDeBancoDeDados/imagens/ModeloLogico.PNG)

### Modelo físico
- Especificar todas as tabelas e colunas;  
- Chaves estrangeiras;  
- Considerações físicas podem fazer com que o modelo de dados físico seja bastante diferente do modelo lógico;  
- O modelo físico é diferente para cada SGBD.  
![ModeloFisico](https://raw.githubusercontent.com/viniciusnasc/ADSAnotacoesAtividades/master/Semestre%201/ModelagemDeDados/2EtapasDeUmProjetoDeBancoDeDados/imagens/ModeloFisico.PNG)

### Diferenças entre os modelos
![Comparativo](https://raw.githubusercontent.com/viniciusnasc/ADSAnotacoesAtividades/master/Semestre%201/ModelagemDeDados/2EtapasDeUmProjetoDeBancoDeDados/imagens/QuadroComparativo.png)