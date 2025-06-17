# Landing Page - Estação dos Doces

> Landing page moderna e responsiva para pequena loja de doces

[![Status](https://img.shields.io/badge/Status-Finalizado-success)](https://github.com/seu-usuario/boutique-elegance-landing)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue)](https://github.com/seu-usuario/boutique-elegance-landing/releases)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Sobre

A Landing Page da Estação dos Doces é uma solução web moderna desenvolvida para apresentar produtos e serviços de uma pequena loja de doces. O projeto foca na experiência do usuário, design responsivo e conversão de visitantes em clientes potenciais.

## Funcionalidades

### 🎨 Design Moderno
- Interface limpa e elegante
- Paleta de cores harmoniosa
- Tipografia profissional
- Animações suaves e interativas

### 📱 Responsividade Total
- Adaptação automática para desktop, tablet e mobile
- Breakpoints otimizados para diferentes dispositivos
- Navegação touch-friendly
- Performance otimizada para carregamento rápido

### 🛍️ Showcase de Produtos
- Galeria interativa de produtos em destaque
- Carrossel de imagens com transições suaves
- Categorização visual de produtos
- Call-to-actions estratégicamente posicionados

### 📧 Captura de Leads
- Formulário de contato integrado
- Newsletter com validação em tempo real
- Integração com redes sociais
- Botões de compartilhamento

## Tecnologias

### Frontend
- **HTML5** - Estrutura semântica moderna
- **CSS3** - Estilização avançada com Flexbox/Grid
- **JavaScript ES6** - Interatividade e animações

### Recursos Utilizados
- **CSS Variables** - Sistema de cores consistente
- **CSS Animations** - Transições e efeitos visuais
- **Intersection Observer** - Animações on-scroll
- **Local Storage** - Persistência de preferências do usuário

### Ferramentas
- **Font Awesome** - Ícones vetoriais
- **Google Fonts** - Tipografia personalizada
- **CSS Grid & Flexbox** - Layout responsivo

## Demonstração

🌐 **[Ver Demo ao Vivo](https://seu-usuario.github.io/boutique-elegance-landing)**

### Screenshots

| Desktop | Mobile | Tablet |
|---------|--------|--------|
| ![Desktop](assets/screenshots/desktop.png) | ![Mobile](assets/screenshots/mobile.png) | ![Tablet](assets/screenshots/tablet.png) |

## Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/boutique-elegance-landing.git
   cd boutique-elegance-landing
   ```

2. **Abra no navegador**
   ```bash
   # Método 1: Abrir diretamente
   open index.html
   
   # Método 2: Servidor local (recomendado)
   python -m http.server 8000
   # ou
   npx serve .
   ```

3. **Acessar a aplicação**
   ```
   http://localhost:8000
   ```

## Estrutura do Projeto

```
boutique-elegance-landing/
├── index.html              # Página principal
├── assets/
│   ├── css/
│   │   ├── style.css       # Estilos principais
│   │   ├── responsive.css  # Media queries
│   │   └── animations.css  # Animações CSS
│   ├── js/
│   │   ├── main.js         # JavaScript principal
│   │   ├── animations.js   # Controle de animações
│   │   └── form.js         # Validação de formulários
│   ├── images/
│   │   ├── products/       # Imagens dos produtos
│   │   ├── gallery/        # Galeria de fotos
│   │   └── icons/          # Ícones personalizados
│   └── fonts/              # Fontes customizadas
├── screenshots/            # Capturas de tela
└── README.md
```

## Seções da Landing Page

```
┌─────────────────────────────────────┐
│            Hero Section             │
│     (Logo + Chamada Principal)      │
├─────────────────────────────────────┤
│          Sobre a Loja               │
│    (História + Valores)             │
├─────────────────────────────────────┤
│        Produtos Destaque            │
│     (Galeria Interativa)            │
├─────────────────────────────────────┤
│         Depoimentos                 │
│    (Social Proof)                   │
├─────────────────────────────────────┤
│        Localização                  │
│   (Mapa + Informações)              │
├─────────────────────────────────────┤
│         Contato                     │
│  (Formulário + Newsletter)          │
└─────────────────────────────────────┘
```

## Customização

### Cores
```css
:root {
  --primary-color: #d4af37;      /* Dourado elegante */
  --secondary-color: #2c2c2c;    /* Cinza escuro */
  --accent-color: #f8f8f8;       /* Branco off */
  --text-color: #333333;         /* Texto principal */
}
```

### Tipografia
```css
/* Fontes utilizadas */
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;600&display=swap');

--font-heading: 'Playfair Display', serif;
--font-body: 'Poppins', sans-serif;
```

## Performance

### Métricas de Performance
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **Time to Interactive**: < 3s

### Otimizações Implementadas
- Compressão de imagens (WebP quando suportado)
- Minificação de CSS e JavaScript
- Lazy loading para imagens
- Critical CSS inline
- Preload de recursos essenciais

## SEO

### Otimizações Implementadas
- Meta tags otimizadas
- Open Graph para redes sociais
- Schema markup para negócios locais
- URLs semânticas
- Alt text em todas as imagens
- Sitemap XML

## Roadmap

- [x] **v1.0** - Landing page base com design responsivo
- [ ] **v1.1** - Integração com Google Analytics
- [ ] **v1.2** - Chat bot para atendimento
- [ ] **v1.3** - Sistema de agendamento online
- [ ] **v2.0** - E-commerce integrado

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

### Diretrizes de Desenvolvimento

- Mantenha o código limpo e comentado
- Teste a responsividade em diferentes dispositivos
- Otimize imagens antes de adicionar
- Valide HTML e CSS
- Teste a performance regularmente

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## Contato

Para dúvidas ou sugestões sobre o projeto:

- **Email**: [g.moreno.souza05@gmail.com](mailto:g.moreno.souza05@gmail.com)
- **LinkedIn**: [Gustavo Moreno Souza](https://www.linkedin.com/in/seu-perfil/)
- **Portfolio**: [https://gustavomoreno.vercel.app](https://gustavomoreno.vercel.app)

---

<div align="center">
  ⭐ Se este projeto foi útil, considere dar uma estrela no GitHub!
  <br><br>
  Desenvolvido com ❤️ por [Seu Nome]
</div>
