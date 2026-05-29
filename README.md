# Princess Motel — Site

Site institucional do **Princess Motel** (BR-491 km 9 · São Sebastião do Paraíso, MG).
HTML/CSS/JS puro — **sem build, sem instalação**. É só abrir os arquivos `.html` no navegador.

## Estrutura

| Arquivo | O que é |
|---|---|
| `index.html` | Página principal (hero com vídeo, suítes, preços, promoções, tour, localização, reserva via WhatsApp) |
| `suite-master14.html` | Suíte Master 14 — cama redonda, hidro dupla, neon RGB |
| `suite-barbie.html` | Suíte Master Barbie 03 — rosa, espelho de teto |
| `suite-japonesa.html` | Suíte Japonesa — ofurô, tatame, lanternas |
| `suite-simples.html` | Suíte Simples + Toscana — foco em pernoite viajante |
| `brand-spec.md` | Sistema visual (cores, tipografia) usado no site |
| `mpq*.jpeg` / `*.png` | Fotos das suítes |
| `mpq59uyk-*.mp4` | Vídeo de fundo do hero |

## Como editar

- **Texto e preços:** abra o `.html` num editor (VS Code, Notepad++) e altere direto. Os preços ficam em tabelas e cards bem identificados.
- **Cores e fontes:** ficam no bloco `:root { ... }` no topo de cada arquivo (variáveis `--bg`, `--accent`, etc.).
- **Trocar fotos:** substitua o arquivo de imagem mantendo o mesmo nome, ou troque o `src="..."` no HTML.
- **WhatsApp:** os botões usam `wa.me/5535992585223` — troque o número se mudar.

## Publicar grátis (GitHub Pages)

`Settings` → `Pages` → Source: `main` / `/ (root)` → `Save`.
Em ~1 min o site fica no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO`.

## Contato do motel

- WhatsApp: (35) 99258-5223
- Endereço: Rod. BR-491 km 9, Zona Rural — ao lado do condomínio Campo Alegre — São Sebastião do Paraíso/MG
- Aberto 24h
