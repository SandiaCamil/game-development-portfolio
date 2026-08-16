# 🚀 Cómo subir este portafolio a GitHub (paso a paso)

Esta guía es solo para ti, Camilo — no es parte del portafolio en sí. Bórrala (o déjala, no afecta la evaluación) una vez que hayas subido todo.

## 1. Crear el repositorio en GitHub

1. Entra a [github.com/new](https://github.com/new) con tu cuenta **SandiaCamil**.
2. Nombre sugerido: `game-development-portfolio` (coincide con el que pide la guía de práctica).
3. Marca el repositorio como **Público**.
4. Agrega una descripción breve, por ejemplo:
   > Portafolio de prototipos de Game Development — UPV, Gestión 2-2026.
5. **No** inicialices con README (ya tienes uno listo aquí) — déjalo vacío y dale "Create repository".

## 2. Subir los archivos

Desde la carpeta `portfolio/` que te generé, abre una terminal ahí mismo y ejecuta:

```bash
git init
git add .
git commit -m "Primera entrega: portafolio con 3 prototipos y sus betas"
git branch -M main
git remote add origin https://github.com/SandiaCamil/game-development-portfolio.git
git push -u origin main
```

Si te pide autenticación, usa un **Personal Access Token** (no tu contraseña normal) — GitHub ya no acepta contraseña por HTTPS. Lo generas en `Settings → Developer settings → Personal access tokens`.

## 3. Verificar que todo se vea bien

Una vez subido, entra a `https://github.com/SandiaCamil/game-development-portfolio` y revisa que:

- [ ] El README principal muestre el banner y las imágenes correctamente (a veces GitHub tarda unos segundos en cachear las imágenes nuevas).
- [ ] Los links a `games/dungeonmathquest/`, `games/trashketball/` y `games/gotitas-magicas/` funcionen.
- [ ] Los links "▶ Jugar" abran el HTML del juego (GitHub no ejecuta JS en la vista normal del repo — para que sea jugable *en línea* sin descargar, ver el paso 4).

## 4. (Opcional pero recomendado) Activar GitHub Pages para jugar en línea

Ahora mismo, el enlace "para jugarlo" que pide la guía de práctica solo funciona si alguien descarga el repo. Si quieres que sea jugable con un link directo en el navegador:

1. Ve a `Settings → Pages` en tu repositorio.
2. En "Branch", selecciona `main` y la carpeta `/ (root)`.
3. Guarda. GitHub te dará una URL tipo `https://sandiacamil.github.io/game-development-portfolio/`.
4. Cada juego quedará jugable en, por ejemplo:
   `https://sandiacamil.github.io/game-development-portfolio/games/dungeonmathquest/`

Si activas esto, actualiza los enlaces "▶ Jugar" en los README para que apunten a esa URL en vez de al archivo local — así cualquiera puede jugar sin clonar el repo, que es justo lo que valora la guía de práctica.

## 5. Ítems de la guía que quedan pendientes de tu parte

Ya cubrí la mayoría de los requerimientos (README principal, README individual por juego, galería, historial de versiones, controles, tecnología, logos). Todavía te falta decidir/agregar:

- Una **foto o avatar tuyo** (o ilustración) en la sección de presentación del README principal, si quieres algo más personal que el banner.
- Revisar si quieres agregar **GIFs animados** en vez de solo capturas estáticas (se ve muy bien en READMEs de portafolio, pero requiere grabar pantalla y convertir a GIF).
- El **enlace real para jugar** una vez actives GitHub Pages (paso 4).

---

*Este archivo no es parte del portafolio — es una nota tuya. Puedes eliminarlo del repo cuando termines de seguir los pasos.*
