https://www.youtube.com/watch?v=1EghfNK218U&ab_channel=OnlineTutorials

1. `*`: Isso seletor universal redefine as margens e os preenchimentos padrão para zero, removendo qualquer espaço em branco indesejado ao redor dos elementos.

2. `body`: Define o estilo para o corpo da página.
   - `display: flex`: Permite que os elementos dentro do corpo sejam organizados como um flex container.
   - `justify-content: center`: Centraliza os elementos horizontalmente no corpo.
   - `align-items: center`: Centraliza os elementos verticalmente no corpo.
   - `min-height: 100vh`: Define a altura mínima do corpo como 100% da altura da viewport.
   - `background: #9c27b0`: Define a cor de fundo do corpo como roxo (#9c27b0).

3. `.loader`: Estiliza o contêiner do carregador.
   - `position: relative`: Define a posição do elemento como relativa em relação ao seu contêiner pai.
   - `width: 300px; height: 300px;`: Define a largura e altura do contêiner do carregador como 300px.
   - `transform-style: preserve-3d`: Define que os filhos do contêiner devem manter sua posição 3D.
   - `transform: perspective(500px) rotateX(60deg)`: Aplica uma perspectiva 3D ao contêiner e o gira 60 graus em torno do eixo X.
   - `border: 3px solid red`: Adiciona uma borda vermelha de 3 pixels ao redor do contêiner.

4. `.loader span`: Estiliza os elementos filhos do contêiner do carregador.
   - `position: absolute`: Remove os elementos do fluxo normal do documento e posiciona-os com relação ao seu contêiner pai.
   - `display: block`: Define os elementos como blocos.
   - `border: 5px solid #fff`: Adiciona uma borda branca de 5 pixels aos elementos.
   - `box-shadow`: Adiciona uma sombra aos elementos.
   - `box-sizing: border-box`: Garante que a largura e a altura dos elementos incluam a borda e o preenchimento.
   - `border-radius: 50%`: Arredonda os elementos em forma de círculo.
   - `animation`: Define a animação dos elementos usando a animação chamada `animate`, com duração de 3 segundos, função de temporização ease-in-out e loop infinito.

5. `@keyframes animate`: Define a animação chamada `animate`.
   - `0%, 100%`: Define os estados inicial e final da animação, onde os elementos são movidos para longe do espectador (-100px).
   - `50%`: Define o estado intermediário da animação, onde os elementos são movidos para perto do espectador (100px).

6. `.loader span:nth-child(n)`: Estiliza cada elemento filho do contêiner individualmente, com base em sua ordem de ocorrência.
   - `top`, `left`, `bottom`, `right`: Define a posição de cada elemento em relação ao contêiner pai.
   - `animation-delay`: Define um atraso de animação para cada elemento, de forma que a animação comece com um intervalo de tempo crescente entre cada elemento.

7. `<body>`: Define o conteúdo HTML para a página.
   - `<div class="loader">`: Cria o contêiner do carregador com os elementos filhos `<span>` que serão animados.
