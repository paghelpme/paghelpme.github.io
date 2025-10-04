# AGENTS.md - Documentação Técnica para Agentes de IA

## 📋 Visão Geral do Projeto

Este é o site oficial do **Paghelp.me**, um aplicativo PIX que funciona 100% offline para gerenciamento de chaves PIX. O site serve como landing page e blog informativo sobre PIX, segurança digital e funcionalidades do aplicativo.

### 🎯 Objetivo Principal
- Apresentar o aplicativo Paghelp.me
- Educar usuários sobre PIX e segurança digital
- Fornecer tutoriais e comparativos de aplicativos PIX
- Manter presença online otimizada para SEO

---

## 🏗️ Estrutura do Site

### 📁 Estrutura de Arquivos

```
paghelpme.github.io/
├── index.html                    # Landing page principal
├── 404.html                      # Página de erro 404
├── CNAME                         # Configuração de domínio customizado
├── robots.txt                    # Diretivas para web crawlers
├── sitemap.xml                   # Mapa do site para SEO
├── sitemap.html                  # Versão visual do sitemap
├── app-ads.txt                   # Configuração de publicidade
├── google2f3c5e7032b61a80.html   # Verificação Google Search Console
├── pix.html                      # Página específica sobre PIX
├── README.md                     # Documentação do projeto
├── AGENTS.md                     # Esta documentação técnica
├── privacy/
│   └── index.html                # Política de privacidade
├── blog/
│   ├── index.html                # Página principal do blog
│   ├── feed.xml                  # RSS feed para syndication
│   ├── posts/                    # Artigos do blog
│   │   ├── paghelp-versao-2-0-26-biometria-links-pagamento.html
│   │   ├── 5-melhores-apps-gerenciar-chaves-pix.html
│   │   ├── como-usar-pix-com-seguranca.html
│   │   ├── gerenciar-chaves-pix-offline.html
│   │   └── 5-recursos-essenciais-paghelp.html
│   └── categorias/               # Páginas de categoria do blog
│       ├── seguranca.html
│       ├── apps.html
│       ├── tutoriais.html
│       ├── comparativos.html
│       ├── pix.html
│       └── atualizacoes.html
└── src/
    └── img/                      # Recursos visuais
        ├── logo.png
        ├── metatag.png
        ├── badges/
        └── screenshots/
```

### 🎨 Stack Tecnológico

- **HTML5**: Estrutura semântica moderna
- **CSS3**: Estilização com glass morphism e gradientes
- **Bootstrap 5.3.8**: Framework responsivo
- **Font Awesome 6.0**: Sistema de ícones
- **Google Fonts (Poppins)**: Tipografia consistente
- **JSON-LD**: Dados estruturados para SEO

---

## 📝 Sistema de Blog

### 🔧 Estrutura Técnica do Blog

#### Página Principal (`blog/index.html`)
- **Layout**: Grid responsivo com sidebar
- **Posts**: Organizados cronologicamente (mais recente primeiro)
- **Componentes**:
  - Header com título e descrição
  - Lista de artigos com metadados
  - Sidebar com categorias e CTAs
  - Footer com links sociais

#### Estrutura de Post Individual
```html
<article class="blog-post">
  <h2><a href="./posts/[slug].html" class="blog-post-title">[Título]</a></h2>
  <div class="blog-post-meta">
    <i class="fas fa-calendar"></i>[Data]
    <span>•</span>
    <i class="fas fa-user"></i>[Autor]
    <span>•</span>
    <i class="fas fa-tag"></i>[Categorias]
  </div>
  <p class="blog-post-excerpt">[Resumo]</p>
  <a href="./posts/[slug].html" class="read-more-btn">Ler mais</a>
</article>
```

### 📂 Sistema de Categorias

#### Categorias Implementadas:
1. **Segurança** (`/blog/categorias/seguranca.html`)
   - Foco: Dicas de segurança PIX
   - Posts: 3 artigos
   - Cor tema: Verde escuro (#004d40)

2. **Apps** (`/blog/categorias/apps.html`)
   - Foco: Comparativos de aplicativos
   - Posts: 1 artigo
   - Cor tema: Azul (#1976d2)

3. **Tutoriais** (`/blog/categorias/tutoriais.html`)
   - Foco: Guias passo a passo
   - Posts: 2 artigos
   - Cor tema: Laranja (#ff5722)

4. **Comparativos** (`/blog/categorias/comparativos.html`)
   - Foco: Análises comparativas
   - Posts: 1 artigo
   - Cor tema: Roxo (#673ab7)

5. **PIX** (`/blog/categorias/pix.html`)
   - Foco: Informações gerais sobre PIX
   - Posts: 5 artigos
   - Cor tema: Turquesa (#00acc1)

6. **Atualizações** (`/blog/categorias/atualizacoes.html`)
   - Foco: Novidades do aplicativo
   - Posts: 1 artigo
   - Cor tema: Verde (#4caf50)

#### Estrutura das Páginas de Categoria:
```html
<!-- Header específico da categoria -->
<div class="category-header">
  <h1>[Nome da Categoria]</h1>
  <p>[Descrição da categoria]</p>
</div>

<!-- Lista filtrada de posts -->
<div class="posts-grid">
  <!-- Posts específicos da categoria -->
</div>

<!-- Navegação entre categorias -->
<div class="category-navigation">
  <!-- Links para outras categorias -->
</div>
```

### 📄 Artigos Atuais do Blog

#### 1. **Paghelp.me 2.0.26: Biometria e Links de Pagamento**
- **Slug**: `paghelp-versao-2-0-26-biometria-links-pagamento.html`
- **Data**: 28/09/2024
- **Categorias**: Atualização, Recursos, PIX, Segurança
- **Foco**: Novidades da versão 2.0.26

#### 2. **Os 5 melhores apps para gerenciar chaves PIX**
- **Slug**: `5-melhores-apps-gerenciar-chaves-pix.html`
- **Data**: 27/09/2024
- **Categorias**: Apps, PIX, Comparativo
- **Foco**: Ranking e comparação de aplicativos

#### 3. **Como usar PIX com segurança**
- **Slug**: `como-usar-pix-com-seguranca.html`
- **Data**: 27/09/2024
- **Categorias**: Segurança, PIX, Dicas
- **Foco**: Práticas de segurança

#### 4. **Gerenciar chaves PIX offline**
- **Slug**: `gerenciar-chaves-pix-offline.html`
- **Data**: 25/09/2024
- **Categorias**: PIX, Offline, Privacidade
- **Foco**: Benefícios do funcionamento offline

#### 5. **5 recursos essenciais do Paghelp.me**
- **Slug**: `5-recursos-essenciais-paghelp.html`
- **Data**: 23/09/2024
- **Categorias**: Tutorial, Recursos, Paghelp.me
- **Foco**: Funcionalidades do aplicativo

---

## 🔍 Estratégia de SEO

### 📊 Implementações SEO Atuais

#### 1. **Meta Tags Otimizadas**
```html
<!-- SEO Meta Tags -->
<meta name="description" content="[Descrição específica da página]">
<meta name="keywords" content="[Palavras-chave relevantes]">
<meta name="author" content="Alexandre Sanlim">
<meta name="robots" content="index, follow">
<meta name="language" content="pt-BR">
<meta name="revisit-after" content="1 days">

<!-- Open Graph / Facebook -->
<meta property="og:type" content="[website/blog/article]">
<meta property="og:url" content="[URL específica]">
<meta property="og:title" content="[Título otimizado]">
<meta property="og:description" content="[Descrição para redes sociais]">
<meta property="og:image" content="https://paghelpme.github.io/src/img/metatag.png">

<!-- Twitter Cards -->
<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:title" content="[Título para Twitter]">
<meta property="twitter:description" content="[Descrição para Twitter]">
```

#### 2. **Dados Estruturados (JSON-LD)**

**Para o Blog:**
```json
{
  "@context": "https://schema.org",
  "@type": "Blog",
  "name": "Blog Paghelp.me",
  "description": "Dicas, tutoriais e novidades sobre PIX",
  "url": "https://paghelpme.github.io/blog/",
  "author": {
    "@type": "Person",
    "name": "Alexandre Sanlim"
  },
  "mainEntity": {
    "@type": "ItemList",
    "itemListElement": [/* Lista de posts */]
  }
}
```

**Para Artigos:**
```json
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "[Título do artigo]",
  "description": "[Descrição do artigo]",
  "author": {
    "@type": "Person",
    "name": "Alexandre Sanlim"
  },
  "datePublished": "[Data ISO]",
  "publisher": {
    "@type": "Organization",
    "name": "Paghelp.me"
  }
}
```

#### 3. **Sitemap XML** (`sitemap.xml`)
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <!-- Páginas principais -->
  <url>
    <loc>https://paghelpme.github.io/</loc>
    <lastmod>2024-09-28</lastmod>
    <priority>1.0</priority>
  </url>
  
  <!-- Blog -->
  <url>
    <loc>https://paghelpme.github.io/blog/</loc>
    <lastmod>2024-09-28</lastmod>
    <priority>0.9</priority>
  </url>
  
  <!-- Posts do blog -->
  <!-- Categorias do blog -->
  <!-- Outras páginas -->
</urlset>
```

#### 4. **RSS Feed** (`blog/feed.xml`)
```xml
<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0" xmlns:content="http://purl.org/rss/1.0/modules/content/">
  <channel>
    <title>Blog Paghelp.me - PIX e Pagamentos Digitais</title>
    <description>Dicas, tutoriais e novidades sobre PIX</description>
    <link>https://paghelpme.github.io/blog/</link>
    
    <!-- Items dos posts com conteúdo completo -->
    <item>
      <title>[Título]</title>
      <link>[URL]</link>
      <description>[Descrição]</description>
      <content:encoded><![CDATA[Conteúdo HTML completo]]></content:encoded>
      <pubDate>[Data RFC 2822]</pubDate>
      <guid>[GUID único]</guid>
    </item>
  </channel>
</rss>
```

#### 5. **Robots.txt**
```
User-agent: *
Allow: /
Allow: /blog/
Allow: /blog/posts/
Allow: /blog/categorias/
Allow: /privacy/

Sitemap: https://paghelpme.github.io/sitemap.xml
```

### 🎯 Palavras-chave Principais

#### Primárias:
- "app pix", "aplicativo pix", "chaves pix"
- "pix offline", "gerenciar pix", "pix seguro"
- "paghelp.me", "qr code pix", "cobrança pix"

#### Secundárias:
- "melhores apps pix", "comparativo apps pix"
- "segurança pix", "dicas pix", "tutorial pix"
- "pix brasil", "banco central pix", "pagamento instantâneo"

#### Long-tail:
- "como gerenciar chaves pix offline"
- "melhor aplicativo para chaves pix 2024"
- "app pix que funciona sem internet"
- "como usar pix com segurança"

---

## 🎨 Design System

### 🎨 Paleta de Cores
```css
:root {
  --primary-color: #667eea;      /* Azul principal */
  --secondary-color: #764ba2;    /* Roxo secundário */
  --accent-color: #004c40;       /* Verde escuro (destaque) */
  --text-primary: #2c3e50;       /* Texto principal */
  --text-secondary: #34495e;     /* Texto secundário */
  --text-muted: #7f8c8d;         /* Texto auxiliar */
  --bg-primary: #ffffff;         /* Fundo principal */
  --glass-bg: rgba(102, 126, 234, 0.08);     /* Fundo glass */
  --glass-border: rgba(102, 126, 234, 0.2);  /* Borda glass */
}
```

### 🔧 Componentes Reutilizáveis

#### Glass Morphism Cards:
```css
.glass-card {
  background: var(--glass-bg);
  backdrop-filter: blur(20px);
  border: 1px solid var(--glass-border);
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.08);
  border-radius: 20px;
  transition: all 0.3s ease;
}
```

#### Botões de Ação:
```css
.action-btn {
  background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
  border: none;
  color: white;
  padding: 0.5rem 1.5rem;
  border-radius: 25px;
  transition: all 0.3s ease;
}
```

### 📱 Responsividade

#### Breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 991px
- **Desktop**: > 992px

#### Estratégias:
- Layout flexível com CSS Grid e Flexbox
- Imagens responsivas com `srcset`
- Navegação adaptativa (hamburger menu em mobile)
- Tipografia escalonável

---

## 🚀 Instruções para Agentes

### ✅ Boas Práticas para Edição

#### 1. **Criação de Novos Posts**
```html
<!-- Template básico para novo post -->
<!doctype html>
<html lang="pt-BR">
<head>
  <!-- Meta tags SEO completas -->
  <!-- Dados estruturados JSON-LD -->
  <!-- Estilos consistentes -->
</head>
<body>
  <!-- Navegação padrão -->
  <main>
    <article>
      <!-- Conteúdo do post -->
    </article>
  </main>
  <!-- Footer padrão -->
</body>
</html>
```

#### 2. **Adição de Posts ao Blog Principal**
- Adicionar post no topo da lista em `blog/index.html`
- Atualizar contadores de categoria na sidebar
- Manter ordem cronológica (mais recente primeiro)

#### 3. **Atualização de Arquivos SEO**
Sempre atualizar quando adicionar conteúdo:
- `sitemap.xml`: Adicionar nova URL
- `blog/feed.xml`: Adicionar item no feed RSS
- `robots.txt`: Verificar permissões se necessário

#### 4. **Categorização de Posts**
- Máximo 3-4 categorias por post
- Usar categorias existentes quando possível
- Criar nova categoria apenas se necessário
- Atualizar páginas de categoria correspondentes

### 🛠️ Padrões de Desenvolvimento

#### Nomenclatura de Arquivos:
```
posts/[palavra-chave-principal]-[descricao-breve].html
Exemplo: paghelp-versao-2-0-26-biometria-links-pagamento.html
```

#### Estrutura de Título:
```
Título Principal: Subtítulo Explicativo | Paghelp.me
Exemplo: "Paghelp.me 2.0.26: Biometria e Links de Pagamento chegam ao app PIX"
```

#### Meta Description (150-160 caracteres):
```
"Ação/Benefício + Palavras-chave + CTA/Diferencial"
Exemplo: "Conheça as novidades da versão 2.0.26 do Paghelp.me: autenticação biométrica e links de pagamento PIX."
```

### 🔍 Checklist de Qualidade

#### Para Novos Posts:
- [ ] Meta tags SEO completas
- [ ] Dados estruturados JSON-LD
- [ ] Imagens otimizadas (WebP quando possível)
- [ ] Links internos relevantes
- [ ] CTA para download do app
- [ ] Navegação breadcrumb
- [ ] Data de publicação clara
- [ ] Categorias apropriadas

#### Para Atualizações do Site:
- [ ] Sitemap.xml atualizado
- [ ] Feed RSS atualizado
- [ ] Links de navegação funcionais
- [ ] Responsividade testada
- [ ] Performance otimizada
- [ ] Acessibilidade (alt text, contraste)

### 🎯 Estratégias de Conteúdo

#### Tipos de Post Recomendados:
1. **Tutoriais**: Como fazer X com Paghelp.me
2. **Comparativos**: Paghelp.me vs. outros apps
3. **Novidades**: Updates e recursos novos
4. **Educacionais**: Explicações sobre PIX
5. **Casos de Uso**: Exemplos práticos

#### Palavras-chave por Categoria:
- **Segurança**: "pix seguro", "proteger chaves pix", "golpes pix"
- **Tutoriais**: "como usar", "passo a passo", "tutorial pix"
- **Apps**: "melhor app pix", "aplicativo pix", "comparativo"
- **PIX**: "sistema pix", "banco central", "pagamento instantâneo"

---

## 🔧 Configurações Técnicas

### 🌐 Hosting e Deploy
- **Plataforma**: GitHub Pages
- **Domínio**: paghelpme.github.io
- **Branch**: master (deploy automático)
- **SSL**: Habilitado automaticamente

### 📊 Analytics e Monitoramento
- **Google Search Console**: Configurado
- **Verificação**: google2f3c5e7032b61a80.html
- **Sitemap**: Submetido automaticamente

### 🔒 Segurança
- **HTTPS**: Forçado
- **Headers**: Configurados via GitHub Pages
- **Política de Privacidade**: `/privacy/index.html`

### ⚡ Performance
- **CDN**: Bootstrap, Font Awesome via CDN
- **Otimização**: CSS minificado em produção
- **Imagens**: Comprimidas e otimizadas
- **Caching**: Configurado via GitHub Pages

---

## 🎯 Conclusão

Este site foi desenvolvido com foco em:
- **SEO otimizado** para termos relacionados a PIX
- **Performance** e acessibilidade
- **Manutenibilidade** para agentes de IA
- **Experiência do usuário** profissional
- **Conversão** para downloads do aplicativo

A estrutura modular e bem documentada permite fácil manutenção e expansão do conteúdo, sempre mantendo as melhores práticas de SEO e desenvolvimento web.