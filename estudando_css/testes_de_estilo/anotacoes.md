# Cores
Usamos CSS para alterar cores do nosso documento

## Tipos

* background-color (para caixas)
* color (para textos)
* border-color (para caixas)
* Outros...

## Valores

Podemos definir valores por

* Palavra-chave (blue, transparent)
* Hexadecimal (#990011)
* Funções (rgb, rgba, hsl, hsla)

```CSS
element{
    /* Keyword values*/
    color: currentcolor;

    /*<named-color> values*/
    color:red;
    color: orange;
    color:tan;
    color:rebeccapurple;

    /* <hex-color> values 0-F*/
    color: #090;
    color: #009900;
    color: #090a;
    color: #009900aa;

    /* <rgb()> values */
    color: hsl(30, 100%, 50%, 0.6); /* Hue - Saturation - Luminance */
    color: hsla(30, 100%, 50%, 0.6);
    color: hsl(30 100% 50% / 0.6);
    color: hsla(30 100% 50% / 0.6);
    color: hls(30.0 100% 50% / 0.6);
    color: hsla(30.2 100% 50% / 0.6);

    /* Global values */
    color: inherit;
    color: initial;
    color: unset;
}
```

## Referencia

http://developer.mozilla.org/en-US/docs/Web/Css/color-value


## Background

- Define um fundo para o nosso elemento
- Sua área de atuação é a caixa toda
- Por padrão é transparente

### Exemplos

- Usar cores sólidas
- Usar imagens
- Controlar
    - a posição das imagens,
    - se elas se repetem ou não
    - o tamanho delas na caixa
- usar cor e imagens juntas
- usar cor gradiente

# Page Layouts

- Tables
- Floats e clear
- Framaworks e Grid Systems
- Grid

## Posicionamentos

controlar onde, na prática o elemnto irá ficar, alterando o fluxo normal dos elementos.

- Name: position
- Value: static | relative | absolute | fixed

## Relative
- Top, right, bottom, left, z-index

## Fixed

## Element Stacking

# Flex Box

* Nos permite posicionar os elementos dentro da caixa.
* Controle emn uma dimenção (horizontal ou vertical)
* Alinhamento, direcionamento, ordenar e tamanho

```CSS
div.parent{
    display: flex;
}
```

## Flex direction

* Qual direção do flex: horizontal ou vertical
* row | column

## Alinhamento

* justify-content
* aligin-items

# Trabalhando com fontes

Tipografia transmite mensagem

    - Negrito
    - Tamanho
    - Estilo

--------------------------------------

## Basic Font Properties

* Font-family
* font-weight
* font-style
* Font-size

--------------------------------------

## Font-family

* Tipo de fonte de um elemento
* Lista de fonte e ordem de prioridade
*Inclui *fallback* font

```CSS
p{
    font-family: "Times New Roman", Times, serif;

}
```








}
