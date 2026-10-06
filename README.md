# Mi Carnet

PWA para llevar el carnet en el teléfono: se instala como app, funciona sin conexión y permite descargar el PDF original.

El PDF **no va en el repositorio**: se carga desde el teléfono y queda guardado solo en ese dispositivo.

## Publicar en GitHub Pages
1. Creá un repositorio y subí estos archivos: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`.
2. En el repo: **Settings → Pages → Source: Deploy from a branch → main / (root)** → Save.
3. Esperá un minuto y abrí `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Instalar en el teléfono
1. Abrí la URL en Chrome (Android).
2. Tocá **Instalar** en la app, o menú ⋮ → **Agregar a pantalla principal / Instalar app**.
3. Abrí la app, tocá **Elegir PDF** y seleccioná tu carnet.

## Uso
- Tocá el carnet o **Mostrar en pantalla completa** para verlo grande y en horizontal (la pantalla no se apaga mientras está abierto).
- **Descargar PDF** baja el archivo original.
- Si actualizás `index.html` o `sw.js`, cambiá `mi-carnet-v1` por `v2` en `sw.js` para que los teléfonos tomen la versión nueva.
