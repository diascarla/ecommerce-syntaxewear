# SyntaxeWear - Landing Page de E-commerce

Este é o repositório da landing page para a **SyntaxeWear**, uma marca fictícia de tênis e sneakers. O projeto foi desenvolvido com foco em um design moderno, responsivo e em boas práticas de estruturação de código HTML e CSS.

## ✨ Funcionalidades

## 🖥️ Visualização

![Pré-visualização da página SyntaxeWear](./images/preview/animação.gif)

-   **Design Responsivo**: A página se adapta a diferentes tamanhos de tela, desde desktops até dispositivos móveis.
-   **Cabeçalho Fixo**: O menu de navegação permanece fixo no topo da tela para fácil acesso.
-   **Menu Hambúrguer**: Em telas menores, a navegação é convertida em um menu hambúrguer funcional, utilizando a técnica "checkbox hack".
-   **Layout em Grid**: A seção de produtos utiliza um layout complexo e assimétrico criado com CSS Grid Layout.
-   **Componentização**: O CSS é organizado em componentes (header, footer, hero, etc.), facilitando a manutenção e escalabilidade.
-   **Efeitos de Hover**: Microinterações em botões, links e imagens para melhorar a experiência do usuário.

## 🚀 Tecnologias Utilizadas

-   **HTML5**: Estrutura semântica para o conteúdo da página.
-   **CSS3**: Estilização moderna e responsiva, utilizando recursos avançados como:
    -   **Flexbox**: Para alinhamento de componentes como o cabeçalho e o rodapé.
    -   **CSS Grid Layout**: Para a criação do layout complexo da galeria de produtos.
    -   **Custom Properties (Variáveis CSS)**: Para um tema consistente e fácil de modificar.
    -   **Media Queries**: Para garantir a responsividade em diferentes dispositivos.

## 📂 Estrutura de Arquivos

O projeto está organizado da seguinte forma para garantir clareza e manutenibilidade:

```
/
├── css/
│   ├── components/
│   │   ├── categories.css
│   │   ├── footer.css
│   │   ├── header.css
│   │   ├── hero.css
│   │   ├── product-category.css
│   │   └── product-grid.css
│   ├── base.css
│   ├── layout.css
│   ├── reset.css
│   └── variables.css
│
├── images/
│   ├── banners/
│   ├── icons/
│   ├── logo/
│   └── products/
│
└── index.html
```

-   **`index.html`**: O arquivo principal que contém toda a estrutura da página.
-   **`css/`**: Pasta com todos os arquivos de estilização.
    -   **`components/`**: Cada arquivo corresponde a um componente específico da página.
    -   **`reset.css`**: Normaliza os estilos padrão dos navegadores.
    -   **`variables.css`**: Centraliza as variáveis CSS (cores, fontes, etc.).
    -   **`layout.css`**: Define os principais contêineres e a estrutura geral do layout.
    -   **`base.css`**: Estilos básicos aplicados a todo o projeto.
-   **`images/`**: Contém todos os recursos visuais, organizados por tipo.

## 💻 Como Executar

Por ser um projeto estático (apenas HTML e CSS), você pode simplesmente abrir o arquivo `index.html` em qualquer navegador web.

Para uma melhor experiência de desenvolvimento, recomenda-se o uso de um servidor local. Se você utiliza o Visual Studio Code, pode instalar a extensão **Live Server** para visualizar o projeto e ter recarregamento automático ao salvar as alterações.

---
