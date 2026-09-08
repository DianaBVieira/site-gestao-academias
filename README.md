# Gestão para Academias — landing de vendas

Página de vendas do serviço da **Utopia Desenvolvimentos**: site institucional
personalizado + painel de gestão (área do aluno e área administrativa) para
academias e studios de treino.

Estática (um `index.html`, sem build). Formulário monta um link `wa.me` com os
campos e abre o WhatsApp — sem backend/serviço externo.

## Ver localmente
```bash
npx serve .
```

## Conteúdo
- Oferta: R$ 259/mês, promoção de lançamento **R$ 199/mês no 1º ano**
- Demo pública: https://dianabvieira.github.io/Site_Academia_Modelo01/ (site) e `/portal/` (painel)
- Cliente em uso: Academia Brothers (Vila Velha–ES)
- Prints em `assets/` recortados da demo (marca fictícia "Vértice")

## Deploy
GitHub Pages (repo público) → `academias.utopiadesenvolvimentos.com.br`
(CNAME já no repo). No Registro.br: `academias CNAME dianabvieira.github.io`.
Também roda em Vercel/Cloudflare Pages/Netlify sem build.

## SEO
title/description/keywords (software para academia, gestão de alunos, controle de
mensalidades…), Open Graph/Twitter, JSON-LD (Service + Offer + FAQPage),
robots.txt, sitemap.xml.
