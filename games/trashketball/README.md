<div align="center">

<img src="../../assets/logos/trashketball-logo.svg" alt="Logo Trashketball" width="480"/>

![Genero](https://img.shields.io/badge/Género-Arcade_%2F_Puntería-2980B9?style=flat-square)
![Tech](https://img.shields.io/badge/Tech-HTML5_Canvas_%2B_JS-C6FF3D?style=flat-square)
![Duración](https://img.shields.io/badge/Duración-60s_por_partida-F1C40F?style=flat-square)
![Versiones](https://img.shields.io/badge/Versiones_documentadas-3-E67E22?style=flat-square)

[◀ Volver al portafolio](../../README.md)

</div>

---

## 🗑️ Sobre el juego

**Trashketball** es un arcade de puntería con temática de reciclaje: cada residuo que aparece debe terminar en su contenedor correcto — **orgánico**, **reciclable** o **no reciclable** — antes de que se acabe el tiempo. En su versión final ("Extreme Pro"), el reto ya no es solo apuntar bien: un **viento dinámico** empuja la trayectoria del residuo en cada tiro, obligándote a compensar el ángulo, y encestar varios seguidos activa un **combo** que multiplica tu puntaje.

- **¿De qué trata?** De clasificar residuos correctamente lanzándolos a su contenedor, contra el reloj.
- **¿Cuál es el objetivo del jugador?** Acumular la mayor cantidad de puntos posible en 60 segundos, encestando en el bote correcto y manteniendo el combo activo.
- **¿Cuál es la mecánica principal?** Arrastrar el residuo hacia atrás como una resortera y soltarlo con el ángulo y fuerza correctos para que caiga en el contenedor indicado — compensando además el viento, que cambia en cada tiro.

## 🎮 Género

`Arcade` · `Puntería / Física` · con enfoque en educación ambiental

## ⌨️ Controles

| Acción | Control |
|---|---|
| Cargar el tiro | `Click` / `Touch` y mantener presionado sobre el residuo |
| Apuntar | Arrastrar el `Mouse` / `dedo` hacia atrás (efecto resortera) |
| Lanzar | Soltar el `Click` / `Touch` |

*Pensado para jugarse tanto en escritorio (mouse) como en móvil (touch).*

## 🌬️ Mecánicas destacadas (versión final)

| Elemento | Descripción |
|---|---|
| 💨 Viento dinámico | Cada tiro tiene una fuerza de viento aleatoria que desvía la trayectoria |
| 🔥 Combos | Encestar seguido multiplica los puntos obtenidos |
| ❤️ Vidas | 3 vidas — fallar el contenedor correcto descuenta una |
| ⏱️ Tiempo | Partidas cronometradas de 60 segundos |
| 🏙️ Escenario urbano | Fondo de ciudad animado que ambienta el juego |

## 🛠️ Tecnología utilizada

- **HTML5** (`<canvas>` para la física del lanzamiento y las animaciones)
- **CSS3** para la interfaz (HUD de puntaje, combo, indicador de viento)
- **JavaScript** vanilla — cálculo de trayectoria tipo proyectil, sistema de viento aleatorio, detección de colisión con cada contenedor y manejo de eventos de mouse/touch

## 📸 Capturas de pantalla

<div align="center">
<table>
<tr>
<td align="center"><img src="screenshots/v3-menu.png" width="380"/><br/><sub>Pantalla inicial — Trashketball Pro</sub></td>
<td align="center"><img src="screenshots/v3-gameplay.png" width="380"/><br/><sub>Gameplay — viento activo, combo y contenedores</sub></td>
</tr>
</table>
</div>

---

## 🧪 Historial de versiones (betas)

Trashketball es el proyecto que más iteraciones tuvo dentro de este portafolio — cambió de mecánica central **dos veces** antes de llegar a su forma final.

### 🔹 v1 — Modo Quiz

La primera beta era la más simple posible: se mostraba un residuo en pantalla y el jugador debía **tocar el bote correcto** entre 3 opciones (orgánico, reciclable, no reciclable). Sin física, sin lanzamiento — el objetivo era validar el concepto educativo (clasificación correcta de residuos) antes de sumar cualquier mecánica de puntería.

<div align="center">
<img src="versions/v1-quiz.png" width="420"/>
<br/><sub>v1 — Modo Quiz: tocar el bote correcto según el tipo de residuo</sub>
</div>

📄 Código: [`versions/v1-quiz.html`](versions/v1-quiz.html)

### 🔹 v2 — Mecánica de resortera

Se reemplazó el toque directo por una mecánica de **arrastrar y soltar tipo resortera**: ahora había que apuntar y calcular la fuerza del lanzamiento para encestar el residuo en el contenedor correcto. Se agregaron vidas (3) y el límite de 60 segundos, acercando el juego a un arcade real en lugar de un simple quiz.

**Cambios clave respecto a v1:**
- ✅ Lanzamiento por arrastre (resortera) en vez de toque directo
- ✅ Sistema de vidas (3) y cronómetro de 60s
- ✅ Contador de puntaje visible en el HUD

<div align="center">
<img src="versions/v2-slingshot.png" width="420"/>
<br/><sub>v2 — Mecánica de resortera: arrastrar y soltar para lanzar</sub>
</div>

📄 Código: [`versions/v2-slingshot.html`](versions/v2-slingshot.html)

### 🔹 v3 — Extreme Pro (versión final)

La versión final añadió la capa de dificultad que le da nombre al juego: **viento dinámico** que cambia en cada tiro y obliga a recalcular la trayectoria, un **sistema de combos** que premia la precisión sostenida, y un **fondo de ciudad animado** que reemplaza el escenario plano de las versiones anteriores.

**Cambios clave respecto a v2:**
- ✅ Viento dinámico aleatorio por tiro (indicador visual de dirección/fuerza)
- ✅ Sistema de combos con multiplicador de puntos
- ✅ Escenario urbano animado (edificios, nubes en movimiento)
- ✅ HUD rediseñado (puntaje, combo y viento visibles simultáneamente)

<div align="center">
<img src="screenshots/v3-gameplay.png" width="420"/>
<br/><sub>v3 — Extreme Pro: viento, combo y ciudad de fondo</sub>
</div>

📄 Código de esta versión: [`index.html`](index.html)

---

## ▶️ Cómo jugar

Descarga o clona el repositorio y abre el archivo `index.html` de esta carpeta directamente en tu navegador — no requiere instalación ni servidor.

[◀ Volver al portafolio principal](../../README.md)
