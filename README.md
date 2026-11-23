# Chapa Prisma · links

Página de links da Chapa Prisma: https://chapaprisma.github.io/links/

## Como editar

- **Links:** ficam escritos direto no HTML do `index.html`, dentro de `<a class="destaque">` (o bloco amarelo) e dos dois `<section class="grupo">`. Para trocar um link, mude o `href`; para trocar o texto, mude o `<b>` e o `<span>` da linha.
- **Carta-programa:** hoje é uma linha "em breve" (`<div class="item breve">`). Quando sair, troque o `<div>` por `<a class="item" href="LINK" data-conta="carta">` e apague o `<span class="selo">`.
- **Propostas por tema:** ponha as imagens na pasta `propostas/` (`rds.png`, `tecnologia.png`, `negocios.png`, `social.png`). Quando a primeira existir, a linha aparece sozinha e abre a grade, com visualizador e link direto (`#hub`, `#rds` etc.). A lista fica no bloco **EDITE AQUI** do `<script>`.
- **QR code:** `assets/qr.svg` aponta para esta página. Se o endereço mudar, gere outro.

## Recursos

- Feito para celular, na identidade da chapa: DM Sans, Azul Poli e o prisma com o feixe de quatro cores.
- Abertura animada com GSAP: o feixe sai do prisma e o lema sobe. Quem pede menos movimento no sistema vê a página parada; se o GSAP não carregar, a página aparece normal.
- Os links estão no HTML, então funcionam mesmo sem JavaScript.
- Botões de compartilhar (menu do celular ou cópia do link) e de QR code, para mostrar ao vivo.
- Prévia para WhatsApp e Instagram (`assets/og.png`).
- Contagem de visitas e cliques no GoatCounter da chapa.

Fonte DM Sans sob licença OFL (`assets/fontes/OFL.txt`). GSAP 3.12.5 carregado do cdnjs.
