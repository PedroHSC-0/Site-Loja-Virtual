<div align="center">

# 📻 Guided by Noises — Virtual Vinyl Shop

<p align="center">
  <strong>Uma experiência e-commerce conceitual dedicada ao Slacker Rock, Lo-Fi e garimpo de vinis underground.</strong>
</p>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap%205.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()

</div>

---

## 📌 Sobre o Projeto

O **Guided by Noises** é uma loja virtual conceitual desenvolvida para colecionadores e entusiastas de vinil, focada no ecossistema de mídias físicas, música indie e cultura lo-fi. 

Diferente de e-commerces convencionais e genéricos, a interface foi desenhada com uma **identidade visual autoral ("FITA & RUÍDO")**, inspirada em encartes de fitas cassete, colagens analógicas e capas icônicas do rock alternativo dos anos 90 (como *Bee Thousand* do *Guided by Voices*).

> *"Traga o ritual de ouvir música de volta para o seu espaço. Discos novos e usados selecionados a dedo."*

---

## ✨ Destaques & Funcionalidades

- 🎛️ **Identidade Analógica "FITA & RUÍDO"**: Overlay estético em SVG com textura de ruído/chiado analógico dinâmico (`fractalNoise`) animado via CSS.
- 💿 **Animações Temáticas**: Ícone de vinil em rotação contínua e equalizador gráfico dinâmico em barras CSS animadas.
- 📚 **Catálogo Organizado por Seções**: Navegação por artistas e bandas (*Guided by Voices*, *Alex G*, *Dinosaur Jr*, *Peter Cat Recording Co*).
- 🏷️ **Cards de Produtos Detalhados**: Badges de status para itens (*Último*, *Novo*, *Esgotado*), preços formatados e botões de ação rápida.
- 🎠 **Carrossel Interativo Hero & Seções**: Destaques de lançamentos e garimpos underground alimentados por sliders fluídos.
- 🗂️ **Sidebar retrátil (Drawer)**: Menu lateral interativo com atalhos para os sites oficiais das bandas e parceiros.
- 📱 **Layout Totalmente Responsivo**: Construído sobre o grid do Bootstrap 5 com adaptação fluida para dispositivos móveis, tablets e desktops.

---

## 🎨 Sistema de Design & Paleta de Cores

A interface utiliza um sistema de design próprio com **Variáveis CSS (`:root`)** e tipografia selecionada do Google Fonts:

### 🎨 Paleta de Cores (`FITA & RUÍDO`)
| Cor | Hex | Aplicação |
| :--- | :--- | :--- |
| **Tinta** | `#0d1517` | Fundo principal (quase preto analógico) |
| **Bloco** | `#16242b` | Fundo dos cards e contêineres |
| **Azul Fita** | `#4aa3da` | Cor de destaque, links e seleções |
| **Papel Creme** | `#efe6c7` | Cor primária do texto e rótulos |
| **Selo Raro** | `#d0bfbc` | Carimbos de edições limitadas e tags |
| **Mostarda** | `#e8b32e` | Acentos secundários e acessibilidade |

### 🔤 Tipografia
- **Títulos & Carazes**: `Anton` (Display impactante estilo pôster de show)
- **Texto Principal & Códigos**: `Space Mono` (Monospaçado remetendo a contadores de fita e encartes)
- **Selo & Carimbos**: `Special Elite` (Estilo maquina de escrever / carimbos artesanais)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica das páginas.
- **CSS3 Avançado**: Animações `@keyframes`, variáveis CSS, filtros SVG, layouts Flexbox e Grid.
- **JavaScript (Vanilla)**: Manipulação DOM para o menu lateral (Sidebar Drawer) e componentes interativos.
- **Bootstrap 5.3.3**: Framework responsivo para Grid, Navbar e Carrossel.
- **FontAwesome 6.4.0**: Iconografia vetorizada temática.
- **Google Fonts**: Tipografias personalizadas (*Anton*, *Space Mono*, *Special Elite*).

---

## 📂 Estrutura do Repositório

```text
Site-Loja-Virtual/
├── index.html        # Redirecionamento e ponto de entrada para hospedagem estática
├── home.htm          # Página Principal (Banner Hero, destaques e vitrine)
├── catalogo.htm      # Catálogo completo de discos organizados por artista
├── sobre.htm         # História, manifesto analógico e conceito da loja
├── contato.htm       # Formulário de contato para dúvidas e encomendas
├── style.css         # CSS principal, sistema de design "FITA & RUÍDO" e animações
├── imagens/          # Banners, logotipos e ilustrações da marca
│   ├── logo.jpg
│   └── paineis/
└── produtos/         # Capas dos discos e artes dos produtos do catálogo
```

---

## 🌐 Visão Geral das Páginas

| Página | Descrição |
| :--- | :--- |
| 🏠 **[Início (`home.htm`)](file:///home/pedro/Documentos/GitHub/Site-Loja-Virtual/home.htm)** | Landing page com banner rotativo em alta resolução, manifesto e seleção de discos recomendados. |
| 🎶 **[Catálogo (`catalogo.htm`)](file:///home/pedro/Documentos/GitHub/Site-Loja-Virtual/catalogo.htm)** | Acervo completo com carrosséis por artista, filtros visuais, tags de raridade e preços. |
| 📻 **[Sobre (`sobre.htm`)](file:///home/pedro/Documentos/GitHub/Site-Loja-Virtual/sobre.htm)** | Conceito da loja, manifesto Lo-Fi e resgate da cultura da música física. |
| ✉️ **[Contato (`contato.htm`)](file:///home/pedro/Documentos/GitHub/Site-Loja-Virtual/contato.htm)** | Formulário estilizado para suporte a colecionadores, encomendas e trocas. |

---

## 🚀 Como Executar o Projeto Localmente

### Opção 1: Diretamente no Navegador
1. Clone este repositório:
   ```bash
   git clone https://github.com/PedroHSC-0/Site-Loja-Virtual.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd Site-Loja-Virtual
   ```
3. Abra o arquivo `home.htm` ou `index.html` em seu navegador de preferência.

### Opção 2: Com o VS Code Live Server
1. Abra a pasta do projeto no **VS Code**.
2. Clique com o botão direito no arquivo `home.htm`.
3. Selecione **Open with Live Server**.

### Opção 3: Servidor Python local
```bash
python3 -m http.server 8000
```
Acesse `http://localhost:8000` no seu navegador.

---

## 👤 Autor

Desenvolvido por **Pedro** no seu processo de constante evolução e organização de portfólio.

[![GitHub](https://img.shields.io/badge/GitHub-PedroHSC--0-181717?style=flat-square&logo=github)](https://github.com/PedroHSC-0)

---

<div align="center">
  <sub>Guided by Noises — Feito com paixão pela cultura do disco de vinil 🎧</sub>
</div>
