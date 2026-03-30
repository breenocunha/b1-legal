# B1 TechFrio — Documentos legais

Site estático com a **Política de Privacidade** e os **Termos de Uso** do aplicativo **B1 TechFrio**, desenvolvido pela B1 Soluções Integradas Ltda.

## Publicação (Netlify)

Site em produção:

| | URL |
|---|-----|
| Página inicial | https://b1-legal.netlify.app/ |
| Política de Privacidade | https://b1-legal.netlify.app/privacy |
| Termos de Uso | https://b1-legal.netlify.app/terms |

**Google Play:** use como URL da política de privacidade:

**https://b1-legal.netlify.app/privacy**

(Os caminhos `/privacy` e `/terms` são definidos em `netlify.toml`.)

## Espelho (GitHub Pages)

| | URL |
|---|-----|
| Página inicial | https://breenocunha.github.io/b1-legal/ |
| Política de Privacidade | https://breenocunha.github.io/b1-legal/privacy.html |
| Termos de Uso | https://breenocunha.github.io/b1-legal/terms.html |

## Conteúdo do repositório

- `index.html` — índice com links para os documentos
- `privacy.html` — política de privacidade (LGPD)
- `terms.html` — termos de uso
- `netlify.toml` — rewrites para `/privacy` e `/terms`
- `.nojekyll` — desativa o Jekyll no GitHub Pages

## Atualizar os textos

Edite os `.html`, faça commit e push. O Netlify e o GitHub Pages passam a servir a nova versão em poucos minutos. Quando alterar o conteúdo jurídico, atualize também a linha **última atualização** no topo de `privacy.html` e `terms.html`.
