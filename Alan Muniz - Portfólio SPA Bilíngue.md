# Alan Muniz - Portfólio SPA Bilíngue

Um portfólio moderno, responsivo e bilíngue (PT-BR/EN-US) desenvolvido com HTML, CSS e JavaScript vanilla.
## 📄 Informações Atualizadas

Este portfólio foi personalizado com as informações de **Alan Brito Muniz**, Engenheiro de Dados com experiência em:
- Engenharia de Dados e Big Data
- Pipelines ETL/ELT com Python e Apache Spark
- Power BI e Analytics
- AWS (S3, Glue, EMR, RedShift)
- Gestão de Projetos e Metodologias Ágeis

## Como Personalizar

### 1. Adicionar suas Fotos

**Passo a passo:**

1. **Crie uma pasta chamada `images`** na raiz do seu repositório (mesmo nível que `index.html` e `style.css`)

```
seu-repositorio/
├── index.html
├── style.css
├── README.md
└── images/          ← Crie esta pasta
    └── perfil.jpg   ← Coloque sua foto aqui
```

2. **Coloque sua foto dentro da pasta `images`**
   - Renomeie sua foto como `perfil.jpg` (ou `.png`, `.webp`)
   - Recomendado: foto quadrada (ex: 500x500px) ou circular
   - Tamanho ideal: entre 200KB e 500KB

3. **Pronto!** A foto aparecerá automaticamente no seu portfólio

### 2️⃣ Personalizar o Nome e Informações

Abra o arquivo `index.html` e procure por:

```html
<h1 class="profile-name">Alan Muniz</h1>
```

Substitua `Alan Muniz` pelo seu nome.

### 3️⃣ Atualizar Email e Links Sociais

Procure pela seção de **Contato** e atualize:

```html
<a href="mailto:alan.abm.ti@gmail.com">alan.abm.ti@gmail.com</a>
```

E os links do LinkedIn e GitHub:

```html
<a href="https://www.linkedin.com/in/seu-usuario" target="_blank">
<a href="https://github.com/seu-usuario" target="_blank">
```

### 4️⃣ Adicionar suas Experiências

Procure pela seção `<!-- Experience Item -->` e siga o padrão:

```html
<div class="timeline-item" data-aos="timeline-reveal">
  <div class="timeline-dot"></div>
  <div class="timeline-content">
    <div class="timeline-header">
      <h3 class="exp-title" data-pt="Seu Cargo" data-en="Your Position"></h3>
      <span class="exp-period" data-pt="2024 – Atual" data-en="2024 – Present"></span>
    </div>
    
    <h4 class="exp-company">Sua Empresa</h4>
    
    <p class="exp-description" data-pt="Descrição em português" data-en="Description in English"></p>
    
    <div class="tech-tags">
      <span class="tech-tag">Tecnologia 1</span>
      <span class="tech-tag">Tecnologia 2</span>
    </div>
  </div>
</div>
```

### 5️⃣ Adicionar seus Projetos

Procure pela seção `<!-- Projects Section -->` e adicione:

```html
<div class="project-card">
  <h3 data-pt="Nome do Projeto" data-en="Project Name"></h3>
  <p data-pt="Descrição em português" data-en="Description in English"></p>
</div>
```

### 6️⃣ Adicionar sua Educação/Graduação

Procure pela seção `<!-- Education Section -->` e siga o padrão:

```html
<div class="education-card">
  <div class="edu-image">
    <img src="images/edu-1.png" alt="Seu Diploma">
  </div>
  <div class="edu-info">
    <h3 class="edu-title" data-pt="Nome do Curso" data-en="Course Name"></h3>
    <p class="edu-institution" data-pt="Instituição" data-en="Institution"></p>
    <p class="edu-period" data-pt="Conclusão: Ano" data-en="Graduation: Year"></p>
  </div>
</div>
```

**Importante:** Coloque as imagens dos diplomas na pasta `images/` com nomes como `edu-1.png`, `edu-2.png`, etc.

### 7️⃣ Adicionar suas Certificações

Procure pela seção `<!-- Certifications Section -->` e siga o padrão:

```html
<div class="certification-card">
  <div class="cert-image">
    <img src="images/cert-1.png" alt="Seu Certificado">
  </div>
  <div class="cert-info">
    <h3 class="cert-title" data-pt="Nome da Certificação" data-en="Certification Name"></h3>
    <p class="cert-issuer" data-pt="Emitido por: Instituição" data-en="Issued by: Institution"></p>
    <p class="cert-date" data-pt="Data: Mês Ano" data-en="Date: Month Year"></p>
  </div>
</div>
```

**Importante:** Coloque as imagens dos certificados na pasta `images/` com nomes como `cert-1.png`, `cert-2.png`, etc.

## 🌐 Fazer Deploy no GitHub Pages

1. **Crie um repositório no GitHub** (ex: `portfolio`)
2. **Faça upload dos arquivos** para o repositório
3. **Ative GitHub Pages:**
   - Vá em Settings → Pages
   - Selecione "Deploy from a branch"
   - Escolha "main" como branch
   - Clique em Save

4. **Seu portfólio estará em:** `https://seu-usuario.github.io/portfolio`

## 🎨 Personalizar Cores

Abra `style.css` e procure por cores azuis (`#3b82f6`, `#60a5fa`). Você pode substituir por suas cores preferidas:

```css
/* Cor principal azul */
#3b82f6  /* Azul mais escuro */
#60a5fa  /* Azul mais claro */
```

Algumas alternativas:
- **Verde**: `#10b981` e `#34d399`
- **Roxo**: `#a855f7` e `#d8b4fe`
- **Vermelho**: `#ef4444` e `#f87171`

## ✨ Funcionalidades

✅ Bilíngue (PT-BR / EN-US)  
✅ Timeline animada nas experiências  
✅ Seção de Educação com imagens de diplomas  
✅ Seção de Certificações com imagens  
✅ Estatísticas com links para seções  
✅ Contato com WhatsApp e Email  
✅ Navegação suave  
✅ Design responsivo (mobile, tablet, desktop)  
✅ Sem dependências externas  
✅ Pronto para GitHub Pages  

## 📝 Estrutura de Arquivos

```
portfolio/
├── index.html          # Estrutura HTML + JavaScript
├── style.css           # Estilos e animações
├── README.md           # Este arquivo
└── images/
    ├── perfil.jpeg     # Sua foto de perfil
    ├── edu-1.png       # Diploma Graduação
    ├── edu-2.png       # Diploma Pós-graduação
    ├── cert-1.png      # Certificação 1
    ├── cert-2.png      # Certificação 2
    ├── cert-3.png      # Certificação 3
    ├── cert-4.png      # Certificação 4
    ├── cert-5.png      # Certificação 5
    └── cert-6.png      # Certificação 6
```

## 🔧 Dicas Extras

- **Para mudar o idioma padrão**: No `index.html`, procure por `let currentLanguage = localStorage.getItem('portfolio-language') || 'pt';` e mude `'pt'` para `'en'`
- **Para adicionar mais seções**: Copie uma seção existente e adapte o HTML
- **Para mudar a fonte**: No `index.html`, procure por `<link href="https://fonts.googleapis.com/...">` e escolha outras fontes do Google Fonts

## 📞 Suporte

Se tiver dúvidas, consulte a documentação do GitHub Pages: https://docs.github.com/en/pages

---

**Desenvolvido com ❤️ para seu portfólio profissional**
