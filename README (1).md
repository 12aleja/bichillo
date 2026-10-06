# Ecosistema artificial

Simulación visual de un ecosistema en tiempo real: plantas (algunas venenosas), herbívoros con pistola, carnívoros con cono de visión de 45°, pastillas gigantes, huevos, madriguera y una partida de 5 minutos con ganador.

Solo usa HTML, CSS y JavaScript. No necesita instalar nada ni servidor: es un único archivo `index.html`.

## Cómo jugar en local
Abre `index.html` en el navegador. Haz clic una vez en la página para activar el sonido.

## Desplegar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `ecosistema`).
2. Sube `index.html`, `README.md` y `.nojekyll` a la raíz del repositorio.
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. Tras un minuto, la web estará en `https://TU-USUARIO.github.io/ecosistema/`.

## Con Git
```bash
git init
git add .
git commit -m "Ecosistema artificial"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/ecosistema.git
git push -u origin main
```
