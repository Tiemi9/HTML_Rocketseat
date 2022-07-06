# page layouts

    - tables
    - floats and clear
    - frameworks and grid Systems
    - flexbox
    - grid

## posicionamento

Controlar onde na página o elemento irá ficar, alterando o fluxo normal dos elementos

- name: position
- value: static/absolute/elative/fixed

### static
padrão, um abaixo do outro em vertical

### relative
Relativo á página e não interfere nos demais elemtnos
- top, reigth, bottom, left, z-index

### absolute
Absoluto a página e demais elementos se movem como se houvessem duas camadas.
- top, reigth, bottom, left, z-index
/usar main para mover tudo junto/

### fixed
Irá fixar o elemento página, demais elementos ficaram por baixo ou por cima de acordo com a hieraquia do código.

### element stacking
- Stackin significa empilhar
- lembrabndo que x é horizontasl e y vertical então z será "diagonal" (empilhamento em diagonal)
- consideram mais forte o ultimo elemento do codigo, por isso esse ficara por cima de todos.

### flex
- Nos permite posicionar os elementos dentro da caixa
- Controle em uma dimensão (horizontal ou vertical)
- Alinhamento, direcionamento, ordenar e tamanhos
div.parent {
	display: flex;
}
#### Flex-direction
- Qual a direção do flex: horizontal ou vertical
- row | column
#### Alinhamento
- justify-content
- align-items

### grid
- posicionamento dentro de uma caixa
- horizontal e vertical simultaneamente
- pode ser fexivel ou fixo
- cria espaços nos elementos para os filhos





