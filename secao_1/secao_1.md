# CSS Transitions

`transition` é uma propriedade abreviada que permite definir a transição entre dois estados

Essa propriedade define os valores de `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`

```css
transition: property duration timing-function delay;
```
## Transition-Property

`transition-property` define quais propriedades CSS as transições devem ser aplicadas

No entanto, nem todas as propriedades podem ser afetadas

```css
transition-property: none; /*aplicada a nenhuma propriedade*/
transition-property: CSS property; /*aplicada a uma propriedade específica*/
transition-property: all; /*aplicada a todas as propriedades*/
```

## Transition-Duration

`transition-duration` define a duração em que as transições devem ocorrer

Pode-se definir apenas um valor para todas as propriedades ou valores diferentes para diversas propriedades

```css
transition-duration: 1s; /*mesmo valor*/
transition-duration: 1s, 3s; /*valores diferentes*/
```

## Transition-Timing-Function

`transition-timing-function` define o comportamento de transição de uma propriedade

```css
transition-timing-function: ease; /*valor padrão*/
transition-timing-function: ease-in; /*começa devagar e termina rápido*/
transition-timing-function: ease-out; /*começa rápido e termina devagar*/
transition-timing-function: ease-in-out; /*começa devagar, acelera e termina devagar*/
transition-timing-function: linear; /*mantém o mesmo valor*/
```

## Transition-delay

`transition-delay` define um delay para a transição de uma propriedade

Pode-se definir apenas um valor para todas as propriedades ou valores diferentes para diversas propriedades

```css
transition-delay: 250ms; /*mesmo valor*/
transition-delay: 250ms, 1s; /*valores diferentes*/
```