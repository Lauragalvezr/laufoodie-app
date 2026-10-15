# LauFoodie Planner

Prototipo navegable de aplicación móvil para Laufoodie.bog.

## Publicación en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube todo el contenido de esta carpeta conservando las carpetas `.github` y `src`.
3. Usa `main` como rama principal.
4. En **Settings > Pages**, configura **Source: GitHub Actions**.
5. En **Actions** podrás ver el despliegue. Al finalizar, la URL pública aparece en Pages.

## Desarrollo local
```bash
npm install
npm run dev
```

El archivo `vite.config.js` usa `base: './'` para funcionar bajo la ruta del repositorio en GitHub Pages.
