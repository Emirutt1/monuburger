# 🍔 MONU BURGER

Página web de una sola página para **MONU BURGER** — *Más que una burger*.

Sitio estático (HTML/CSS/JS, sin dependencias) con:

- **Hero** a pantalla completa con el logo de la marca.
- **Menú real por categorías** — Burger del Mundial (edición limitada), Hamburguesas, Burger del Repar, Combos, Para picar, Bebidas, Postres y Salsas — con opciones Simple / Doble / Triple y fotos.
- **Reels** que corren en loop y abren el Instagram [@_monuburger](https://www.instagram.com/_monuburger/).
- **Sistema de encargue por WhatsApp**: nombre, celular, forma de pago (efectivo o transferencia con alias `Pipo.monu` + aviso de comprobante) y detalle del pedido.
- Optimizada para **celular y PC**.

## ⚙️ Antes de publicar — completar el WhatsApp

En `index.html`, dentro del bloque `CONFIG` (arriba del `<script>`), reemplazá el número:

```js
const CONFIG = {
  whatsapp: "5491100000000", // <== número real de MONU BURGER (formato: 54 9 + área + número)
  ...
};
```

## 🎬 Reels en video (opcional)

Para que se vean los videos reales de los reels (además de las fotos en movimiento),
descargá tus reels de Instagram y ponelos en una carpeta `reels/` como `1.mp4`, `2.mp4`, `3.mp4`, `4.mp4`.
El sitio los detecta y los reproduce en loop automáticamente.

## 🚀 Ver el sitio

Es un sitio estático: abrí `index.html` o publicalo con **GitHub Pages**
(Settings → Pages → Branch: `main` / `root`).
