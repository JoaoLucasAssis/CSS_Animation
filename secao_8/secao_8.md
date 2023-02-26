# CSS Animations

As animações CSS permitem animar transições de uma configuração de estilo CSS para outra

* As animações consistem em dois componentes:

    * um estilo que descreve a animação CSS
    
    * conjunto de quadros-chave que indicam os estados inicial e final do 
    estilo da animação, bem como possíveis pontos intermediários.

`animation` ou suas subpropriedades estilizam o elemento que deseja animar

## Animation Property 

```css
animation: <animation-name> <animation-duration> <animation-timing-function> <animation-delay> <animation-iteration-count> <animation-direction> <animation-fill-mode>;
```

## Animation Name Property

`animation-name` especifica o nome da regra @keyframes que descreve os quadros-chave de uma animação

## Animation Duration Property

`animation-duration` especifica o período de tempo em que uma animação completa um ciclo.

## Animation Timing Function

`animation-timing-function` especifica como uma animação transita pelos quadros-chave estabelecendo curvas de aceleração.

```css
animation-timing-function: ease; /*valor padrão*/
animation-timing-function: ease-in; /*começa devagar e termina rápido*/
animation-timing-function: ease-out; /*começa rápido e termina devagar*/
animation-timing-function: ease-in-out; /*começa devagar, acelera e termina devagar*/
animation-timing-function: linear; /*mantém o mesmo valor*/
```

## Animation Delay

`animation-delay` especifica um delay no início de uma sequência de animação e se a animação deve começar imediatamente desde o início ou no meio da animação

## Animation Iteration Count

`animation-iteration-count` especifica o número de vezes que uma animação deve ser repetida

## Animation direction Property

`animation-direction` define se uma animação deve ser reproduzida para frente, para trás ou alternar entre reproduzir a sequência para frente e para trás

```css
animation-direction: normal; /*início ao final*/
animation-direction: reverse; /*final ao início*/
animation-direction: alternate; /*início ao final em looping*/
animation-direction: alternate-reverse; /*final ao início em looping*/
```

## Animation Fill Mode Property

`animation-fill-mode` define como uma animação CSS aplica estilos ao seu destino antes e depois de sua execução

```css
animation-fill-mode: forwards; /*mantém os valores definidos pelo último keyframe*/
animation-fill-mode: backwards; /*mantém os valores definidos pelo primeiro keyframe*/
animation-fill-mode: both; /*seguirá as regras para ambas forwards e backwards*/
```