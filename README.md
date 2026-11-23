# Chapa Prisma · links

Página de links da Chapa Prisma: https://chapaprisma.github.io/links/

## Como editar

No começo do `<script>` do `index.html`, no bloco **EDITE AQUI**:

- `ELEICAO`: o cartão da eleição, com rótulo, título, nota, `dias` (AAAA-MM-DD), `abre`/`fecha` (horário de Brasília) e `dica`. O dia de hoje fica em laranja, os dias que já passaram ficam apagados e a linha de baixo diz se a votação começa, está aberta ou reabre. O cartão some sozinho depois do horário de fechamento do último dia. `ELEICAO = null` esconde o cartão. No título, o trecho entre `*asteriscos*` fica marcado em laranja.
- `CARTA`: suba o PDF na raiz do repositório com o nome exato `carta-proposta.pdf` e a linha da carta-programa liga sozinha.
- `PROPOSTAS`: o hub de propostas. Ponha a imagem na pasta `propostas/` com o nome indicado (`rds`, `tecnologia`, `negocios`, `social`, em `.png`, `.jpg`, `.jpeg` ou `.webp`). Quando a primeira existir, a linha "Propostas por tema" aparece e abre a grade, com visualizador e link direto (`#hub`, `#rds`, `#tecnologia`, `#negocios`, `#social`). Veja `propostas/LEIA-ME.md`.

Os outros links ficam escritos direto no HTML: o bloco amarelo do Fuja das P3 (`<a class="destaque">`) e os dois `<section class="grupo">`. Para trocar um link, mude o `href`; para trocar o texto, mude o `<b>` e o `<span>` da linha.

`assets/qr.svg` é o QR code desta página. Se o endereço mudar, gere outro.

## Recursos

- Feito para celular, na identidade da chapa: DM Sans, Azul Poli e o prisma com o feixe de quatro cores.
- Abertura animada com GSAP: o feixe sai do prisma e o lema sobe. Quem pede menos movimento no sistema vê a página parada; se o GSAP não carregar, a página aparece normal.
- Os links estão no HTML, então funcionam mesmo sem JavaScript.
- Botões de compartilhar (menu do celular ou cópia do link) e de QR code, para mostrar ao vivo.
- Prévia para WhatsApp e Instagram (`assets/og.png`).
- Contagem de visitas e cliques no GoatCounter da chapa.

Fonte DM Sans sob licença OFL (`assets/fontes/OFL.txt`). GSAP 3.12.5 carregado do cdnjs.
