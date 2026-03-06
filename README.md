# Bsociety Brasil

Site institucional da Bsociety — Agência de Inteligência Corporativa.

## Stack

- HTML/CSS/JS puro (zero dependências)
- Hospedagem: Vercel (static)
- CDN: Vercel Edge Network

## Deploy

Conectado à Vercel via GitHub. Cada push na `main` faz deploy automático.

## Estrutura

```
├── index.html          # Home
├── about-us.html       # Sobre
├── methodology.html    # Metodologia HUMINT
├── services.html       # 9 Serviços
├── our-ethics.html     # Código de Ética
├── case-studies.html   # Casos de Referência
├── contact.html        # Contato
├── careers.html        # Carreiras
├── blog.html           # Blog (listing)
├── blog/               # 11 artigos
├── sitemap.xml         # Sitemap para Google
├── robots.txt          # Diretivas de crawling
├── vercel.json         # Config Vercel (rewrites, headers)
└── .gitignore
```

## Domínio

Configurar `bsociety.com.br` no Registro.br apontando para Vercel.
