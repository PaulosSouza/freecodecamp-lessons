
## Anotações do FreeCodeCamp

# Propriedade box-shadow
-  offset-x sombra na horizontal
-  offset-y sombra na vertical	
-  blur-radius radio de desfoque
-  spread-radius radio de propagação
-  color cor

# Propriedade relative
-  Permaneçe no fluxo normal do elemento.

# Propriedade absolute
-  Remove do fluxo normal
-  É bloqueado pelo pai.
-  Pode ser contida usando no pai a position relative

# Propriedad float
-  Move para a direita ou esquerda sobre seu pai.

# Propriedade z-index
-  A propriedade z-index pode especificar a ordem de como os elementos são empilhados uns sobre os outros

# Propriedade scale
-  Aumenta o tamanho original do elemento

# Pseudoelemento ::before
-  Adicionar algo antes do elemento
-  Precisa da propriedade conteudo definida.

# Pseudoelemento ::after
-  Adicionar algo depois do elemento
-  Precisa de uma propriedade conteudo definida.

## Flexbox

# flex-direction row
- Main-axis é horizontal
- cross-axis vertical

# flex-direction column
Main-axis é vertical
cross-axis horizontal

# justify-content 
modifica o main axis

# align-items 
modifica o cross-axis

# flex-wrap 
para quebra quanto para coluna tanto para linha.

# flex-shrink 
pode encolher se o item for muito pequeno. Quanto maior for o valor, maior será diminuido o item. Pode encolher se container for muito pequeno.

# flex-grow 
faz o oposto de flex-shrink.Controla o tamanho dos itens quando o container se expande.

# flex-basis 
define tamanho inicial do item antes que o CSS faça ajuste com flex-grow e flex-shrink. Dimensiona com px, %, em etc.

# flex 
é um short hand de flex-grow, flex-shrink e flex-basis

# order 
ordena os items na tela.

# self-align 
permite alinha o item auto se alinhar. Aceita os mesmos valores que align-items e substituira qualquer valor de align-items

##  Grid

# grid-template-colums 
indica a quantidade de cada coluna na página com seus valores.

# grid-template-rows 
a mesma coisa de grid-template-colums só que define as linhas.]

# grid-column-gap 
espaço entre colunas

# grid-column-row 
espaço entre linhas

# grid-gap 
Se houver dois valores, terá espaços tanto na linha quanto na coluna, mas se apenas um, este valor será para linha e coluna.

#  justify-self
Alinha o item horizontal

# align-self
Alinha o item da grid verticalmente.

# justify-items
Alinha todos os itens, colocado onde está o grid, de forma horizontal

#  align-items
Da mesma forma que justify-itens só que verticalmente

### Observações

# hack para deixar imagem responsiva
- img {
  max-width: 100%;
  display: block;
  height: auto;
}

# imagens
- Usar figure e figcaption para imagem e descrição de imagem.

**Definir como  block facilita bastante às vezes.**

**Para usar o margin 0 auto, deve-se definir uma largura.**

**O uso do before e after é antes de forma a tag e depois que forma a tag.**

**min, valor maior ou igual**

**max, maior menor ou igual**

**por padrão input, select, textarea não herdam tamanho de fonte, familia da  fonte e altura da linha.**

**remover outline e colocar  borda é uma boa alternativa.**

**alterar o checkbox display block ou inline  block, alterar altura e largura.**

**colocar o html e o body com altura e largura 100%**

# RESET CSS
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body,
html {
    width: 100%
    height: 100%;
}