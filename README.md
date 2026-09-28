# Lave Mais Tapetes

Site institucional da **Lavanderia Lavemais Tapetes** (Taubaté - SP).
Site estático (HTML + CSS + JS puro), sem build — pronto para publicar no Cloudflare Pages.

## Estrutura

```
index.html        # página completa
assets/           # logos, fotos (WebP), vídeo e poster do vídeo
_headers          # cache dos arquivos de mídia no Cloudflare
```

## Publicar no Cloudflare Pages

1. No painel do Cloudflare: **Workers & Pages → Create → Pages → Connect to Git**.
2. Selecione este repositório.
3. Configurações de build:
   - **Framework preset:** None
   - **Build command:** (deixe vazio)
   - **Build output directory:** `/`
4. **Save and Deploy**.

## Editar

- Textos, cores e seções: `index.html`
- Trocar fotos/vídeo: substitua os arquivos em `assets/` mantendo os mesmos nomes.

## Contato configurado no site

WhatsApp: (12) 99773-3067 — Endereço: R. Amadeu Orestes Matera, 56 - Independência, Taubaté - SP

Desenvolvido por [Three Core Soluções](https://www.threecoresolucoes.com.br)
