# O Que é CSS?

### Introdução ao CSS
- Cascading Style Sheets - Folha de estado;  
- Linguagem de definição de layouts de HTML;  
- Controla fontes, cores , margens, linhas, alturas, larguras, imagens de fundo, posicionamento...  

### Sintaxe CSS
- Seletor: podendo ser um elemento HTML ou um elemento que iremos criar e aplicar ao elemento HTML;  
- Declaração: podendo ser uma ou mais.  
**h1 {color:blue; font-size:12px;}**
h1 = seletor;  
{color:blue; font-size:12px;} = declaração;  
color e font-size = property;  
blue e 12px = value.  

### Onde declarar
- Pode ser declarado no head a partir da tag <style></style>(Estilo interno)  
- Ou de um arquivo externo tipo css que é declarado no head com a tag link(Estilo externo);  
- Direto na tag html pelo comando style(Estilo inline);  

### Id e Classe
- Id é atribuido por um elemento unico no HTML, e no css sera identificado por uma # seguido de seu nome.  
- Classe é atribuido para um conjunto de elementos no HTML, no css é identificado por um . seguido de seu nome.  

## Estilos:
### background
body {background-color:#b0c4de} => muda cor de fundo;  
body {background-image:url('paper.gif');} => coloca uma imagem como fundo;  
background-repeat:repeat-x; => define que a imagem vai se repetir no eixo x;  
background-repeat:no-repeat; => define que nao tera repetição da imagem;  
background-position:right top; => define a posicao da imagem;  

### text
body {color:blue;} => define a cor do texto;  
p.main {text-align:justify;} => texto justificado;  
a{text-decoration:none;}    
h1{text-decoration:overline;}   
h2{text-decoration:line-through;}   
h3{text-decoration:underline;}   
p.uppercase{text-transform:uppercase;}  

### font
p{font-family:"Times New Roman", Times, serif;}  
p.normal{font-style:normal;}  
p.italic{font-style:italic;}  
p.oblique{font-style:oblique;}  
h1{font-size:40px;} ou h1{font-size:50%;}