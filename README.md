# Mariel García-Hernández, PhD · Dra. Data Rabbit

Sitio estático (CV como dashboard de datos + INDEX + Schema Lab).

## Publicar en GitHub Pages
1. Crea un repositorio público en https://github.com/punkytanoise (p. ej. `dradatarabbit`).
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio (incluido `.nojekyll`).
3. Settings → Pages → Source: *Deploy from a branch* → Branch `main` / `(root)` → Save.
4. En 1–2 minutos: `https://punkytanoise.github.io/<nombre-del-repo>/`
   (si nombras el repo `punkytanoise.github.io`, queda en `https://punkytanoise.github.io/`).

## Dominio propio
Settings → Pages → Custom domain → `tudominio.com`. En tu proveedor de dominio:
- 4 registros A → 185.199.108.153 · 185.199.109.153 · 185.199.110.153 · 185.199.111.153
- CNAME `www` → `punkytanoise.github.io`
Luego activa *Enforce HTTPS*.

## Estructura
- `index.html` — la página
- `data/*.json` — los datos (publicaciones, clases, tesis, etc.). Editar aquí actualiza las gráficas.
- `assets/` — tipografías, logos e imágenes de INDEX y Schema Lab
- `vendor/d3.v7.9.0.min.js` — librería de gráficas

Para verlo en tu computadora usa un servidor local (por ejemplo `python3 -m http.server` dentro de la carpeta);
abrir `index.html` con doble clic no carga los datos.
