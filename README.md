# viagens--landing-page
Landing page simples e moderna sobre vilarejos encantadores, construída para cumprir os requisitos do Projeto de certificação 1 – Agência de Viagem 🎓

## O que contém
- `index.html` — página única com CSS incorporado (estilo inspirado em Flutter: cards, sombras suaves e transições).

🏗️ Estrutura do Projeto

viagens--landing-page/
├── index.html          # Página principal
├── assets/
│   ├── banner-vilarejo.jpg    # Banner
│   ├── hallstatt.jpg          # 10 imagens dos vilarejos
│   ├── bibury.jpg
│   ├── oia.jpg
│   ├── bled.jpg
│   ├── vernazza.jpg
│   ├── folegandros.jpg
│   ├── wengen.jpg
│   ├── albarracin.jpg
│   ├── furnas.jpg
│   └── tobermory.jpg
└── README.md           # Este arquivo

🎨 Paleta de Cores

| Cor        | Hex     | Uso                    |
| ---------- | ------- | ---------------------- |
| Primary    | #6750A4 | Títulos, botões, hover |
| Accent     | #03DAC6 | Destaques, scrollbars  |
| Background | #F6F6FB | Fundo principal        |
| Card       | #FFFFFF | Cards e seções         |
| Muted      | #6B6B7A | Textos secundários     |

📋 Seções Implementadas
Home - Banner atrativo com call-to-action visual

Locais - Galeria horizontal com 10 vilarejos (Hallstatt, Bibury, Oia, Bled, etc.)

TripMe - Pacotes de viagem com features em grid

MeetUs - Equipe com cards personalizados

Advice - Dicas práticas em lista animada

🎨 Customizações
--> Adicionar Novos Vilarejos
Baixe imagem para assets/nome-vilarejo.jpg
Copie um <article class="card"> na seção #locais

--> Atualize src, alt, título e descrição
--primary: #nova-cor;
--accent: #nova-destaque;


## Por que este projeto
Criei uma interface limpa e acessível que destaca 10 vilarejos (Hallstatt, Bibury, Oia, Bled, Vernazza, Folegandros, Wengen, Albarracín, Furnas, Tobermory). A navegação é interna e responsiva, com foco em usabilidade e apresentação visual.

## Como visualizar
1. Clone o repositório:
   `git clone https://github.com/SEU_USUARIO/viagens--landing-page.git`
2. Abra `index.html` no navegador ou use Live Server no VSCode.
3. (Opcional) Coloque imagens em `assets/images/` e atualize os `src` no HTML.
