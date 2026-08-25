# Johan Yandun — Portafolio

Sitio portafolio de una sola página para **Johan Yandun**, Desarrollador Full Stack Jr. especializado en agentes autónomos con LLMs, MCP y calidad de datos.

Construido con HTML, CSS y JavaScript puro (sin frameworks, sin build step) — paleta clara de blancos, azules y verdes (confianza y crecimiento), animaciones de scroll (reveals, contadores, barra de progreso), foto de perfil con anillo giratorio y efecto tilt 3D, typewriter de roles, marquee de tecnologías, navegación con sección activa y menú móvil.

## Estructura

```
.
├── index.html          # sitio completo (HTML + CSS + JS)
├── assets/
│   ├── johan.jpeg      # foto de perfil
│   └── punkstars.png   # captura del proyecto Punk Stars
└── README.md
```

## Ver en local

No necesita instalación. Basta con abrir `index.html` en el navegador, o servirlo con cualquier servidor estático:

```bash
python3 -m http.server 8000
# luego abrir http://localhost:8000
```

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `portfolio` o `johanyandun.github.io`).
2. Conecta este repo local y sube el código:

   ```bash
   git remote add origin https://github.com/JohanYP/NOMBRE-DEL-REPO.git
   git branch -M main
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Source → Deploy from a branch → main / (root)** → Save.
4. El sitio queda publicado en `https://JohanYP.github.io/NOMBRE-DEL-REPO/`
   (o en `https://JohanYP.github.io/` directamente si el repo se llama `johanyandun.github.io`).

## Publicar en Vercel

1. Sube el repo a GitHub siguiendo los pasos anteriores.
2. Entra a [vercel.com](https://vercel.com) → **Add New Project** → importa el repositorio.
3. Framework preset: **Other** (sitio estático). No requiere build command ni output directory especial.
4. Deploy. Vercel te da una URL `https://NOMBRE.vercel.app` automáticamente.

Alternativa rápida sin conectar GitHub: instala la CLI (`npm i -g vercel`) y desde esta carpeta corre `vercel`.

## Editar contenido

Todo el contenido (texto, enlaces, proyectos) está directamente en `index.html`, dentro de las secciones marcadas con comentarios (`<!-- HERO -->`, `<!-- PROJECTS -->`, etc.). Los colores y tipografías están centralizados como variables CSS al inicio del `<style>` (`:root { --bg, --navy, --blue, --green, ... }`).

## Contacto

- Email: johanyandun1@gmail.com
- LinkedIn: [linkedin.com/in/johanyandun-6bb3a342b](https://linkedin.com/in/johanyandun-6bb3a342b)
- GitHub: [github.com/JohanYP](https://github.com/JohanYP)
