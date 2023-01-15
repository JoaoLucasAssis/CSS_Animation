# CSS 3D Transforms

Sempre que utilizar animações em 3D, deve-se definir uma perspectiva

Junto da perspectiva, algumas das propriedades, como `translateZ`, `rotateX` e `rotateY`, tem funcionalidades diferentes

## Perspective

`perspective` define a distância entre os olhos e a tela do computador

```css
perspective: 1000px;
```

## Translate

```css
perspective: 1000px; /*distância entra os olhos e a tela*/
transform: translateZ(150px); /*se aproxima da tela em 850px*/
transform: translateZ(-150px); /*se afasta da tela em 1150px*/
```

## Rotate

```css
perspective: 1000px; /*distância entra os olhos e a tela*/
transform: rotateX(60deg); /*rotaciona ao longo do eixo X*/
transform: rotateY(60deg); /*rotaciona ao longo do eixo Y*/
transform: rotateZ(60deg); /*funciona como o rotate 2D*/
```