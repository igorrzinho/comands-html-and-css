# alguns comando de htlm e css para me lembrar depois
## FORMULARIO [clique aqui](https://github.com/igorrzinho/comands-html-and-css/blob/main/form.md)
## BORDAS [clique aqui](https://github.com/igorrzinho/comands-html-and-css/blob/main/border.md)
## KEY FRAMES[clique aqui](https://github.com/igorrzinho/comands-html-and-css/blob/main/keyframes.md)
## ALINHAMENTO [clique aqui](https://github.com/igorrzinho/comands-html-and-css/blob/main/align.md)
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
# alinhamento
 para alinhas uma imagem no centro de uma div usamos:
 ```` css
 .img {
  margin: auto 50%;
  transform: translateX(-50%);
}
 ````
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
````
