# Chapa Prisma · links

Página de links da Chapa Prisma: https://chapaprisma.github.io/links/

## Como editar

Tudo fica no começo do `<script>` do `index.html`, no bloco **EDITE AQUI**:

- `AVISO`: uma faixa amarela de texto livre no topo. Vazio = escondida.
- `ELEICAO`: o cartão da eleição, com rótulo, título, nota, `dias` (AAAA-MM-DD), `abre`/`fecha` (horário de Brasília) e `dica`. O dia de hoje fica em laranja, os dias que já passaram ficam apagados e a linha de baixo diz se a votação começa, está aberta ou reabre. O cartão some sozinho depois do horário de fechamento do último dia. `ELEICAO = null` esconde o cartão. No título, o trecho entre `*asteriscos*` fica marcado em laranja.
- `LINKS`: os links principais. Com `url: ""` o link aparece como "em breve". `tag: "novo"` põe um selo laranja ao lado do título.
- Carta-programa: suba o PDF na raiz do repositório com o nome exato `carta-proposta.pdf`. O cartão liga sozinho, sem mexer no código. Se preferir outro endereço, ponha o link em `url` no item `carta`.
- `PROPOSTAS`: o hub de propostas. Basta pôr a imagem na pasta `propostas/` com o nome indicado (`rds`, `tecnologia`, `negocios`, `social`, em `.png`, `.jpg`, `.jpeg` ou `.webp`) e ela aparece sozinha. Veja `propostas/LEIA-ME.md`.

## Recursos

- Feito para celular, na identidade da chapa (DM Sans, Azul Poli, faixa de 4 cores).
- O hub de propostas abre por tema; cada imagem abre num visualizador com setas e deslize, e tem link direto (`#rds`, `#tecnologia`, `#negocios`, `#social`, `#hub`).
- Botão de compartilhar (menu do celular ou cópia do link).
- Prévia para WhatsApp e Instagram (`assets/og.png`).
- Contagem de visitas e cliques no GoatCounter da chapa.

Fonte DM Sans sob licença OFL (`assets/fontes/OFL.txt`).
