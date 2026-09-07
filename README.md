# DUCK - Produção Musical

Portfolio web de Duck (Duck4x), produtor musical, beatmaker e engenheiro de som de Aracaju, Sergipe, Brasil.

## Estrutura do Projeto

```
heyduck-rebuild/
├── index.html              ← Página principal
├── server.js               ← Servidor local (Node.js)
├── README.md
├── .gitignore
├── .nojekyll
├── .github/
│   └── workflows/
│       └── deploy.yml      ← GitHub Actions
├── css/
│   └── main.css            ← Estilos completos
├── js/
│   ├── data.js             ← Datos: singles, tracks, i18n
│   ├── main.js             ← Orchestrator
│   ├── animations.js       ← GSAP animations
│   ├── audio.js            ← Audio pad player
│   └── easter-egg.js       ← Easter egg waves
├── audio/
│   └── duck.mp3            ← Audio Duck
└── images/
    ├── logo-*.png          ← Logos
    ├── capa-*.jpg          ← Cover arts
    ├── covers/             ← Album covers
    └── studio/             ← Studio photos
```

## Tecnologías

- **HTML5** - Markup semántico
- **CSS3** - Custom Properties, Grid, Flexbox
- **JavaScript ES6+** - Modular, vanilla
- **GSAP 3.12** - Animaciones y scroll effects
- **i18n** - Multiidioma (PT/ES/EN)

## Funcionalidades

- Preloader animado con GSAP
- Cursor personalizado con dot + ring
- Ticker de scroll infinito
- Hero con parallax y text split
- Stats counters animados
- Galería 3D con hover effects
- Portfolio con filtros (Pop/Trap/MPB)
- Audio pad interactivo
- Easter egg sound wave
- Smooth scroll navigation
- Responsive (desktop/tablet/mobile)

## Ejecutar Local

```bash
node server.js
# → http://localhost:4242
```

## Deploy

- **GitHub Pages**: Push a `main` → deploy automático
- **Cloudflare Pages**: Conectar repo → deploy
- **Netlify**: Importar proyecto → deploy

## URLs de Producción

- **Sitio oficial (vivo):** https://belentani7.github.io/heyduck/
- **Repositorio canónico:** https://github.com/belentani7/heyduck

> ⚠️ Aviso (verificado 2026-08): los enlaces alternativos que antes aparecían aquí **no entregan el sitio de DUCK**:
> - `https://heyduck.pages.dev` — el dominio no existe (falla DNS). No hay nada desplegado ahí.
> - `https://heyduck.netlify.app` — está secuestrado por una página de una memecoin de Solana ("$HEYDUCK / $MYRO$WIF", token `0xA3A9...`), NO es el sitio de DUCK. No lo compartas.
>
> Esta carpeta `heyduck-rebuild/` es una **copia de referencia** sin `.git` ni los assets listados (`audio/duck.mp3`, `images/logo-*`, `images/capa-*` no están presentes). No la despliegues como está: usa el repositorio canónico `belentani7/heyduck`, que contiene `index.html`, `styles.css`, `app.js`, `data.js` y se publica por GitHub Actions en el enlace oficial.

## Contacto

- Instagram: [@duck4s](https://instagram.com/duck4s)
- Email: duck-beats@hotmail.com
- WhatsApp: +55 79 99602-6590

## Licencia

© 2026 DUCK Produção Musical — Todos os direitos reservados
