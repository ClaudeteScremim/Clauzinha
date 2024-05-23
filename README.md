<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus objetivos do ano</title>
</head>
<body>
   
</body>
</html>
<section class="conteudo-principal">
            <h2 class="titulo-principal">Meus Objetivos do ano_</h2>
   <div class="botoes">
            <button class="botao">Cursos na Alura</button>
            <button class="botao">Criar projetos em Javascript</button>
            <button class="botao">Criar um portfolio</button>
            <button class="botao">Atualizar meu currículo</button>
     </div>
 </section>
<link rel="stylesheet" href="style.css">
:root {
    --cor-de-fundo: #1E1E1E;
    --verde: #6FFF57;
    --branco: #FFFFFF;
    --botao-ativo: #3A375E;
    --botao-inativo: rgba(58, 55, 94, 0.5);
    --texto-fundo: rgba(58, 55, 94, 0.3);
}
@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@400;700&display=swap');
body {
    background-color: var(--cor-de-fundo);
    color: var(--branco);
    font-family: 'Chakra Petch', sans-serif;
}:root {
  --cor-base: #ff6347;
}
<body>
    <h2>Olá devs!</h2>
    <div>
        <p>Aula 01</p>
        <a href="#"><p>Slides da Aula</p></a>
    </div>
</body>:root {
    --cor-fundo: #CCCCCC;
}
.conteudo-principal {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    max-width: 1200px;
    width: 100%;
    margin: 0 auto;
}
.titulo-principal {
    text-align: left;
    width: 100%;
    font-size: 32px;
}
 <h2 class="titulo-principal">Meus Objetivos do ano<span>_</span></h2>
.titulo-principal span {
    color: var(--verde);
}
.botao {
    font-family: "Crakra Petch", sans-serif;
    background-color: var(--botao-inativo);
    color: var(--branco);
    display: flex;
    justify-content: center;
    padding: 1em;
    font-size: 18px;
    align-items: center;
    width: 100%;
 border-bottom: 4px solid var(--botao-ativo); 
    border-left: 2px solid var(--botao-ativo); 
    border-right: 2px solid var(--botao-ativo); 
    border-top: none;
.botoes {
    display: block;
}

@media screen and (min-width: 768px) {
    .botoes {
        display: flex;
    }
.botao:first-child {
    border-radius: 40px 40px 0 0;
}

@media screen and (min-width: 768px) {
    .botoes {
        display: flex;
    }

    .botao:first-child {
        border-radius: 40px 0 0 0;
    }

    .botao:last-child {
        border-radius: 0 40px 0 0;
    }
}
        <div class="container">
            <div class="item"></div>
            <div class="item"></div>
            <div class="item"></div>
        </div>
  <h2 class="titulo-principal">Escola de Tecnologia<span>_</span></h2>
        <div class="botoes">
            <button class="botao">Nossos cursos</button>
            <button class="botao">Quem somos?</button>
        </div>
.ativo{
    background-color: var(--botao-ativo);
    border-bottom: 4px solid var(--verde);
}
<button class="botao ativo">Cursos na Alura</button>
<button class="botao">Criar projetos em Javascript</button>
<button class="botao">Criar um portfolio</button>
<button class="botao">Atualizar meu currículo</button>
<script src="main.js"></script>
const botoes = document.querySelectorAll(".botao");
console.log(botoes)
for(let i=0; i <  botoes.length; i++){
    console.log(i);
}
botoes[i].onclick = function(){
    
    botoes[i].classList.add("ativo");
}
for(let j=0;j<botoes.length;j++){
            botoes[j].classList.remove("ativo");
 }
const botoes = document.querySelectorAll(".botao");

for(let i=0;i <botoes.length;i++){
    botoes[i].onclick = function(){

        for(let j=0;j<botoes.length;j++){
            botoes[j].classList.remove("ativo");
        }

        botoes[i].classList.add("ativo");
    }
}<p class="numero impar">1</p>
<p class="numero impar">2</p>
<p class="numero impar">3</p>
<p class="texto">Este é o primeiro parágrafo.</p>
<p class="texto">Este é o segundo parágrafo.</p>
<p class="texto">Este é o terceiro parágrafo.</p>
<p class="numero impar">1</p>
<p class="numero par">2</p>
<p class="numero impar">3</p>
<p class="numero par">4</p>
<p class="numero imfor ([inicialização]; [condição]; [incremento]) {
   declaração
   }
par">5</p>
for (var i = 1; i <= 5; i++) {
  console.log(i);
}
for (var i = 0; i <= 10; i += 2) {
  console.log(i);
}
var frutas = ["Maçã", "Banana", "Laranja", "Pera"];
for (var i = 0; i < frutas.length; i++) {
  console.log(frutas[i]);
}
let contador = 5;
contador += 3;
let contador = 10;
contador -= 4;

var numero = 3;
numero *= 2;
var numero = 10;
numero /= 2; 
<div class="abas-textos">
    
</div>
<div class="abas-textos">
    <div class="aba-conteudo">
           
    </div>
</div>
<div class="abas-textos">
    <div class="aba-conteudo">
        <h3 class="aba-conteudo-titulo-principal">Estudar 4 cursos na Alura</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
    </div>
</div>
<div class="abas-textos">
    <div class="aba-conteudo">
        <h3 class="aba-conteudo-titulo-principal">Estudar 4 cursos na Alura</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
    </div>
    <div class="aba-conteudo">
        <h3 class="aba-conteudo-titulo-principal">Criar 5 projetos em Javascript</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
    </div>
    <div class="aba-conteudo">
        <h3 class="aba-conteudo-titulo-principal">Criar um portfolio com os meus 3 melhores projetos</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
    </div>
    <div class="aba-conteudo">
        <h3 class="aba-conteudo-titulo-principal">Atualizar meu curriculo com os certificados da Alura</h3>
        <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
    </div>
</div>
.abas-textos{
    background-color: var(--texto-fundo);
}
<div class="conteudo">
    <div class="botoes">
        <button class="botao ativo">Cursos na Alura</button>
        <button class="botao">Criar projetos em Javascript</button>
        <button class="botao">Criar um portfolio</button>
        <button class="botao">Atualizar meu currículo</button>
    </div>
    <div class="abas-textos">
        <div class="aba-conteudo">
            <h3 class="aba-conteudo-titulo-principal">Estudar 4 cursos na Alura</h3>
            <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
        </div>
        <div class="aba-conteudo">
            <h3 class="aba-conteudo-titulo-principal">Criar 5 projetos em Javascript</h3>
            <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
        </div>
        <div class="aba-conteudo">
            <h3 class="aba-conteudo-titulo-principal">Criar um portfolio com os meus 3 melhores projetos</h3>
            <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
        </div>
        <div class="aba-conteudo">
            <h3 class="aba-conteudo-titulo-principal">Atualizar meu curriculo com os certificados da Alura</h3>
            <h4 class="aba-conteudo-titulo-secundario">Tempo para completar o objetivo</h4>
        </div>
    </div>
</div>
.abas-textos{
    background-color: var(--texto-fundo);
    padding: 40px;
    border-radius: 0 0 40px 40px;
}
.botao.ativo{
    background-color: var(--botao-ativo);
    border-bottom: 4px solid var(--verde);
}





