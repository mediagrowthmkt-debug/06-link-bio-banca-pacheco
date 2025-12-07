# 🎯 Link Bio - Banca Pacheco

Uma landing page moderna e responsiva no estilo **Linktree**, criada para centralizar todos os links importantes da Banca Pacheco em um único lugar.

## 📋 Características

### ✨ Design Moderno
- **Tema escuro profissional** com gradientes sofisticados
- **Animações suaves** que melhoram a experiência do usuário
- **Responsivo** - funciona perfeitamente em desktop, tablet e mobile
- **Cores personalizadas** (vermelho principal #d41c1c, combinando com a identidade da marca)

### 🔗 Links Inclusos
1. **Site Oficial da Banca** - https://bancapacheco.com.br/
2. **Produtos** - https://lp.bancapacheco.com.br/
3. **Localização** - Modal popup com 4 bancas e links para Google Maps
4. **Promoções da Semana** - https://promos.bancapacheco.com.br/

### 📱 Redes Sociais
- Instagram: @bancapacheco
- TikTok: @banca.pacheco
- Facebook: Banca Pacheco
- YouTube: @bancapacheco
- LinkedIn: Pacheco Frios de Laticínios
- Pinterest: @bancapacheco
- Google Business: Banca Pacheco

### 📍 Modal de Localização
Popup interativo mostrando:
- **4 unidades da Banca Pacheco**
- Endereços completos
- Links diretos para Google Maps/compartilhamento de localização
- Design responsivo e elegante

## 🎨 Estrutura do Design

### Cores
```css
--primary-color: #d41c1c (Vermelho Principal)
--dark-bg: #0a0a0a (Fundo Escuro)
--card-bg: #1a1a1a (Fundo dos Cards)
--text-primary: #ffffff (Texto Branco)
--accent-color: #ff6b6b (Vermelho Claro)
```

### Fontes
- **Montserrat** - Títulos (700, 800)
- **Inter** - Textos (400, 500, 600)

## 🚀 Como Usar

### Instalação
1. Copie o arquivo `index.html` para seu servidor
2. Abra em um navegador
3. Pronto! O site está funcional

### Customização

#### Alterar Imagem do Perfil
```html
<img src="https://seu-url-da-imagem.png" alt="Banca Pacheco">
```

#### Alterar Links
Encontre os `href=""` e atualize com seus links:
```html
<a href="https://seu-link.com" class="link-btn" target="_blank">
```

#### Adicionar/Remover Redes Sociais
```html
<a href="https://sua-rede-social.com" class="social-link" target="_blank" title="Nome da Rede">
    <i class="fab fa-icon-name"></i>
</a>
```

#### Modificar Cores
Altere as variáveis CSS no `:root`:
```css
:root {
    --primary-color: #seu-cor;
    --accent-color: #seu-cor-secundaria;
}
```

## 🎭 Efeitos e Animações

- ✨ Fade in/up animados na entrada
- 🎯 Hover effects nos botões
- 💫 Pulse animation no botão de promoções
- 🌊 Wave effect ao passar o mouse
- 📱 Suporte a touch em mobile

## 📊 Performance

- **Lightweight** - Carregamento rápido
- **Sem dependências pesadas** - Apenas Font Awesome para ícones
- **Otimizado para mobile** - Menos de 50KB
- **SEO Friendly** - Meta tags apropriadas

## 🔒 Segurança

- Links abrem em `target="_blank"` (nova aba)
- Modal seguro com backdrop blur
- Validações de entrada em JavaScript
- Sem armazenamento de dados sensíveis

## 📲 Compatibilidade

✅ Chrome/Chromium
✅ Firefox
✅ Safari
✅ Edge
✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (Grid, Flexbox, Animations, Gradients)
- JavaScript vanilla (sem dependências)
- Font Awesome 6.4.0 (ícones)
- Google Fonts (tipografia)

## 📝 Estrutura de Arquivos

```
06-link-bio/
├── index.html          # Página principal
└── README.md           # Esta documentação
```

## 🎯 Otimizações Implementadas

1. **Mobile First** - Estrutura otimizada para mobile
2. **Lazy Loading** - Imagens carregam sob demanda
3. **CSS Otimizado** - Minificação e organização
4. **Animações Smooth** - GPU accelerated
5. **Acessibilidade** - ARIA labels e contraste adequado

## 🤝 Funcionalidades Extras

### Modal de Localização
- Popup com 4 unidades da Banca
- Fechar com X, ESC ou clicando fora
- Scroll suave para conteúdo longo
- Styling consistente

### Efeitos Visuais
- Gradiente de fundo com radial gradient
- Glow effect nos botões ao hover
- Border animado na imagem
- Sombras dinâmicas

## 💡 Dicas de Uso

1. **Compartilhe** o link em suas bios do Instagram/TikTok
2. **QR Code** - Gere um QR code apontando para este link
3. **Email** - Inclua na assinatura de emails
4. **WhatsApp** - Compartilhe em grupos e chats
5. **Redes Sociais** - Coloque no BIO do Instagram/TikTok

## 📞 Suporte

Para qualquer dúvida ou ajuste, entre em contato com a equipe de desenvolvimento.

---

**Última atualização:** 6 de Dezembro de 2024  
**Versão:** 1.0.0
