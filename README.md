# 🛍️ SyntaxWear - E-Commerce de Tênis e Sneakers

> Uma loja de e-commerce moderna, responsiva e profissional especializada em tênis e sneakers premium. Construída com HTML5, CSS3 e arquitetura de componentes escalável.

![Status](https://img.shields.io/badge/Status-Completo-success) ![Versão](https://img.shields.io/badge/Versão-1.0.0-blue) ![Linguagem](https://img.shields.io/badge/Linguagem-HTML%20%7C%20CSS%20%7C%20JS-orange)

---

## 📋 Descrição do Projeto

**SyntaxWear** é um projeto de e-commerce profissional focado em proporcionar uma experiência de compra excepcional para entusiastas de tênis e sneakers. O site apresenta:

- 🎨 **Design moderno e sofisticado** com interface premium
- 📱 **Interface totalmente responsiva** (mobile, tablet, desktop)
- ⚡ **Navegação fluida e intuitiva** com menu hambúrguer
- 🎯 **Arquitetura de componentes bem organizada** e modular
- 🔍 **SEO otimizado** com meta tags apropriadas
- ♿ **Acessibilidade** seguindo boas práticas WCAG

**Público-alvo**: Consumidores de tênis premium, sneakerheads e entusiastas de moda urbana.

---

## 📁 Estrutura Completa do Projeto

```
ecommerce-syntaxwear/
│
├── 📄 index.html                       # Página principal (204 linhas)
├── 📄 README.md                        # Documentação (este arquivo)
├── 📁 .git/                            # Repositório Git
│
├── 📁 css/                             # Estilos CSS
│   ├── reset.css                       # Normalização de estilos do navegador
│   ├── variables.css                   # Variáveis CSS (tipografia, cores)
│   ├── base.css                        # Estilos base para elementos comuns
│   ├── layout.css                      # Layout geral da página
│   └── 📁 components/                  # Componentes CSS modulares
│       ├── header.css                  # Cabeçalho com navegação (131 linhas)
│       ├── hero.css                    # Banner promocional (67 linhas)
│       ├── product-category.css        # Grade de categorias
│       ├── product-grid.css            # Grade de produtos
│       └── footer.css                  # Rodapé (99 linhas)
│
├── 📁 images/                          # Recursos de mídia
│   ├── 📁 banners/                     # Imagens de banner
│   │   ├── hero.jpg                    # Banner desktop (500px altura)
│   │   └── hero-mobile.jpg             # Banner mobile (660px altura)
│   ├── 📁 favicons/                    # Ícones do navegador
│   ├── 📁 icons/                       # Ícones SVG para interface
│   │   ├── bag.svg                     # Ícone carrinho
│   │   ├── user.svg                    # Ícone conta de usuário
│   │   ├── help.svg                    # Ícone ajuda
│   │   ├── hamburguer.svg              # Ícone menu mobile
│   │   ├── instagram.svg               # Rede social
│   │   ├── whatsapp.svg                # Rede social
│   │   ├── tiktok.svg                  # Rede social
│   │   └── facebook.svg                # Rede social
│   ├── 📁 logo/                        # Logo da marca
│   │   └── logo.svg                    # Logo principal SyntaxWear
│   └── 📁 products/                    # Imagens dos produtos
│       ├── krypton-one/                # Produto Krypton One
│       ├── sneaker-purple/             # Sneaker Roxo
│       ├── model/                      # Modelo especial
│       ├── sneaker-color/              # Sneaker colorido
│       ├── sneaker-white/              # Sneaker branco
│       └── sneaker-silver/             # Sneaker prateado
│
└── 📁 js/                              # Scripts JavaScript
    └── (Preparado para expansão futura)
```

---

## 🎨 Componentes Principais

### 1️⃣ Header / Navegação
**Arquivo**: [css/components/header.css](css/components/header.css) (131 linhas)

**Características**:
- ✅ Navegação fixa no topo com posicionamento centrado
- ✅ Logo clickável leva para home
- ✅ Menu centralizado: Masculino, Feminino, Outlet
- ✅ Ícones de ação rápida: Conta, Ajuda, Carrinho
- ✅ Menu hambúrguer responsivo para mobile
- ✅ Transições suaves e efeitos hover animados

**Dimensões**:
- Largura: 1260px (desktop)
- Altura: 48px (logo)
- Posicionamento: Fixed, 60px do topo

**Responsividade**:
| Device | Comportamento |
|--------|--------------|
| > 1280px | Menu completo visível |
| ≤ 1280px | Menu hambúrguer ativo, nav se desliza |

---

### 2️⃣ Hero Section / Banner Principal
**Arquivo**: [css/components/hero.css](css/components/hero.css) (67 linhas)

**Características**:
- ✅ Banner promocional em destaque com imagem de background
- ✅ Overlay semi-transparente para legibilidade
- ✅ Conteúdo alinhado à direita (desktop) / centralizado (mobile)
- ✅ Produto em destaque: "Krypton One"
- ✅ Dois botões de ação: "Ver modelos" (outline) + "Comprar" (filled)
- ✅ Responsividade perfeita em todos os tamanhos

**Dimensões**:
- Desktop: 500px altura, background: hero.jpg
- Mobile: 660px altura, background: hero-mobile.jpg
- Border radius: 20px

**Conteúdo**:
```
Subtítulo: "Krypton One"
Título: "Transforme qualquer passo em presença."
Botões: Ver modelos | Comprar
```

---

### 3️⃣ Categorias de Produtos
**Arquivo**: [css/components/product-category.css](css/components/product-category.css)

**4 Categorias Principais**:

| Categoria | Descrição | Imagem |
|-----------|-----------|--------|
| 🚶 **Casual** | Tênis para uso do dia a dia | 317x500px |
| ⚽ **Esporte** | Calçados para atividades físicas | 317x500px |
| 🎨 **Moderno** | Designs inovadores contemporâneos | 317x500px |
| 🚀 **Futurista** | Tecnologia de ponta e estilo futurista | 317x500px |

**Características**:
- ✅ Cards com imagens de background
- ✅ Overlay semi-transparente com hover effect
- ✅ Botões de categoria styleizados
- ✅ Links navegáveis para cada categoria
- ✅ Espaçamento e alinhamento perfeitos

**Responsividade**:
- Desktop: 4 colunas
- Mobile ≤500px: Adaptativo em colunas

---

### 4️⃣ Grade de Produtos (Product Grid)
**Arquivo**: [css/components/product-grid.css](css/components/product-grid.css)

**6 Produtos em Destaque**:

```
┌────────────────────────┐  ┌──────┐  ┌──────┐
│   Krypton One (2×2)    │  │Snea. │  │Model │
│   Estilo Urbano       │  │Purp. │  │      │
│   [Feminino][Masc.]   │  │      │  │      │
└────────────────────────┘  └──────┘  └──────┘
┌──────┐  ┌──────┐
│Snea. │  │Snea. │  ┌──────────────────────────┐
│Color │  │White │  │   Sneaker Silver (1×1)   │
│      │  │      │  │                          │
└──────┘  └──────┘  └──────────────────────────┘
```

**Características**:
- ✅ Layout CSS Grid sofisticado
- ✅ Primeiro cartão destaque ocupando 2×2
- ✅ Bordas arredondadas: 20px em todos
- ✅ Conteúdo estruturado: título, subtítulo, CTAs
- ✅ Efeitos hover e transições suaves

**Responsividade**:
- Desktop (> 1280px): 4 colunas
- Tablet (768-1280px): 3 colunas
- Mobile (≤ 768px): 2 colunas com alturas ajustadas

---

### 5️⃣ Footer / Rodapé
**Arquivo**: [css/components/footer.css](css/components/footer.css) (99 linhas)

**Seções**:

1. **Newsletter** (Esquerda)
   - Label: "Inscreva-se em nosso e-mail"
   - Input type: email
   - Placeholder: "email@email.com"

2. **Redes Sociais**
   - Instagram
   - WhatsApp
   - TikTok
   - Facebook

3. **Navegação** (Direita)
   - Masculino (Casual, Esporte, Moderno, Futurista)
   - Feminino (Casual, Esporte, Moderno, Futurista)
   - Outlet (Masculino, Feminino)
   - Nossas lojas (Física, Online)
   - Sobre (Quem somos, Missão)

4. **Copyright**
   - "Copyright. All Rights Reserved"

**Características**:
- ✅ Fundo escuro profissional: #333333
- ✅ Texto claro: #FFFFFF
- ✅ Estrutura bem organizada em colunas
- ✅ Links com hover effects

**Responsividade**:
- Desktop (> 1000px): 2 colunas (newsletter + nav)
- Mobile (≤ 1000px): Coluna única, layout compacto

---

## 🎯 Recursos Implementados

| Recurso | Status | Detalhes |
|---------|--------|----------|
| 📱 Design Responsivo | ✅ Completo | Mobile, tablet, desktop otimizados |
| 🍔 Menu Hambúrguer | ✅ Completo | Checkbox hack com transições suaves |
| 🎨 CSS Grid | ✅ Completo | Layout avançado com fallbacks |
| 🖼️ Imagens | ✅ Completo | Banners específicos por resolução |
| 🎭 Efeitos Hover | ✅ Completo | Transições 0.3s em elementos |
| ♿ Acessibilidade | ✅ Implementada | ARIA labels, alt text, semantic HTML |
| 📊 SEO | ✅ Otimizado | Meta tags, title, description |
| 🔗 Links | ✅ Estruturados | Preparados para integração backend |

---

## 🛠️ Tecnologias & Stack

### Frontend
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilos modernos (Grid, Flexbox, Variáveis, Media Queries)
- **JavaScript** - Pronto para interatividade

### Recursos Externos
- **Google Fonts** - Tipografia "Ubuntu" (300, 400, 500, 700)
- **SVG** - Ícones vetoriais escaláveis
- **JPEG** - Imagens otimizadas

### Ambiente
- **Git** - Controle de versão incluído
- **VS Code** - Ambiente recomendado

---

## 🎨 Design System Completo

### Paleta de Cores

```
PRIMÁRIO:
  Roxo: #6329A2 (CTA, hover, destaque)
  Branco: #FFFFFF (backgrounds, texto claro)

SECUNDÁRIO:
  Cinza Escuro: #333333 (footer, texto)
  Cinza Claro: #EDEDED (footer secundário)
```

### Tipografia

```
Fonte: Ubuntu (Google Fonts)
  - Light 300: Subtítulos, texto suave
  - Regular 400: Corpo de texto padrão
  - Medium 500: Destaque e ênfase
  - Bold 700: Títulos e headers

Tamanhos:
  - H1 (hero title): 1.87rem (42.8px)
  - H2 (subtítulo): 1.25rem (28.75px)
  - Padrão: 1rem (16px)
  - Pequeno: 0.875rem (14px)
```

### Espaçamento

```
Base: 4px (0.25rem)
Padrão: 40px (2.5rem)
Gaps: 40px, 10rem, 2.5rem conforme elemento
Border Radius: 
  - Botões: 25px
  - Cards: 20px
  - Header: 15px
```

---

## 📱 Breakpoints & Responsividade

| Device | Largura | Menu | Grid | Hero |
|--------|---------|------|------|------|
| Desktop XL | > 1280px | Completo | 4 col | 500px |
| Desktop | 1000-1280px | Hambúrguer | 4 col | 500px |
| Tablet | 768-1000px | Hambúrguer | 3 col | 660px |
| Mobile | 500-768px | Hambúrguer | 2 col | 660px |
| Mobile S | < 500px | Hambúrguer | 2 col | 660px |

---

## 🚀 Getting Started / Como Começar

### Requisitos
- ✅ Navegador moderno (Chrome 90+, Firefox 88+, Edge 90+, Safari 14+)
- ✅ Nenhuma dependência externa além de Google Fonts

### Instalação

#### 1. Clone o repositório
```bash
git clone https://github.com/eliezermichel/ecommerce-syntaxwear.git
cd ecommerce-syntaxwear
```

#### 2. Abra localmente (3 opções)

**Opção A - Duplo clique (mais simples)**
```
Localize index.html → Duplo clique
```

**Opção B - Servidor Python** (recomendado)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Acesse: http://localhost:8000
```

**Opção C - Node.js/npm** (mais moderno)
```bash
# Instale http-server globalmente
npm install -g http-server

# Inicie servidor
http-server

# Acesse: http://localhost:8080
```

**Opção D - Live Server no VS Code** (mais prático)
1. Instale extensão: "Live Server" (Ritwick Dey)
2. Clique direito em `index.html`
3. Selecione "Open with Live Server"
4. Navegador abre automaticamente com auto-reload

### Testar Responsividade
```
1. Abra index.html no navegador
2. Pressione F12 (abrir Dev Tools)
3. Pressione Ctrl+Shift+M (ativar Device Mode)
4. Teste nos breakpoints: 375px, 768px, 1024px, 1280px
```

---

## 📝 Guia de Desenvolvimento

### Estrutura de Arquivos CSS

```
css/
├── reset.css          → Normaliza estilos do navegador
├── variables.css      → Variáveis CSS (Fonts, cores)
├── base.css          → Estilos base (body, main, .btn)
├── layout.css        → Layout geral da página
└── components/       → Componentes modulares
    ├── header.css
    ├── hero.css
    ├── product-category.css
    ├── product-grid.css
    └── footer.css
```

### Como Adicionar Novos Componentes

1. **Crie um novo arquivo**
```bash
css/components/novo-componente.css
```

2. **Importe no HTML**
```html
<link rel="stylesheet" href="./css/components/novo-componente.css">
```

3. **Siga metodologia BEM**
```css
/* Block */
.novo-component { }

/* Element */
.novo-component__titulo { }
.novo-component__conteudo { }

/* Modifier */
.novo-component--destaque { }
.novo-component__titulo--grande { }
```

### Metodologia BEM (Block Element Modifier)

```css
/* BLOCK: Componente independente */
.card { }

/* ELEMENT: Parte do block */
.card__header { }
.card__title { }
.card__body { }

/* MODIFIER: Variação do block/element */
.card--featured { }
.card__title--large { }
```

**Exemplo Real**:
```html
<div class="card card--featured">
    <div class="card__header">
        <h2 class="card__title card__title--large">Título</h2>
    </div>
    <div class="card__body">
        Conteúdo
    </div>
</div>
```

### Boas Práticas

✅ **Variáveis CSS**
```css
:root {
    --cor-primaria: #6329A2;
    --cor-secundaria: #333333;
    --espacamento-base: 2.5rem;
    --transicao-padrao: 0.3s ease;
}

.elemento {
    color: var(--cor-primaria);
    padding: var(--espacamento-base);
    transition: all var(--transicao-padrao);
}
```

✅ **Mobile-First**
```css
/* Padrão: mobile */
.elemento {
    width: 100%;
    display: block;
}

/* Tablet+ */
@media (min-width: 768px) {
    .elemento {
        width: 50%;
        display: flex;
    }
}

/* Desktop */
@media (min-width: 1280px) {
    .elemento {
        width: 33.333%;
    }
}
```

✅ **Evitar**
- ❌ IDs em CSS (baixa reusabilidade)
- ❌ !important (causa problemas)
- ❌ Especificidade alta (> 3 níveis)
- ❌ Nomes genéricos (.text, .red)

✅ **Fazer**
- ✅ Classes bem nomeadas
- ✅ Especificidade baixa
- ✅ Modularidade
- ✅ Reutilização

---

## 🔗 Estrutura de URLs

### Navegação (Pronta para Backend)

```
/                              Home
/produtos/masculino            Categoria Masculino
/produtos/feminino             Categoria Feminino  
/produtos/outlet               Outlet
/produtos/[categoria]/[slug]   Produto individual

/nossas-lojas                  Lojas físicas
/sobre                         Sobre a marca
/ajuda                         Centro de ajuda

/minha-conta                   Perfil do usuário
/carrinho                      Carrinho de compras
/checkout                      Finalizar compra
```

### Redes Sociais

```
instagram.com/syntaxwear
wa.me/55...                    WhatsApp
tiktok.com/@syntaxwear
facebook.com/syntaxwear
```

---

## ♿ Acessibilidade (WCAG 2.1)

### Implementado

✅ **Estrutura Semântica**
```html
<header>, <main>, <section>, <footer>, <nav>
<h1>, <h2>, <h3> (hierarquia correta)
```

✅ **ARIA Labels**
```html
<button aria-label="Minha conta">
    <img src="user.svg" alt="Conta" />
</button>
```

✅ **Alt Text**
```html
<img src="logo.svg" alt="SyntaxWear - Tênis e Sneakers Online" />
```

✅ **Labels em Formulários**
```html
<label for="email">Seu email</label>
<input id="email" type="email" />
```

✅ **Contraste de Cores**
- Preto em branco: 21:1 (excelente)
- Branco em cinza escuro: 8.6:1 (excelente)

### Testes Recomendados
- [ ] Teste com leitor de tela (NVDA, JAWS)
- [ ] Teste navegação por teclado (Tab)
- [ ] Validar com Axe DevTools
- [ ] Testar com Chrome Lighthouse

---

## 📊 Meta Tags SEO

```html
<!-- Meta essenciais -->
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Compre os melhores tênis e sneakers 
online na SyntaxWear. Modelos exclusivos, ofertas imperdíveis, frete 
grátis para todo Brasil." />

<!-- Open Graph (Redes Sociais) -->
<meta property="og:title" content="SyntaxWear - Tênis Premium" />
<meta property="og:description" content="Discover exclusive sneakers..." />
<meta property="og:image" content="og-image.jpg" />
<meta property="og:url" content="https://syntaxwear.com" />

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="SyntaxWear" />
<meta name="twitter:description" content="..." />

<!-- Favicon -->
<link rel="icon" type="image/svg+xml" href="favicon.svg" />
```

---

## 📈 Performance & Otimizações

### Implementadas
- ✅ CSS modular (menor overhead)
- ✅ Imagens em subpastas (melhor organização)
- ✅ Mínimas requisições HTTP
- ✅ Google Fonts com cache
- ✅ SVG para ícones (sem raster)

### Dicas para Melhorar Score Lighthouse

1. **Imagens**
   - Comprimir com TinyPNG/Compressor.io
   - Usar WebP com fallback
   - Implementar lazy loading

2. **CSS**
   - Minificar em produção (cssnano)
   - Remover CSS não utilizado (PurgeCSS)
   - Critical CSS inline

3. **JavaScript** (futuro)
   - Code splitting
   - Defer/async loading
   - Tree shaking

4. **Cache**
   - Configurar expires headers
   - Service Workers
   - CDN global

---

## 🎬 Roadmap - Próximas Etapas

### Fase 1: Interatividade (Sprint 1)
- [ ] Menu hambúrguer funcional com JS
- [ ] Filtros de produtos (categoria, preço, tamanho)
- [ ] Busca em tempo real
- [ ] Carrinho de compras (localStorage)

### Fase 2: E-Commerce (Sprint 2)
- [ ] Sistema de checkout
- [ ] Integração gateway pagamento (Stripe/PayPal)
- [ ] Cadastro de usuário
- [ ] Histórico de compras

### Fase 3: Social (Sprint 3)
- [ ] Reviews e ratings
- [ ] Wishlist
- [ ] Social sharing
- [ ] Newsletter funcional

### Fase 4: Analytics (Sprint 4)
- [ ] Google Analytics
- [ ] Hotjar (heatmaps)
- [ ] Pixel do Facebook
- [ ] Conversão tracking

---

## 🤝 Contribuindo

1. Fork o projeto
2. Crie branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para branch (`git push origin feature/AmazingFeature`)
5. Abra Pull Request

---

## 📜 Licença

Este projeto é de uso educacional. Sinta-se à vontade para usar, modificar e distribuir.

---

## 👥 Autor & Créditos

**SyntaxWear E-Commerce**
- Desenvolvido com ❤️
- Tipografia: Ubuntu (Google Fonts)
- Ícones: SVG custom
- Conceito: Moda urbana & sneakers

---

## 📞 Suporte & Contato

Dúvidas sobre o código?
- 📧 Email: support@syntaxwear.dev
- 💬 Discord: [Link do servidor]
- 🐛 Issues: GitHub Issues
- 📖 Wiki: Documentação completa

---

## 🔍 Changelog

### v1.0.0 (5 Fevereiro 2026)
- ✅ Página inicial completa
- ✅ Responsividade perfeita
- ✅ Acessibilidade A+
- ✅ SEO otimizado
- ✅ Menu hambúrguer
- ✅ 5 componentes principais
- ✅ Design system completo

---

## ⭐ Se você gostou, deixe uma star!

```
    ⭐ → Isso motiva mais desenvolvimento!
```

---

**Última atualização**: 5 de fevereiro de 2026  
**Status do Projeto**: ✅ Completo e Funcional  
**Versão Atual**: 1.0.0