# Secret Word

Jogo de palavra secreta desenvolvido em React como projeto prático de um curso de React, para colocar em prática os conceitos aprendidos.

## Funcionalidades

- Palavras separadas por categorias: carro, fruta, corpo, computador, programação e alimento.
- Palavra e categoria escolhidas aleatoriamente a cada rodada.
- Ganhe 100 pontos por palavra acertada.
- São permitidas até 3 tentativas erradas.
- Telas de início, jogo e fim de jogo.

## Tecnologias

- React 19
- Vite
- CSS

## Como executar

```bash
npm install
npm run dev
```

Para gerar a versão de produção:

```bash
npm run build
```

## Estrutura do projeto

```
src/
├── components/
│   ├── Game.jsx
│   ├── GameOver.jsx
│   └── StartScreen.jsx
├── data/
│   └── words.js
├── App.jsx
└── main.jsx
```

---

Este README foi gerados com o auxílio de IA.
