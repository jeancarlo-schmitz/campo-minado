<h1 align="center"> 💣 Campo Minado💣  </h1>

<div align="center">
  <a href="https://github.com/jeancarlo-schmitz/campo-minado">
    <img align="center" heigh="180em" src="https://user-images.githubusercontent.com/11407906/184350286-ed6db44c-3ece-42ab-ab17-dfffcdd863b8.jpg"/>
  </a>
</div>

<h1>📑 Descrição do Projeto </h1>
<p>
  Projeto desenvolvido no curso de java. A ideia do projeto é fazer a lógica do jogo campo minado. <br>
  Não tem interface gráfica, as ações do jogo acontecem via console do java. <br>
</p>

<h1>🔨 Funcionalidades do projeto</h1>
<p>
  Inicialmente foi feito o jogo todo pelo console.<br>
  Somente depois que foi feito a parte grafica do jogo. Deixei os 2 modos de jogo ativo.
</p>

<h4>Modo de jogo pelo console.<h4>
<p>
  Primeiro o jogador seleciona as configurações do jogo, podendo escolher a quantidade de linhas, colunas e a quantidade de bombas.<br>
  A condição de vítoria é abrir todos os campos seguros, e marcar todos os campos minados.<br>
  O jogo começa com o jogador podendo escolher a posição que ele deseja abrir do campo minado <br>
  O jogador pode escolher entre 2 opções, 1 - Abrir o campo, ou 2- Marcar o campo <br>
    - Abrir um campo, seria mostrar se ele é um campo seguro, ou se o jogador escolheu um campo minado<br>
    -- Se o campo for seguro, e os campos vizinhos também forem seguros, todos os campos seguros serão abertos.<br>
    --- Caso um campo aberto, tenha algum campo minado ao redor, uma marcação indicando a quantidade de bombas ao redor aparecera<br> 
    -- Se o campo for minado, você perdeu o jogo, e precisa reiniciar.<br> 
    -- Quando o jogador perde o jogo. Todos os campos com minas são revelados<br> 
    - Marcar o campo, significa que ele acredita que esse campo possui uma bomba; <br>
    - Um campo marcado, não pode ser aberto <br>
  O usuário digita no console o campo que deseja abrir/marcar, e a mágica acontece. <br>
</p>

![campo_minado_2](https://user-images.githubusercontent.com/11407906/187006983-fa43a4c4-4066-4a26-b099-129498a8bc79.gif)
![campo_minado](https://user-images.githubusercontent.com/11407906/185352606-f06addba-5561-4a23-a742-e02318ff5b0c.gif)


Indice: 
<ul>
  <li>? -> Campo fechado</li>
  <li>* -> bombas (amarelo)</li>
  <li>X -> campo marcado (vermelho)</li>
  <li>Números -> Indica a quantidade de bombas ao redor do campo (Cores variadas).</li>
</ul>

<h1>⚙ Técnicas e tecnologias utilizadas</h1>
<ul>
  <li>Java 8 +</li>
  <li>Junit 5</li>
  <li>MVC</li>
  <li>STS IDE</li>
</ul>

<h1>📍 Status do Projeto </h1>

<h3 align="center">
✅  Finalizado  ✅
</h3>

<h1>⚡ Como Rodar </h1>
  <h4>Modo Interface Grafica.</h4>
<ul>
  <li>Fazer o clone, ou baixe o projeto para sua maquina</li>
  <li>Abra o projeto na sua IDE de preferencia</li>
  <li>Abre o arquivo em view/TelaPrincipal.java</li>
  <li>Agora é so rodar o projeto.</li>
</ul>
  
<h4>Modo Pelo console</h4>
<ul>
  <li>Fazer o clone, ou baixe o projeto para sua maquina</li>
  <li>Abra o projeto na sua IDE de preferencia</li>
  <li>Abre o arquivo em AplicacaoWithConsole.java</li>
  <li>Agora é so rodar o projeto.</li>
</ul>
