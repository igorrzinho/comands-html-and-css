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
