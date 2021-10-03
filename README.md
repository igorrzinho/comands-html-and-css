# alguns comando de htlm e css para me lembrar depois
## formulario
## no html
 para escrever dentro de um input usamos:  
```` html
<input type="text" placeholder="escreve dentro do input" > 
```` 
 para escrever em um formulario usamos:  
```` html
<label for="o id do input" > 
````
 para desabilitar um input usamos:   
````html
<input disabled="" >
````
___
## no css
 para selecionar os inputs pelo tipo dele no css usamos:   
```` css
input [type="text"] {


}
```` 

 para estilizar essa placeholder use:    
```` css
::-webkit-input-placeholder { 


}
```` 
  para tirar a borda de um input ao clicar nele usamos:   
```` css
input{
outline : none;
}
```` 
___
# html
___
# css
# before e after

  usamos para estilizar antes do elemento:
````css
::before{
  content:"";
}
````
___
  para estilizar depois do elmento:
````css
::after{
  content:"";
}
````
___
___
  para separar os ites de um elemento usamos:   
```` css
justify-content: space-betwen;
```` 
___
  para declarar variaveis no css usamos:    
```` css
:root {
  --nomeDaVariavel: oque ela recebe;
  --azul : blue;
}
```` 
___
 # para usarmos essas variaveis usamos:   
```` css
var(--nomeDaVariavel)
```` 
___
  para rodar algun elemento use:   
```` css
trasition: rotate 180deg;
````
___
  para definir um tempo para essa rotação usamos:   
```` css
transition: 3s;
```` 
___
  para tirar o sublinhado de algum link usamos:   
````css
text-decoration:none;
````
___
  para colocar algun texto em sublinhado pode usar:
````css
text-decoration:underline;
````

  ou 
````css
border-botton:solid red 3px;
````
___
# bordas
  para mudar uma borda usamos :    
```` css
border: 3px solid black;
```` 
___
  para colocar uma borda emcima:
````css
border-top:3px solid red;
````
___
  para colocar uma borda na esquerda:
````css
border-left:3px solid red;
````
___
  para colocar uma borda na direita:
````css
border-rigt:3px solid red;
````
___
  para colocar uma borda embaixo:
````css
border-botton:3px solid red;
````
___
## border radius
  para colocar um elemento com todas as bordas aredondadas use:
````css
border-radius: 15px;
````
___
  para colocar apenas uma borda arredondada use:
````css
 border-radius: 0 0 0 0;
 ````
1. a primeira medida se refere ao canto superior esquerdo 
1. a segunda medida se refere ao canto superior direito
1. a terceira medida se refere ao canto inferior direito
1. a quarta medida se refere ao canto inferior esquerdo
___
# bara de rolagem
  para estilizar toda a barra de rolagem usamos:
````css
::-webkit-scroll-bar-track{


}
````
___
  para estilizar onde o scroll usamos:
````css
::-webkit--scollbar-thumb{


}
````
___
# keyframes
````css
@keyfrmes nomedaanimação{
from{

  }
to{

  }
}
````
## exemplos
````css
p {
  animation-duration: 3s;
  animation-name: slidein;
}

@keyframes slidein {
  from {
    margin-left: 100%;
    width: 300%;
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}

.slidein {
  -moz-animation-duration: 3s;
  -webkit-animation-duration: 3s;
  animation-duration: 3s;
  -moz-animation-name: slidein;
  -webkit-animation-name: slidein;
  animation-name: slidein;
  -moz-animation-iteration-count: 3;
  -webkit-animation-iteration-count: 3;
  animation-iteration-count: 3;
  -moz-animation-direction: alternate;
  -webkit-animation-direction: alternate;
  animation-direction: alternate;
}

@-moz-keyframes slidein {
  from {
    margin-left:100%;
    width:300%;
  }

  to {
    margin-left:0%;
    width:100%;
  }
}

@-webkit-keyframes slidein {
  from {
    margin-left:100%;
    width:300%;
  }
  

  to {
   margin-left:0%;
   width:100%;
 }
}

@keyframes slidein {
  from {
    margin-left:100%;
    width:300%
  }

  to {
   margin-left:0%;
   width:100%;
 }
}
````