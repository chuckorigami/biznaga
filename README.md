# biznaga red creativa_ · Landing estática

Este paquete está listo para subirse a **GitHub Pages** o **Netlify**.

## 1) Personaliza
- Reemplaza los textos en `index.html`.
- Coloca tu número de WhatsApp en la constante `WHATSAPP_NUMBER` (sin el signo +).
- Sustituye enlaces del portafolio y correo si hace falta.
- Cambia imágenes dentro de `/assets`.

## 2) GitHub Pages
- Crea un repositorio nuevo (p. ej. `biznaga-site`).
- Sube estos archivos a la rama `main`.
- En `Settings > Pages` elige `Deploy from a branch` y selecciona `main`.
- La URL será `https://TU_USUARIO.github.io/biznaga-site/` o tu dominio personalizado.

## 3) Dominio en Squarespace
- Mantén Squarespace como registrador.
- Crea un CNAME hacia `TU_USUARIO.github.io.` o apunta a Netlify cuando sea el caso.
- Espera propagación DNS.

## 4) Netlify (opcional)
- Arrastra y suelta esta carpeta en https://app.netlify.com/drop o conecta el repo.
- Para dominio, agrega un CNAME desde Squarespace a `NOMBREDELASITIO.netlify.app`.

## 5) Favicon
Se generó `favicon.ico` automáticamente desde tu logo.

— Hecho para GitHub Pages/Netlify, sin dependencias ni build.