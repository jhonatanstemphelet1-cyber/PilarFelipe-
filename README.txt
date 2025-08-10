# Pilar & Felipe – Papelería
Sitio estático listo para subir (GitHub Pages / Netlify).

## Cómo publicar en Netlify
1. Creá cuenta en https://app.netlify.com/ o iniciá sesión.
2. Click **Add new site → Deploy manually**.
3. **Descomprimí** este ZIP y **arrastrá la carpeta** (con `index.html`, `logo.svg`, `README.txt`) a la zona de carga.
4. Netlify te dará una **URL pública** al instante. En *Site settings → Domain management* podés renombrar el subdominio.

## Cómo publicar en GitHub Pages
1. Creá un repositorio nuevo y subí **estos tres archivos** a la rama `main`.
2. *Settings → Pages* → **Deploy from branch**, `main` / **root** → Save.
3. En ~1 minuto tendrás la URL `https://TU-USUARIO.github.io/NOMBRE-REPO/`.

## Editar productos y categorías
- Están dentro de `index.html` en el `<script type="text/babel">` (arrays `sampleProducts` y `categories`).

## Pagos reales (a implementar)
- **Mercado Pago**: botón de checkout con `preference_id`.
- **eBROU**: link de pago/transferencia prellenado.
- **OCA/VISA/MASTER**: checkout de tu procesador.
- **Abitab/Redpagos**: emisión de boleta vía proveedor.

> Esta versión **simula** la confirmación (alert) y vacía el carrito; no procesa cobros reales.
