# MODELOS ENTIDADE-RELACIONAMENTO

### Relacionamentos
- Conjunto de associações entre entidades;  

### Relação unária
- Associação entre duas instancias em uma mesma entidade.  
- Exemplo: Objeto Produto se relacionando com objeto herdado dele ProdutoFabricavel.  

### Relação binária
- Relação entre duas entidades  

### Relação ternária
- Relação entre três entidades.  

## Cardinalidade

### Relação um para muitos 1:N
- A relação entre uma instância que se relaciona com várias instâncias.  
- Uma pessoa possui N carros, mas um carro só pode ter uma pessoa.  

### Relação muitos para muitos N:N ou N;M
- Uma instancia do conj A pode ter varias relacoes  com instancias do conj B, sendo que uma do conj B pode ter várias com do conj A.  

### Relação um para um 1:1
- Uma relação de uma instancia do conj A se rela ciona exclusivamente com uma do conj B, e vice-versa.  

## Cardinalidade minima-maxima
- Cliente(1:1) = (1:1) Login => Cliente possui no minimo um login, e no maximo um login, um login possui no minimo um cliente, e no maximo um cliente.  
- Cliente(1:1) = (0,N) Pedido => Cliente possui no minimo nenhum pedido, e no maximo vários, um pedido tem no minimo um cliente, no maximo um cliente.  

## Atributos
- Propriedade ou caracteristica de uma entidade;  

### Descritores
- Descrevem uma caracteristica de uma entidade.  

### Identificador
- Atributo com valor único que identifica sua instancia, Id.  

### Identificadores com chave composta
- Classes fracas precisam do identificador da classe mãe.  

## Graficos
- Entidades = retangulos.  
- Atributos = circulos ou elipses.  
- Atributos identificadores = circulos ou elipses escuros, ou elipse com nome sublinhado.  
- Relação = losangulo.  