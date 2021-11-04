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

