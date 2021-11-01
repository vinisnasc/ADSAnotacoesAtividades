# Implementando o modelo relacional

## Normalização  
- Avaliar a estrutura da tabela para minimizar redundancia de dados.  
- Criado após a realização do modelo conceitual DER.  
- Evitam anomalias.  
- Ocorrem através dos estágios das Formas Normais.  

## Anomalias  
### Inserção  
Presença de campos nulos que não deveriam ser nulos.  

### Atualização
Atualização de vários dados quando só se é necessário atualizar um.  

### Exclusão  
Exclusão de um objeto que não deveria ter sido excluido ao excluir um objeto relacionado a ele   

## Formas normais
### 1º Forma normal 1FN
- Não deve existir colunas com dados repetidos ou similares;  
- Não devem existir dados compostos - apenas um valor por coluna;  
- Cada linha deve ser única, possuindo uma chave primária;  
- Cada campo deve ter um nome exclusivo.  

### 2ª Forma normal 2FN
- A tabela já está adequada a 1FN;  
- Todos os atributos não-chave devem depender da chave primária completa, não devem ter dependência parcial.  

### 3ª Forma normal 3FN
- Já deve estar adequada a 1FN;  
- Não existam atributos não-chave que dependam de outros atributos não-chaves