# Portfólio

## Estrutura de Pastas

```
portfolio/
├── index.html        ← Página principal (hero + todas as seções)
├── css/
│   └── style.css     ← Todo o estilo (cores, fontes, layout)
├── js/
│   └── main.js       ← Comportamentos (cursor, scroll, formulário)
└── assets/           ← Coloque aqui suas fotos e imagens de projetos
```

---

## Como Personalizar

### 1. Cores — `css/style.css` (topo do arquivo)

```css
:root {
  --bg:        #080c12;   /* Fundo principal */
  --bg-panel:  #0e1420;   /* Fundo dos cards */
  --text:      #e8e0d0;   /* Texto principal */
  --text-muted:#7a8090;   /* Texto secundário */
  --accent:    #00f5c4;   /* Cor de destaque (botões, borda ativa) */
}
```

### 2. Sua Foto — `index.html`

Substitua o bloco `.image-placeholder` por:
```html
<img src="assets/sua-foto.jpg" alt="Seu Nome" />
```

### 3. Textos — `index.html`

Busque pelos comentários e substitua:
- `Seu Nome` → seu nome real
- `Desenvolvedor Full Stack` → sua área
- Os parágrafos de bio e about
- As tags de skills
- Os números dos stats
- Os cards de projeto com suas infos reais
- E-mail, LinkedIn, GitHub

### 4. Imagens dos Projetos

Substitua o texto dentro de `.project-thumb` por uma imagem:
```html
<div class="project-thumb">
  <img src="assets/proj1.png" alt="Nome do Projeto" style="width:100%;height:100%;object-fit:cover;" />
</div>
```

---

## Funcionalidades Já Incluídas

- ✅ Grid hero (imagem + info) responsivo
- ✅ Scroll suave entre seções
- ✅ Cursor personalizado
- ✅ Animações ao entrar na viewport
- ✅ Hover nos botões e cards
- ✅ Formulário de contato (front-end only)
- ✅ Design responsivo para mobile

---

## Próximos Passos (Backend)

Quando quiser adicionar backend:
- Formulário de contato real (envio de e-mail via SMTP/SendGrid)
- Painel admin para atualizar projetos sem editar HTML
- Integração com GitHub API para puxar repositórios automaticamente
