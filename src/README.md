# Portfólio – Victor Hugo

> Landing page em HTML/CSS focada em mostrar projetos, processo e canais de contato com clareza.

## 🌟 Destaques

- Hero com CTA direto e destaques rápidos de stack/formação.
- Cases com métricas resumidas (**Login Seguro** e **AjudeAqui**).
- Timeline de processo cobrindo descoberta → UX → dev → handoff.
- Formulário de contato acessível + CTA final reutilizável.

## 🗂 Estrutura do repo

```
portfolio/
├── index.html              # ponto de entrada da landing page
├── style.css               # estilos globais específicos da página
└── src/
    ├── README.md           # este arquivo
    └── assets/
        ├── icons/          # SVGs (seta, botão "let's talk")
        ├── images/         # screenshots e fundos
        └── styles/
            └── global.css  # tokens (cores/tipografia) compartilhados
```

- `index.html`: marcação semântica com blocos reutilizáveis (`section-block`, `project-card`, etc.).
- `style.css`: consome `src/assets/styles/global.css` e define layouts/responsividade.
- `src/assets`: centraliza ícones e imagens chamadas via caminhos relativos (`src/assets/...`).

## ▶️ Como visualizar/editar

1. Abra `index.html` direto no navegador ou sirva a pasta com qualquer servidor estático.
2. Ajuste textos/links na própria `index.html` (as seções estão organizadas com IDs: `hero`, `sobre`, `projetos`, `ajudeaqui`, `processo`, `contact`).
3. Personalize estilos em `style.css`; use `src/assets/styles/global.css` para trocar tokens (cores, fontes, espaçamentos base).
4. Substitua imagens/SVGs dentro de `src/assets/...` e mantenha o mesmo nome para não quebrar os imports.

## 📌 Próximos passos

- Trocar screenshots por capturas reais de cada projeto.
- Ligar o formulário a um serviço de email/automatização (Formspree, Beeceptor, etc.).
- Medir e publicar resultados (métricas, depoimentos) nos cards.

Sugestões e PRs são bem-vindos. 🚀
