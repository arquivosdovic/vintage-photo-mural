# Mural Revelado

Um editor de mural fotográfico vintage, direto no navegador — sem instalação, sem servidor, sem dependências. Suba fotos, monte um mosaico ou grade, aplique paletas de cor com aparência de filme antigo, destaque fotos como camadas soltas por cima de um fundo desfocado, e baixe o resultado em alta resolução.

🔗 **[Abrir o editor](./mural-vintage.html)** — é um único arquivo HTML, funciona offline.

## Recursos

- **Layouts**: grade regular ou mosaico orgânico (com rotação e orientação automática por foto).
- **Molduras**: nenhuma ou estilo Polaroid, com numeração de quadro e legendas opcionais.
- **Paletas de cor**: Foto original (cor real), Sépia clássico, Frio lavado, Amarelado quente, Retrato desbotado — cada uma editável via sliders de saturação, sépia, desbotado, duotom, equilíbrio de temperatura, grão e vinheta (agora bipolar: clara ↔ escura).
- **Filtro por foto**: cada imagem pode seguir os sliders globais ("Automático"), usar uma paleta fixa, ou receber um resultado aleatório — com indicação visual clara de quais fotos estão ao vivo com os sliders.
- **Randomizador controlável**: escolha quais paletas entram no sorteio e trave fotos individuais para que fiquem de fora.
- **Camadas em destaque**: marque uma ou mais fotos para flutuarem por cima do mural, com controle de tamanho, rotação e posição (arrastando direto no canvas), enquanto o fundo pode ser desfocado para dar profundidade.
- **Cor de fundo**: seletor visual, campo de hexadecimal e atalhos de tons neutros (branco, creme, cinzas, pretos).
- **Proporções e exportação**: proporções predefinidas ou personalizadas, e download em PNG em 1600 / 2400 / 3200px.

## Como usar

1. Baixe `mural-vintage.html` (ou clone o repositório).
2. Abra o arquivo em qualquer navegador moderno.
3. Arraste suas fotos para a área de upload.
4. Ajuste layout, paleta, destaques e cor de fundo na barra lateral.
5. Baixe o mural em `Baixar mural`.

Não há build, backend ou etapa de instalação — é HTML, CSS e JavaScript puros em um arquivo só.

## Stack

- HTML5 Canvas para composição e renderização de imagem
- JavaScript vanilla (sem frameworks)
- Fontes: Fraunces, Special Elite e Work Sans (Google Fonts)

## Licença

Defina a licença que preferir (ex.: MIT) antes de tornar o repositório público.
