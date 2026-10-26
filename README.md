# Caminhos Mágicos — Aventura das Formas
WM Jogos Educativos

Jogo com 10 fases: tracejados, círculo, quadrado, triângulo, retângulo, encaixes, casinha e movimentos corporais acompanhados por um adulto. Sem cronômetro. Compatível com mouse e toque.

## Publicar no GitHub Pages
1. Descompacte o ZIP no computador.
2. Envie o conteúdo para o repositório: index.html deve ficar na raiz, junto da pasta assets, sem outra pasta por cima.
3. Nas configurações do repositório, abra Pages e selecione a publicação pela branch principal e pasta raiz.
4. Aguarde o GitHub fornecer o endereço do jogo.

## Publicar no Netlify
Envie a pasta descompactada com index.html e assets para uma implantação manual. Não é necessário compilar. O arquivo netlify.toml já indica a pasta raiz.

## Música e voz
A música começa depois do botão Vamos brincar e tem controle de volume. A narração é em português, com velocidade inicial suave de 0,85 e preferência por vozes femininas conhecidas. O navegador não informa gênero de forma padronizada: a seleção automática é uma preferência, não uma garantia. Em Ajustes, escolha e experimente uma voz em português instalada no dispositivo. Algumas vozes precisam de internet. Quando não há síntese de voz disponível, as pistas visuais permanecem. A música fica mais baixa durante a fala. O botão Ouvir repete a instrução.

## Interação e acessibilidade
Arraste ou toque na peça e no contorno. Para traçar há modo de arrastar ou tocar nos pontos. Há redução de movimentos. As atividades corporais exigem acompanhamento e confirmação de um adulto; não usam câmera. No celular, a posição horizontal oferece área de jogo maior. As fases podem ser repetidas livremente.

## Progresso
O nome opcional e o progresso são guardados apenas no navegador, usando armazenamento local quando disponível. Este pacote não inclui cadastro, bloqueio de acesso ou sincronização entre aparelhos.

## Validação desta versão
Lógica das dez fases, seis tracejados, modo por pontos, encaixes, 24 ordens possíveis na casinha, sete movimentos corporais, botões, retomada e música verificados por testes automatizados. Abertura, mapa, ajustes e encaixes de círculo e retângulo conferidos no navegador de computador. O navegador de teste não tinha vozes em português; timbre e áudio falado precisam ser conferidos no aparelho de destino. Layout móvel ajustado, ainda sem teste em aparelho físico.

## Arquivos
index.html: entrada; assets/game.js: lógica e narração; assets/style.css: visual; assets/jardim-*.png: imagens. Não há bibliotecas externas nem etapa de instalação.
