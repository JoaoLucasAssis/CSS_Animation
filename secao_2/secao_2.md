# CSS 2D Transforms

`transform` é uma propriedade que permite girar, dimensionar, inclinar ou movimentar um elemento

## Transform-origin

`transform-origin` define o ponto em torno do qual uma transformação é aplicada

```css
transform-origin: top left right bottom; /*posições*/
transform-origin: 150px 70px; /*pixels*/
transform-origin: 50% 50%; /*porcentagem*/
```

## Translate

`translate` reposiciona um elemento nas direções do seu eixo

Suas coordenadas definem o quanto o elemento se move em cada direção

```css
transform: translate(50px 50%); /*movimenta 50px no eixo X e 50% no eixo Y*/
transform: translateX(50px); /*movimenta 50px no eixo X*/
transform: translateY(50%); /*movimenta 50% no eixo Y*/
transform: translateZ(12px); /*movimenta 12px no eixo Z*/
```

## Scale

`scale` redimensiona o tamanho do elemento nas direções do seu eixo

```css
transform: scale(2); /*dobra ambos os lados*/
transform: scaleX(2);
transform: scaleY(2);
transform: scaleZ(2);
```

## Rotate 

`rotate` rotaciona um elemento das direções do seu eixo