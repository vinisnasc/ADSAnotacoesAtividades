# MODELOS ENTIDADE-RELACIONAMENTO

### Elementos do BD-ER
- Entidade: Uma classe de objetos do mundo real com caracteristicas e propriedades comuns sobre as quais desejamos registrar informações;  
- Relacionamento: Associação entre duas ou mais entidades;  
- Atributo: Característica de uma entidade ou relacionamento.  

### Vantagens do modelo ER:
- Simplicidade conceitual;  
- Representação visual;  
- Ferramenta de comunicação eficaz;  
- Integrado com o modelo de bd relacional.  

### Desvantagens:
- Representação limitada de restrições e relacionamentos.  

## Entidade
- Pessoa, lugar, evento, objeto, conceito.  
- Ela se tornará uma tabela no BD.  
- Um objeto é uma instancia de uma entidade.  

### Entidade forte
- Não depende de outra entidade para existir.  
- "Além de independência de existência, normalmente possuem independência de identificação dada por um ou mais atributos próprios" - Barbieri(1994).  

### Entidade fraca
- Precisa de outra entidade para existir.  
- Tem uma chave primaria que é parcial ou totalmente derivada da entidade mãe no relacionamento.  

### Entidade associativa
- Entidade que une duas entidades n para n.  
- Identificada pela concatenação entre as duas chaves primarias das entidades que a representam.  

## Diagrama de ER:
- Entidades representadas por retangulos;  
- Atributos por circulos;  
- Relacionamentos por um losango, entre as linhas que ligam as entidades;  