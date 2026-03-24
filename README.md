<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f8a99c,100:f28c7d&height=200&section=header&text=Bella%20Dona&fontSize=70&fontAlignY=35&animation=fadeIn&fontColor=white"/>
  
  <img src="img/logo_fim.png" alt="Bella Dona Logo" width="280"/>
  
  ### **E-commerce de Cosméticos**
  
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
  [![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
  
  ![Status](https://img.shields.io/badge/Status-Concluído-28a745?style=for-the-badge)
  ![SPA](https://img.shields.io/badge/Architecture-SPA-ff69b4?style=for-the-badge)
  
  > *Atividade acadêmica de Desenvolvimento Web I — FATEC Cotia*

</div>

---

## 📖 Sobre o Projeto

A **Bella Dona** é uma loja virtual de cosméticos desenvolvida como atividade da disciplina de **Desenvolvimento Web I**. O projeto simula um e-commerce completo com navegação dinâmica entre seções sem recarregamento, utilizando o padrão **SPA (Single Page Application)** com `<template>` e JavaScript puro.

A identidade visual da marca utiliza tons **rosé, salmão e terracota**, com tipografia da família **Poppins**, transmitindo elegância, acolhimento e modernidade — valores que conversam diretamente com o público feminino que busca beleza e autocuidado.

---

## ✨ Funcionalidades

<div align="center">
  
| | | |
|:---:|:---:|:---:|
| 🛍️ **Catálogo de Produtos** | 🎠 **Carrossel de Destaques** | 🔐 **Página de Login** |
| 9 itens com cards interativos | Bootstrap Carousel animado | Formulário estilizado |
| 🛒 **Carrinho de Compras** | 💳 **Checkout** | 👤 **Menu do Usuário** |
| Tabela dinâmica + resumo | Validação nativa Bootstrap | Dropdown Login/Registrar |
| 🔍 **Barra de Busca** | 📱 **Responsividade** | ⚡ **Navegação SPA** |
| Filtro no header | Mobile → Desktop | Sem recarregamento |

</div>

---

## 🗂️ Estrutura do Projeto

```bash
belladona/
├── 📄 index.html               # Página principal (SPA)
├── 📄 login.html               # Página de login separada
└── 📁 img/
    ├── 🖼️ logo_fim.png         # Logo principal
    ├── 🖼️ logo.png             # Variação do logo
    ├── 🖼️ logo_2.png           # Variação do logo
    ├── 🖼️ banner.png           # Banner do header
    ├── 🖼️ base.png             # Base Líquida
    ├── 🖼️ batom_liquido.png    # Batom Líquido
    ├── 🖼️ blush.png            # Blush
    ├── 🖼️ body_splash.png      # Body Splash
    ├── 🖼️ kit_banho.png        # Kit Banho Premium
    ├── 🖼️ kit_paleta_colorida_-_carnaval.png
    ├── 🖼️ kit_skin_care.png    # Kit Skin Care
    ├── 🖼️ Mascara_de_Cílios.png
    └── 🖼️ pincel.png           # Kit Pincéis
```

---

## 🛠️ Stack Tecnológica

<div align="center">
  
| Tecnologia | Finalidade |
|------------|------------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20"/> **HTML5** | Estrutura semântica |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20"/> **CSS3** | Estilização + animações |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20"/> **JavaScript ES6+** | Lógica SPA + navegação |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="20"/> **Bootstrap 5.3** | Grid + componentes |
| <img src="https://fontawesome.com/icons" width="20"/> **Font Awesome 6** | Ícones vetoriais |
| <img src="https://fonts.gstatic.com/s/poppins/v20/pxiByp8kv8JHgFVrLEj6Z1xlFQ.woff2" width="20"/> **Poppins** | Tipografia principal |

</div>

---

## 📄 Navegação SPA

O `index.html` utiliza o padrão **SPA com `<template>`**: ao clicar em um item da navbar, o JavaScript troca o conteúdo da `<div id="dynamicContent">` sem recarregar a página.

| Página / Template | Rota | Descrição |
|:---:|:---:|---|
| 🏠 **Catálogo** | `data-page="catalog"` | Carrossel + grid de produtos |
| 🛒 **Carrinho** | `data-page="cart"` | Tabela de itens + resumo |
| 💳 **Checkout** | `data-page="checkout"` | Endereço + pagamento |
| 🔐 **Login** | `login.html` | Página separada |

---

## 🎨 Identidade Visual

<div align="center">
  
| Elemento | Cor | Código |
|:---|:---:|:---:|
| **Primária** | Rosa | `#f8a99c` |
| **Secundária** | Salmão | `#f28c7d` |
| **Destaque** | Vermelho | `#dc3545` |
| **Fundo** | Terracota claro | `#faf0e2` |
| **Tipografia** | Poppins | `'Poppins', sans-serif` |

</div>

---

## ▶️ Como Executar

Por se tratar de um projeto **100% front-end**, não é necessária nenhuma instalação adicional.

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/belladona.git
cd belladona

# 2. Abra no navegador
open index.html   # macOS
start index.html  # Windows
```

> 💡 **Dica:** Para melhor experiência, utilize a extensão **Live Server** no VS Code — clique com botão direito em `index.html` → *"Open with Live Server"*

⚠️ **Atenção:** Certifique-se de que todas as imagens estejam na pasta `img/` com os nomes exatos listados na estrutura acima.

---

## 👥 Equipe de Desenvolvimento

<div align="center">
  
| <img src="https://ui-avatars.com/api/?background=f8a99c&color=fff&bold=true&size=80&name=Ana+Clara" width="60" height="60" style="border-radius: 50%"> | <img src="https://ui-avatars.com/api/?background=f8a99c&color=fff&bold=true&size=80&name=Jennifer" width="60" height="60" style="border-radius: 50%"> | <img src="https://ui-avatars.com/api/?background=f8a99c&color=fff&bold=true&size=80&name=Martie" width="60" height="60" style="border-radius: 50%"> | <img src="https://ui-avatars.com/api/?background=f8a99c&color=fff&bold=true&size=80&name=Maysa" width="60" height="60" style="border-radius: 50%"> | <img src="https://ui-avatars.com/api/?background=f8a99c&color=fff&bold=true&size=80&name=Victoria" width="60" height="60" style="border-radius: 50%"> |
|---|---|---|---|---|
| **Ana Clara Madeira de Gois** | **Jennifer Gabriely Lopes dos Santos** | **Martie Bello Silva** | **Maysa Alexandre Nazario** | **Victória Heloísa de Melo Teixeira** |

</div>

---

## 🎓 Contexto Acadêmico

<div align="center">
  
| | |
|:---|:---|
| 🏛️ **Instituição** | FATEC Cotia |
| 📚 **Curso** | Desenvolvimento de Software Multiplataforma (DSM) |
| 💻 **Disciplina** | Desenvolvimento Web I |
| 📍 **Semestre** | 1º Semestre |
| 📅 **Período** | 2024 |
| 🎯 **Tipo** | Atividade Prática — Front-end |

</div>

---

<div align="center">
  <br>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f8a99c,100:f28c7d&height=100&section=footer"/>
  
</div>
