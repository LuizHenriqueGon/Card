
<h1 align="center">
  📖 Card Interativo "Ler Mais"
</h1>

<p align="center">
  <strong>Um componente de UI elegante com funcionalidade de expandir e recolher texto.</strong>
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-funcionalidades">Funcionalidades</a> •
  <a href="#-tecnologias">Tecnologias</a> •
  <a href="#-como-executar">Como Executar</a> •
  <a href="#-estrutura">Estrutura</a> •
  <a href="#-autor">Autor</a>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge" alt="Status Concluído">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</div>

<hr>

## 💻 Sobre o Projeto

Este projeto consiste em um **Card de Conteúdo** interativo desenvolvido para interfaces web modernas. O objetivo foi criar um componente que otimiza o espaço na tela, ocultando textos longos inicialmente e permitindo que o usuário expanda o conteúdo clicando em um botão "Read More" (Ler Mais).

O design segue uma estética "Dark Mode" com detalhes em verde neon, utilizando gradientes para suavizar a quebra do texto.

---

## ⚙️ Funcionalidades

- [x] **Expansão de Texto:** O card inicia com altura fixa e expande automaticamente para mostrar todo o conteúdo ao clicar no botão.
- [x] **Efeito Fade:** Um gradiente sobre o texto cria um efeito visual suave indicando que há mais conteúdo para ler.
- [x] **Toggle Dinâmico:** O botão alterna seu texto entre "Read More" e "Read Less" e o card ajusta sua altura e estilos via manipulação de classes (`.active`).
- [x] **Design Responsivo:** Centralizado na tela e adaptável.

---

## 🚀 Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estrutura semântica.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):**
  - **Flexbox:** Para centralização do layout.
  - **Pseudo-elementos:** (`::before`) para criar os detalhes visuais (triângulo no canto e gradiente de texto).
  - **Transições:** Para suavizar as interações dos botões.
- **[JavaScript (Vanilla)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Manipulação do DOM (classList e eventListeners) para a lógica de abrir/fechar.

---

## 📂 Estrutura de Pastas

```bash
├── assets/
│   ├── css/
│   │   └── style.css     # Estilos do card e animações
│   ├── images/
│   │   └── icon.svg      # Ícone ilustrativo do card
│   └── js/
│       └── script.js     # Lógica do botão Read More
└── index.html            # Estrutura principal
````

-----

## 🔧 Como Executar

Este é um projeto estático, não requer instalação de dependências.

1.  **Clone este repositório:**
    ```bash
    git clone [https://github.com/LuizHenriqueGon/NOME-DO-REPOSITORIO.git](https://github.com/LuizHenriqueGon/NOME-DO-REPOSITORIO.git)
    ```
2.  **Acesse a pasta do projeto:**
    Navegue até o diretório onde os arquivos foram salvos.
3.  **Abra o projeto:**
    Basta dar um duplo clique no arquivo `index.html` para abri-lo em seu navegador padrão.
