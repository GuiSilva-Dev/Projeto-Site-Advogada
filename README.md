# Portfólio / Landing Page

Este projeto é uma Landing Page responsiva e interativa, desenvolvida para apresentar portfólio, serviços e facilitar o contato com clientes. O site utiliza JavaScript puro (Vanilla JS) para criar experiências de navegação fluidas e animações dinâmicas.

## 🚀 Funcionalidades

O projeto conta com diversas interatividades implementadas via JavaScript e CSS:

- **Menu Responsivo**: Sistema de menu "hambúrguer" que controla a navegação em dispositivos móveis, bloqueando o scroll da página quando aberto (`header.js`).
- **Galeria de Portfólio**: Carrossel de imagens (Slider) com navegação manual (botões anterior/próximo) e transição automática a cada 3 segundos (`slidePortfolio.js`).
- **Headline Animado**: Efeito de letreiro infinito (scroll contínuo) na seção "Sobre", clonando elementos dinamicamente para um loop perfeito (`slideSobre.js`).
- **Botões de Ação Flutuantes**:
  - Botão "Voltar ao Topo" que aparece suavemente após o scroll.
  - Botão de WhatsApp fixo para contato rápido.
  - Ambos possuem lógica de exibição baseada na posição da rolagem (`actionButton.js`).
- **Design Responsivo**: Ajustes dedicados para tablets e dispositivos móveis, garantindo legibilidade e usabilidade em diferentes resoluções (`responsividade.css`).

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica.
- **CSS3**: Estilização, Flexbox e Media Queries.
- **JavaScript (ES6+)**: Lógica de interação e manipulação do DOM.

## 📂 Estrutura de Arquivos Relevante

```text
/assets
  ├── /css
  │    └── responsividade.css  # Ajustes de layout para mobile/tablet
  └── /js
       ├── actionButton.js     # Botões flutuantes (Top/Zap)
       ├── header.js           # Lógica do Menu Mobile
       ├── slidePortfolio.js   # Slider de imagens
       └── slideSobre.js       # Animação de texto infinito
```

## 📦 Como executar

1. Clone este repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
