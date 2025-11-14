# Portfólio Victor Hugo

Landing page em HTML + CSS puro para apresentar projetos, processos e canais de contato. O layout usa blocos largos, gradientes e tipografia serifada/pantográfica para reforçar a identidade visual e manter o foco no storytelling.

## Destaques

- **Hero direto ao ponto:** mensagem principal, links para redes e CTA “Let’s Talk”.
- **Projetos em evidência:** cards descrevem contexto, stack e links para repositórios.
- **Sessão de serviços/processos:** descreve como conduzo discovery → handoff.
- **Formulário acessível:** campos essenciais, microcópia em PT-BR e botão com ícone.
- **CTA final:** reforça disponibilidade para freelas e repete navegação.

## Estrutura atual

```
portfolio/
├── index.html              # página principal na raiz
├── style.css               # estilos da landing (importa global.css)
└── src/
    └── assets/
        ├── icons/          # SVGs usados nos CTAs e navegação
        ├── images/         # screenshots e fundos
        └── styles/
            └── global.css  # tokens, variáveis e resets compartilhados
```

- `index.html`: marcação semântica organizada em seções (`section-block`, `project-card`, etc.).
- `style.css`: regras principais da página e import do `src/assets/styles/global.css` para variáveis globais.
- `src/assets`: concentra ícones, imagens e folhas de estilo utilitárias.

## Tecnologias

- HTML5 semântico
- CSS (Flexbox, Grid, clamp, custom properties)
- SVG/PNG estáticos

## Próximos passos sugeridos

- Incluir imagens reais dos projetos e GIFs curtos.
- Escrever estudos de caso completos e métricas de impacto.
- Integrar o formulário com um backend (Formspree, Resend, etc.).

Feedbacks e PRs são sempre bem-vindos! 🚀
