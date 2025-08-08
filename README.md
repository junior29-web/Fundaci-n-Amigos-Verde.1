# Fundación Amigos Verde por Colombia — Sitio Web

Versión lista para repositorio (GitHub) y despliegue en Netlify.

## Estructura
```
.
├─ index.html
├─ assets/
│  └─ img/
│     ├─ logo.png
│     ├─ banner.jpg
│     ├─ quienes.jpg
│     ├─ mision.jpg
│     ├─ vidasverdes.jpg
│     ├─ pazliderazgo.jpg
│     └─ comedores.jpg
├─ netlify.toml
└─ .gitignore
```

## Despliegue en GitHub Pages (opcional)
1. Crea un repositorio en GitHub (p. ej. `fundacion-amigos-verde`).
2. Sube estos archivos (`index.html`, `assets/...`, etc.).
3. Ve a **Settings → Pages** y selecciona **Deploy from a branch** (branch: `main`, folder: `/root`).
4. Guarda. La URL será algo como: `https://tuusuario.github.io/fundacion-amigos-verde/`

## Despliegue en Netlify
### Opción A: Conectar repositorio
1. Entra a Netlify → **Add new site** → **Import an existing project**.
2. Conecta tu cuenta de GitHub y elige el repositorio.
3. Build command: *(vacío)*. Publish directory: `/` (raíz).
4. Deploy.

### Opción B: Arrastrar y soltar
1. Ve a https://app.netlify.com/drop
2. Arrastra la carpeta del proyecto (o un .zip con estos archivos en la raíz).

## Personalización
- Colores y animaciones en `index.html` (Tailwind vía CDN).
- Reemplaza imágenes en `assets/img/` con tus fotografías reales.

## Dominio personalizado (Netlify)
- En tu sitio Netlify → **Domain settings** → **Add custom domain**.
- Apunta tu dominio con CNAME a `<tu-sitio>.netlify.app` y configura DNS.
