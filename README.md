# Redobrinha — A Jornada da Conexão

> Jogo web de plataforma procedural em HTML5 Canvas, criado pela Redobrai.

**Jogar online:** [https://redobrinha.netlify.app](https://redobrinha.netlify.app)

## Sobre o projeto

Redobrinha é um jogo de plataforma side-scrolling no navegador. O jogador controla a mascote da Redobrai, recupera núcleos de conexão, quebra blocos, desvia de inimigos e atravessa a fenda entre fases. As fases são geradas proceduralmente, com clima, estação, trilha sonora, efeitos sonoros e progresso salvo no navegador.

O projeto é 100% estático (HTML, CSS e JavaScript), otimizado para PC e celular, com controles touch nas laterais, tela cheia e suporte a orientação landscape.

## Funcionalidades principais

- Plataforma procedural com fases progressivas
- Sprites animados (idle, walk, run, jump, emotion, wave, magic, inspect)
- Sistema de vidas, score, núcleos e checkpoint
- Clima e estação dinâmicos por fase
- Trilha e efeitos com volumes separados
- Controles teclado (PC) e touch nas faixas laterais (celular)
- Tela cheia no celular ao iniciar e botão/atalho F no PC
- Save local (`localStorage`) com continuar partida
- Layout responsivo e aviso para girar o celular

## Tecnologias utilizadas

- HTML5 Canvas
- CSS3
- JavaScript
- Netlify (deploy estático)

## Jogar online

[https://redobrinha.netlify.app](https://redobrinha.netlify.app)

## Estrutura

```text
redobrinha-jornada-conexao-v1/
├── netlify.toml          ← publish = redobrinha-game
├── README.md
└── redobrinha-game/      ← site publicado
    ├── index.html
    ├── styles.css
    ├── game.js
    ├── netlify.toml
    └── assets/
```

## Como executar localmente

```bash
cd redobrinha-game
python -m http.server 8080
```

Abra `http://localhost:8080`.

## Controles

| PC | Celular |
|---|---|
| ← → / A D andar | ◀ ▶ na faixa esquerda |
| Shift correr | ⚡ na faixa direita |
| Espaço / W / ↑ pular | ▲ na faixa direita |
| M mutar | Botão ♪ |
| F tela cheia | Abre ao iniciar / botão ⛶ |

## Deploy no Netlify

1. Conecte este repositório no Netlify **ou** faça drag-and-drop da pasta `redobrinha-game`.
2. O `netlify.toml` na raiz já define:
   - **Build command:** vazio
   - **Publish directory:** `redobrinha-game`
3. Site publicado em: [https://redobrinha.netlify.app](https://redobrinha.netlify.app)

## Progresso

Salvo em `localStorage` (`redobrinha_save_v2`): fase, vidas, score, checkpoint e recorde.

## Repositório

[github.com/thomasrangelbugs/redobrinha-jornada-conexao](https://github.com/thomasrangelbugs/redobrinha-jornada-conexao)

## Autor

**Thomas Rangel Bugs** · Redobrai
