# Cómo subir este portafolio a GitHub (paso a paso)

Esta guía es solo para ti, Camilo — no es parte del portafolio en sí. Bórrala del repo cuando termines de seguir los pasos.

**Importante:** en esta versión los README ya tienen botones "Jugar" que apuntan directo a `https://sandiacamil.github.io/game-development-portfolio/...`. Para que esos botones funcionen, **el paso 4 (GitHub Pages) ya no es opcional** — sin eso, los botones "Jugar" no van a abrir nada.

## 1. Crear el repositorio en GitHub

1. Entra a [github.com/new](https://github.com/new) con tu cuenta **SandiaCamil**.
2. Nombre del repositorio: `game-development-portfolio` — **usa exactamente este nombre**, porque todos los enlaces "Jugar" del README ya están escritos asumiendo esta URL. Si le pones otro nombre, tienes que reemplazar `game-development-portfolio` por el nombre real en todos los README (buscar y reemplazar).
3. Márcalo como **Público**.
4. **No** inicialices con README — déjalo vacío y dale "Create repository".

## 2. Subir los archivos

**Sube el contenido que está dentro de esta carpeta** (`README.md`, `assets/`, `games/`, etc.), no la carpeta contenedora en sí. Puedes arrastrarlos desde la web de GitHub, o usar git:

```bash
git init
git add .
git commit -m "Portafolio con botones de jugar y código por versión"
git branch -M main
git remote add origin https://github.com/SandiaCamil/game-development-portfolio.git
git push -u origin main
```

Si te pide autenticación, usa un **Personal Access Token** (no tu contraseña normal) — se genera en `Settings → Developer settings → Personal access tokens`.

## 3. Activar GitHub Pages (obligatorio para los botones "Jugar")

1. En tu repositorio, ve a `Settings → Pages`.
2. En "Branch", selecciona `main` y la carpeta `/ (root)`.
3. Guarda. GitHub tarda uno o dos minutos en publicar y te da una URL tipo `https://sandiacamil.github.io/game-development-portfolio/`.
4. Recién ahí los botones "JUGAR" de todos los README van a abrir el juego real y jugable, no el código.

## 4. Verificar que todo funcione

Entra a `https://github.com/SandiaCamil/game-development-portfolio` y revisa:

- [ ] El README principal muestra la portada y las imágenes correctamente (a veces GitHub tarda unos segundos en cachear imágenes nuevas).
- [ ] Los botones "JUGAR" de la portada abren el juego jugable (no código) — solo funciona después del paso 3.
- [ ] Los botones "Código" abren el archivo fuente en la vista de GitHub — estos funcionan siempre, incluso sin Pages.
- [ ] La tabla "Jugar cualquier versión" del README principal: probar al menos un enlace de cada juego (v1, v2, v3).

## 5. Si usas otro nombre de repositorio

Todos los enlaces "Jugar" en `README.md`, `games/dungeonmathquest/README.md`, `games/trashketball/README.md` y `games/gotitas-magicas/README.md` tienen la forma:

```
https://sandiacamil.github.io/game-development-portfolio/...
```

Si tu repo se llama distinto, reemplaza `game-development-portfolio` por el nombre real en esa parte de la URL (el usuario `sandiacamil` no cambia). Los botones "Código" no necesitan cambios si el repo se llama igual que el `blob/main/...` que ya está en los enlaces — si cambia el nombre, ahí también hay que actualizarlo.

## 6. Pendiente opcional

- GIFs animados en vez de capturas estáticas (se ve bien en portafolios, pero requiere grabar pantalla y convertir a GIF) — no es necesario, las capturas ya cumplen el requisito.

---

*Este archivo no es parte del portafolio — es una nota tuya. Puedes eliminarlo del repo cuando termines de seguir los pasos.*
