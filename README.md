# GT Scripts — Herramientas para Guerras Tribales

Web estática (un solo archivo) con herramientas y biblioteca de scripts para Guerras Tribales.
Sin build, sin dependencias: se sirve tal cual.

## Estructura
- `index.html` — la web completa (HTML + CSS + JS embebidos).
- `Scrips Legales/` — capturas que muestra la web.
- `.nojekyll` — desactiva el procesado Jekyll de GitHub Pages.

## Publicar / actualizar (GitHub Pages)
Editar `index.html` (o añadir capturas en `Scrips Legales/`) y:

```bash
git add .
git commit -m "describe el cambio"
git push
```

En ~1 min los cambios quedan online.

## Desarrollo local
Abrir `index.html` en el navegador, o servirlo en local con cualquier servidor estático
para que las rutas de las capturas resuelvan bien.
