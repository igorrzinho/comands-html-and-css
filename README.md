# alguns comando de htlm e css para me lembrar depois
## formulario
### html
#### para escrever dentro de um input usamos:<br>
* < input type="text" placeholder="escreve dentro do input" > 
#### para escrever em um formulario usamos:<br>
* < label for="o id do input"> 
#### para desabilitar um input usamos: <br> 
*  < input disabled="" >





### css
#### para selecionar os inputs pelo tipo dele no css usamos:<br>
* input [type="text"] {<br><br> } 

#### para estilizar essa placeholder use: <br>
* ::-webkit-input-placeholder {<br><br> }
#### para tirar a borda de um input ao clicar nele usamos:<br>
* outline : none;


## html
## css
#### para separar os ites de um elemento usamos:<br>
* justify-content: space-betwen;

#### para mudar uma borda usamos :<br> 
* border: 3px solid black;
#### para declarar variaveis no css usamos: <br>
* :root {<br>
  --nomeDaVariavel: oque ela recebe;<br>
  /* por exemplo*/<br>
  --azul : blue;<br>
}
#### para usarmos essas variaveis usamos:<br>
* var(--nomeDaVariavel)
#### para rodar algun elemento use:<br>
* trasition: rotate 180deg;<br>
#### para definir um tempo para essa rotação usamos:<br>
* transition: 3s;
#### para tirar o sublinhado de algum link usamos:<br>
* text-decoration:none;
#### para colocar algun texto em sublinhado pode usar:<br>
* text-decoration:underline;
#### ou 
* border-botton:solid red 3px;
#### para colocar um elemento com todas as bordas aredondadas use:<br>
* border-radius: 15px:
#### para colocar apenas uma borda arredondada use:<br>
* border-radius: 0 0 0 0;
* * a primeira medida se refere ao canto superior esquerdo 
* * a segunda medida se refere ao canto superior direito
* * a terceira medida se refere ao canto inferior direito
* * a quarta medida se refere ao canto inferior esquerdo
# keyframes
@keyfrmes nomedaanimação{<br>
from{<br>
  }<br>
to{<br>
  }<br>
}
## exemplos

p {<br>
  animation-duration: 3s;<br>
  animation-name: slidein;<br>
}<br>

@keyframes slidein {<br>
  from {<br>
    margin-left: 100%;<br>
    width: 300%;<br>
  }<br>

  to {<br>
    margin-left: 0%;<br>
    width: 100%;<br>
  }<br>
}
<br>
.slidein {<br>
  -moz-animation-duration: 3s;<br>
  -webkit-animation-duration: 3s;<br>
  animation-duration: 3s;<br>
  -moz-animation-name: slidein;<br>
  -webkit-animation-name: slidein;<br>
  animation-name: slidein;<br>
  -moz-animation-iteration-count: 3;<br>
  -webkit-animation-iteration-count: 3;<br>
  animation-iteration-count: 3;<br>
  -moz-animation-direction: alternate;<br>
  -webkit-animation-direction: alternate;<br>
  animation-direction: alternate;<br>
}<br>

@-moz-keyframes slidein {<br>
  from {<br>
    margin-left:100%;<br>
    width:300%;<br>
  }<br>

  to {<br>
    margin-left:0%;<br>
    width:100%;<br>
  }<br>
}<br>

@-webkit-keyframes slidein {<br>
  from {<br>
    margin-left:100%;<br>
    width:300%;<br>
  }<br>
  <br>

  to {<br>
   margin-left:0%;<br>
   width:100%;<br>
 }<br>
}<br>

@keyframes slidein {<br>
  from {<br>
    margin-left:100%;<br>
    width:300%<br>
  }<br>

  to {<br>
   margin-left:0%;<br>
   width:100%;<br>
 }<br>
}
