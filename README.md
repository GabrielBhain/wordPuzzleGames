# Animal Learning Game 🐾🎮

Repositório desenvolvido em dupla para um projeto de estágio sendo um jogo educativo interativo em JavaScript, jQuery, HTML e CSS.

## Objetivo 🎯
O objetivo deste projeto é criar uma experiência divertida e educativa para aprender sobre diferentes animais. Os jogadores podem interagir com imagens de animais, ouvir seus sons e formar os nomes corretos por meio de correspondência de letras.

## Funcionalidades ✨
- Exibição de imagens de animais com seus respectivos nomes.
- Reprodução de sons das letras e barulhos característicos dos animais.
- Desafio de correspondência de letras para formar o nome do animal.

## Ferramentas Utilizadas 🛠️
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [jQuery](https://jquery.com/)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

## Descrição
Este é um jogo educativo desenvolvido em JavaScript, jQuery, HTML e CSS que permite aos jogadores aprenderem sobre diferentes animais de forma interativa. Ao explorar o jogo, os usuários podem clicar nas imagens dos animais para ouvir seus sons correspondentes e participar de um desafio de correspondência de letras para formar o nome correto do animal.

## Como Jogar 🎮
1. Abra o arquivo `index.html` em seu navegador. (Preferencialmente com Live Server)
2. Arraste as letras da parte inferior da tela para formar o nome correto do animal.
3. Continue jogando para aprender sobre diferentes animais!

Divirta-se aprendendo sobre a vida selvagem com este jogo educativo interativo!

## Arquivos e Estrutura do Projeto 📁
- **`index.html`:** Página inicial contendo introdução ao jogo.
- **`game.html`:** Estrutura básica do jogo, contendo as imagens, elementos interativos e referências aos scripts necessários.
- **`demo.js`:** Script JavaScript responsável pela lógica do jogo.
- **`styles.css`:** Arquivo CSS que define o estilo e o layout do jogo.
- **`buzz.js`:** Biblioteca para reprodução de áudio.
- **`jquery.js`:** Biblioteca jQuery para interatividade e manipulação do DOM.
- **`ui.jquery.js`:** Biblioteca jQuery UI para recursos adicionais de interface.
- **`img/`:** Pasta contendo imagens dos animais utilizadas no jogo.
- **`sounds/`:** Pasta contendo arquivos de som associados aos animais.

## Funcionamento do Jogo 🕹
### Carregamento de Dados:
No arquivo JavaScript (demo.js), há um array de objetos chamado games que contém informações sobre cada animal no jogo, incluindo imagem, palavra associada, cor e som correspondente.
Os dados são carregados ao iniciar o jogo, permitindo a exibição dinâmica de imagens, palavras e sons.
 
### Interatividade do Usuário:
Os jogadores interagem com o jogo ao arrastar letras embaralhadas (#letters) e soltá-las sobre os espaços correspondentes (#models) para completar a palavra.
A biblioteca jQuery UI é utilizada para tornar os elementos li draggable (arrastáveis) e droppable (soltáveis) em áreas específicas.
 
### Verificação de Respostas:
Ao soltar uma letra sobre um espaço de modelo (#models), o código verifica se a letra corresponde à posição correta na palavra associada ao animal.
Se a letra estiver correta, ela é animada para o local correto. Se estiver errada, ela retorna à posição inicial com um efeito de erro.
 
### Feedback Visual e Sonoro:
Feedbacks visuais incluem animações de sucesso (letras se movendo para a posição correta) e animações de erro (letras retornando à posição inicial).
Efeitos sonoros são reproduzidos conforme o jogador interage com o jogo, adicionando elementos auditivos à experiência.
 
### Pontuação e Progresso:
A pontuação do jogador é atualizada dinamicamente com base no desempenho ao completar palavras.
O jogo avança para o próximo animal após cada acerto, oferecendo uma progressão contínua e desafiadora.
 
### Personalização e Expansão Futura 🚀
Adicionar Novos Animais:
Para personalizar o jogo, novos animais podem ser adicionados ao array games com imagens, palavras e sons correspondentes.
Basta incluir um novo objeto com os dados necessários para que o jogo reconheça e integre o novo animal.
 
### Implementar Recursos Adicionais:
Recursos extras como níveis de dificuldade (médio), tempo limite, dicas visuais ou sonoras podem ser incorporados para aumentar a complexidade e a diversão.
 
Isso pode exigir ajustes nas funções existentes ou a criação de novas funções para lidar com novos recursos.
 
### Estilização e Animações Personalizadas:
A estilização visual do jogo pode ser personalizada editando o arquivo CSS (styles.css), permitindo alterações de cores, fontes e layouts.
 
Animações adicionais podem ser implementadas usando recursos avançados do jQuery UI para adicionar elementos visuais mais dinâmicos.
 
### Otimização e Melhorias de Desempenho:
Para expandir o projeto, é importante se atentar a otimizações, como carregamento assíncrono de recursos, para melhorar o desempenho e a experiência do usuário.


## Autores 🟠🚀
Desenvolvido por [Gabriel Ferreira](https://github.com/GabrielBhain) e [Adriany Corrêa](https://github.com/adrianycmc).

---
