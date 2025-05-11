# Huddle Landing Page

![Huddle Landing Page](./src/images/illustration-mockups.svg)

## Visão Geral

Este projeto é uma landing page responsiva para o Huddle, uma plataforma que facilita a construção de comunidades. A página apresenta um design moderno com uma seção introdutória que destaca o propósito da plataforma.

## Características

- **Design Responsivo**: Adaptável para dispositivos desktop, tablet e mobile
- **Animações Interativas**: Efeitos de hover em botões e ícones sociais
- **Fontes Personalizadas**: Utiliza as fontes Open Sans e Poppins do Google Fonts
- **Ícones Sociais**: Integração com Font Awesome para ícones de redes sociais

## Tecnologias Utilizadas

- HTML5
- CSS3
- Font Awesome 5.15.4
- Google Fonts

## Estrutura de Arquivos

```
/
├── index.html
├── src/
│   ├── css/
│   │   ├── reset.css
│   │   ├── estilos.css
│   │   └── responsivo.css
│   └── images/
│       ├── bg-desktop.svg
│       ├── bg-mobile.svg
│       ├── favicon-32x32.png
│       ├── illustration-mockups.svg
│       └── logo.svg
└── README.md
```

## Como Usar

1. Clone este repositório
2. Abra o arquivo `index.html` em seu navegador

## Responsividade

A landing page é totalmente responsiva, com três pontos de quebra principais:

- **Desktop** (≥ 1440px): Layout em duas colunas com imagem à esquerda e conteúdo à direita
- **Tablet** (≥ 768px e < 1440px): Layout adaptado para telas médias com elementos reorganizados
- **Mobile** (≥ 425px e < 768px): Layout otimizado para dispositivos móveis com background adaptado
- **Smartphone** (< 425px): Layout altamente otimizado para smartphones com ajustes específicos de tamanho e espaçamento

## Detalhes de Implementação

### Estilo Principal
O arquivo `estilos.css` contém os estilos base da página, incluindo:
- Configuração do background e cores
- Layout usando Flexbox
- Estilização de botões e elementos interativos

### Responsividade
O arquivo `responsivo.css` contém as media queries para adaptar o layout para diferentes tamanhos de tela:
- Media query para 1440px: Ajustes específicos para telas grandes
- Media query para 768px: Alterações para telas de tamanho médio
- Media query para 425px: Otimizações específicas para dispositivos móveis menores, incluindo ajustes de fonte, espaçamento e layout

### Reset CSS
O arquivo `reset.css` garante a consistência entre diferentes navegadores, removendo margens e paddings padrão.

## Personalização

Para personalizar este projeto:

1. Modifique as cores alterando os valores HSL no arquivo CSS
2. Substitua as imagens na pasta `images`
3. Ajuste os tamanhos e espaçamentos no arquivo CSS conforme necessário

## Licença

Este projeto foi construído como parte de um desafio do Frontend Mentor.