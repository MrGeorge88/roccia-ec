# Roccia.ec

Heladería italo-argentina artesanal en Cumbayá, Quito.
Sitio principal de marca · roccia.ec

## Stack

- HTML estático (sin framework)
- CSS vanilla con variables de marca
- JavaScript vanilla para interactividad mínima
- Schema.org `IceCreamShop` JSON-LD

## Estructura

- `index.html` — Home principal
- `mayoristas.html` — Landing B2B
- `assets/` — Imágenes, fuentes, recursos estáticos

## Deploy

Auto-deploy desde GitHub a Vercel en cada push a main.
Production: https://roccia.ec

## Dominios

`roccia.ec` es el dominio canónico y único sitio. Los dominios secundarios
redirigen con 301 a `roccia.ec` (configurado en `vercel.json`):

- heladosroccia.com → roccia.ec (301)
- momentosroccia.com → roccia.ec (301)
- roccia.com.ec → roccia.ec (301)

`rocciaheladeria.com` NO redirige: se mantiene activo para el correo
`hola@rocciaheladeria.com`.

## Brand

Manual de marca: ver /docs/brand-manual.pdf en repo privado.
Voz: gentil, cercana, evocativa. Tú-form ecuatoriano.
Paleta: cream #faf4e0, brownDark #50351c, brownMid #846f59, brownNeutral #66523a.

© Roccia · LA2 S.A.S. · Cumbayá · 2026
