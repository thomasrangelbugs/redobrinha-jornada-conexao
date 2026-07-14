# Redobrinha — A Jornada da Conexão

Jogo de plataforma procedural em HTML5 Canvas.

**Jogar agora:** [https://redobrinha.netlify.app](https://redobrinha.netlify.app)

## Como jogar localmente

```bash
python -m http.server 8080
```

Acesse `http://localhost:8080`.

| Controle | Ação |
|---|---|
| ← → / A D | Andar |
| Shift | Correr |
| Espaço / W / ↑ | Pular |
| M | Mutar áudio |
| F | Tela cheia |
| Esc | Voltar ao menu / sair da tela cheia |
| Celular | Controles nas laterais · inicia em tela cheia |

Sliders no menu ajustam **trilha** e **efeitos** separadamente.

## Deploy

Site online: **https://redobrinha.netlify.app**

No Netlify, publique esta pasta (`redobrinha-game`) ou use o `netlify.toml` da raiz do repositório com `publish = "redobrinha-game"`.

## Sprites (`assets/sprites/`)

| Pasta | Uso no jogo |
|---|---|
| `idle_front` | Animação do menu (piscar) |
| `walk` (8) | Caminhada |
| `run` (8) | Corrida (Shift) |
| `jump` | Pulo / queda / aterrissagem |
| `emotion` | Idle lateral, pensando, dano |
| `wave` | Vitória de fase |
| `magic` | Coleta / power-up |
| `inspect` | Checkpoint |

## Progresso

Salvo em `localStorage` (`redobrinha_save_v2`): fase, vidas, score, checkpoint e recorde.

## Autor

Thomas Rangel Bugs · Redobrai
