# Victor Hugo Roth Romaniuk - Portfolio

Portfolio pessoal de Victor Hugo Roth Romaniuk, especialista em Backend & Automação.

## Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Estilização via CDN
- **Google Fonts** - Hanken Grotesk & JetBrains Mono
- **Material Symbols** - Ícones

## Estrutura do Projeto

```
portfloio/
├── index.html          # Página principal do portfolio
├── README.md           # Este arquivo
└── .github/
    └── workflows/
        └── deploy.yml  # Workflow para GitHub Pages
```

## Design System

O design segue o sistema "Cyber-Logic Portfolio" com:
- **Cores**: Dark mode com acentos neon (violeta, azul)
- **Tipografia**: Hanken Grotesk (display) + JetBrains Mono (código)
- **Estética**: IDE/terminal com elementos técnicos

## Responsividade

O site é totalmente responsivo:
- **Desktop**: Layout multi-coluna com grid de 1200px
- **Mobile**: Layout single-column com margens de 16px
- **Tablet**: Adaptação automática via breakpoints do Tailwind

## Personalização

### Alterar Cores
Edite as variáveis de cor no `tailwind.config` dentro do `index.html`

### Alterar Conteúdo
- **Hero section**: Linhas 171-197
- **Experiência**: Linhas 199-270
- **Competências**: Linhas 271-331
- **Footer**: Linhas 333-348
