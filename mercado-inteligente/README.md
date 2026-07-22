# 🛒 Mercado Inteligente

App gratuita para automatizar tu mercado semanal/mensual. **Funciona sin internet**, no necesita cuenta ni pagar nada, y tus datos se quedan solo en tu dispositivo.

## ✨ Qué hace

- **Lista de compras** con checkboxes para marcar lo que ya compraste.
- **Comparador de precios** entre supermercados: te dice dónde está más barato cada producto y cómo repartir la compra para pagar el mínimo.
- **Despensa**: guarda lo que compraste. Cuando algo *se acaba*, lo marcas y vuelve solo a la lista de la próxima semana.
- **Historial** de todas tus compras con fechas, tiendas y totales.
- **Gráficos** de gasto: en qué productos gastas más y cuáles compras con más frecuencia (los que debes reponer antes).
- **Exportar** a Excel (CSV) y PDF.
- **Instalable** como app en Android e iPhone (PWA).

Precios de referencia y supermercados vienen precargados (España, €) pero son **totalmente editables** desde la app (Ajustes y pestaña Precios). También puedes cambiar la moneda.

## 🚀 Publicar gratis en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `mercado-inteligente`).
2. Sube estos archivos al repo (`index.html`, `manifest.webmanifest`, `sw.js` y los `.png`).
3. En GitHub: **Settings → Pages → Source: `main` / carpeta `/root`** y guarda.
4. En 1–2 minutos tendrás una URL tipo `https://TU-USUARIO.github.io/mercado-inteligente/`.
5. Comparte esa URL: cualquiera puede usarla e instalarla, sin pagar nada.

## 📲 Instalar en el móvil

- **Android (Chrome):** abre la URL → botón **📲 Instalar** o menú ⋮ → "Instalar app".
- **iPhone (Safari):** abre la URL → botón **Compartir** ↑ → **"Añadir a pantalla de inicio"**.

Una vez instalada se abre a pantalla completa como una app normal y funciona sin conexión.

## 🔒 Privacidad

Todo se guarda con `localStorage` en tu propio navegador. Nada se envía a ningún servidor. Puedes descargar una copia de seguridad (JSON) desde **Ajustes → Datos**.

## 🛠️ Uso local (opcional)

Ábrelo con doble clic (`index.html`) o sírvelo para probar la PWA:

```bash
python3 -m http.server 8080
# luego abre http://localhost:8080
```

---
Hecho para ser libre y gratis. Copia, modifica y comparte.
