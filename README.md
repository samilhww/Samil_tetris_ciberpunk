# 🟦 Tetris Ciberpunk – One File

Juego tipo Tetris responsive con temática oscura ciberpunk, desarrollado en un solo archivo HTML usando Bootstrap 5 (CDN) y JavaScript puro.

## 🎮 Características

- Piezas clásicas de Tetris (I, O, T, L, J, S, Z) con colores neón
- Controles de teclado, táctiles (botones on-screen) y mouse
- Sistema de puntaje + líneas completadas
- Temporizador de 3 minutos
- 3 niveles de dificultad (Fácil / Normal / Difícil)
- Diseño responsive centrado (desktop + móvil)
- HUD con Bootstrap 5 + Font Awesome

## 🚀 Cómo jugar localmente

1. Abre el archivo `index.html` en cualquier navegador moderno.
2. O usa un servidor local:
   ```bash
   # Con Python
   python -m http.server 5500
   # Luego visita http://localhost:5500
   ```

## 📁 Estructura

```
tetris-ciberpunk/
├── index.html      # Todo el juego (HTML + CSS + JS)
└── README.md       # Este archivo
```

No requiere dependencias, API Keys ni archivo `.env`.

## 🌐 Publicación

### GitHub Pages
1. Sube el repositorio a GitHub.
2. Ve a Settings → Pages → Source: Deploy from a branch → main → / (root).
3. URL típica: `https://tu-usuario.github.io/tetris-ciberpunk`

### Vercel
1. Importa el repositorio en Vercel.
2. Framework Preset: Other (o Static).
3. Deploy. URL típica: `https://tetris-ciberpunk.vercel.app`

## 🛠️ Tecnologías

- HTML5
- CSS3 (custom properties + cyberpunk theme)
- Bootstrap 5.3 (CDN)
- Font Awesome 6 (CDN)
- JavaScript puro (Canvas 2D)

## 📝 Créditos

Proyecto académico – One File Tetris Ciberpunk.
Hecho con ayuda de IA (Grok / xAI) para estructurar el código, HUD y lógica.
