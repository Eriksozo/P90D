# No eres demasiado intensa — Landing (PAUSA-90)

Sitio estático bilingüe (ES / PT) listo para Cloudflare Pages.

## Estructura
- `index.html` — versión en español (principal)
- `pt/index.html` — versión en português
- `assets/` — imágenes y mockups

## Publicar en Cloudflare Pages
1. Sube esta carpeta a un repositorio de GitHub.
2. En Cloudflare → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Elige el repo. Build settings:
   - **Framework preset:** None
   - **Build command:** *(vacío)*
   - **Build output directory:** `/`
4. Deploy. Tu sitio queda en `https://<proyecto>.pages.dev`.
5. (Opcional) Agrega tu dominio propio en **Custom domains**.

## Ya configurado
- Link de pago Hotmart en todos los CTA: `pay.hotmart.com/M106317637U`
- Meta Pixel: `1323954313203113`
- Tracking UTM + `sck` de Hotmart (aparece en el informe de ventas)

## Cómo trackear el origen de la venta
Apunta tus anuncios al sitio con UTMs, por ejemplo:
```
https://tudominio.com/?utm_source=facebook&utm_medium=cpc&utm_campaign=pausa90&utm_content=creativo1
```
El sitio reenvía esas UTMs al checkout y arma el parámetro `sck` que aparece en el informe de ventas de Hotmart.
