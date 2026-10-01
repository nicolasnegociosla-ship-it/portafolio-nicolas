# Sushi adonde el Oso — menú web

Sitio estático (HTML + `menu.json` + imágenes). Sin build ni backend.

## Editar el menú
Todo está en `menu.json`: precios, descripciones, horarios (`days`, domingo = índice 0), WhatsApp (`wa`), aviso (`notice`).
Fotos nuevas: súbelas a `img/` y cambia el campo `img` del producto.

## Probar local
    cd sushi-oso && python3 -m http.server 8000

## Para salir a producción (checklist)
- [ ] Comprar dominio en nic.cl (ej. sushiadondeeloso.cl) y apuntar DNS al hosting
- [ ] Hosting: GitHub Pages / Netlify / Cloudflare Pages (gratis) con carpeta `sushi-oso/`
- [ ] Fotos reales de cada producto (hoy se reutilizan 9 fotos genéricas)
- [ ] Confirmar WhatsApp, dirección y horarios reales
- [ ] Agregar `og:image` con URL absoluta y `og:url` cuando exista el dominio
- [ ] Decidir: ¿delivery? hoy es solo retiro en local
- [ ] Nikkei: se quitó el producto de prueba; agregar la carta real
