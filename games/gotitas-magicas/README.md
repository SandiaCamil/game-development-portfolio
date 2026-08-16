<div align="center">

<img src="../../assets/logos/gotitas-magicas-logo.svg" alt="Logo Gotitas Mágicas" width="480"/>

![Genero](https://img.shields.io/badge/Género-Arcade_%2F_Catcher-2563EB?style=flat-square)
![Tech](https://img.shields.io/badge/Tech-HTML5_%2B_JS-7C3AED?style=flat-square)
![Tema](https://img.shields.io/badge/Tema-Cuidado_del_agua-059669?style=flat-square)
![Versiones](https://img.shields.io/badge/Versiones_documentadas-1-DB2777?style=flat-square)

[◀ Volver al portafolio](../../README.md)

</div>

---

## 💧 Sobre el juego

**Gotitas Mágicas** es un arcade tipo *catcher* con un mensaje de fondo: la concientización sobre el **cuidado del agua**. Ajolí, un pequeño ajolote, necesita agua pura para sobrevivir — y depende de ti para conseguirla. Mueves una canasta a lo largo de la parte inferior de la pantalla para atrapar gotas de agua limpia mientras evitas (o aprovechas, según el power-up) otros elementos que caen.

Cada cierto tiempo el juego muestra mensajes educativos reales sobre el consumo de agua (por ejemplo, cuánta agua se desperdicia con una llave goteando), integrando el aprendizaje directamente en la experiencia de juego, no como un texto aparte.

- **¿De qué trata?** De purificar agua para Ajolí atrapando gotas limpias con una canasta, mientras aprendes sobre el cuidado del recurso hídrico.
- **¿Cuál es el objetivo del jugador?** Llenar la barra de progreso de "agua pura" recolectando suficientes gotas antes de quedarse sin las 3 vidas, subiendo de nivel a medida que avanza.
- **¿Cuál es la mecánica principal?** Mover la canasta horizontalmente para atrapar gotas y power-ups (❄️ Hielo, 🛡️ Escudo, 💖 Vidas) que caen desde la parte superior de la pantalla, sumando puntos y progreso.

## 🎮 Género

`Arcade` · `Catcher` · con enfoque en concientización ambiental

## ⌨️ Controles

| Acción | Control |
|---|---|
| Mover la canasta | Mover el `Mouse` horizontalmente |
| En móvil | Deslizar el `dedo` (touch) horizontalmente |

*Controles minimalistas de un solo eje — pensado para ser accesible incluso para jugadores jóvenes.*

## ✨ Power-ups

| Power-up | Efecto |
|---|---|
| ❄️ Hielo | Ralentiza la caída de elementos, facilita atrapar más gotas |
| 🛡️ Escudo | Protege una vida ante un fallo |
| 💖 Vida extra | Suma una vida adicional |

## 🛠️ Tecnología utilizada

- **HTML5** y **CSS3** — interfaz con tarjetas tipo *glassmorphism*, animaciones de nubes, burbujas y texto flotante
- **JavaScript** vanilla — loop de juego, generación de objetos que caen, detección de colisión con la canasta, sistema de niveles y progreso
- **localStorage** — persistencia del puntaje más alto entre partidas

## 📸 Capturas de pantalla

<div align="center">
<table>
<tr>
<td align="center"><img src="screenshots/menu.png" width="380"/><br/><sub>Pantalla inicial</sub></td>
<td align="center"><img src="screenshots/gameplay.png" width="380"/><br/><sub>Gameplay — atrapando gotas para Ajolí</sub></td>
</tr>
</table>
</div>

---

## 🧪 Historial de versiones (betas)

A diferencia de DungeonMathQuest y Trashketball, **Gotitas Mágicas** llegó directamente a esta primera versión pública sin betas intermedias documentadas — es el prototipo más reciente del portafolio. Queda como base para las siguientes iteraciones (ver sección de mejoras abajo).

### 🔹 v1 — Versión inicial (única por ahora)

Incluye ya el ciclo completo de juego: sistema de vidas, power-ups, niveles progresivos, mensajes educativos y persistencia del puntaje más alto en `localStorage`.

<div align="center">
<img src="screenshots/gameplay.png" width="420"/>
<br/><sub>v1 — Atrapando gotas de agua pura para Ajolí</sub>
</div>

📄 Código de esta versión: [`index.html`](index.html)

> 📌 **Nota:** para la siguiente entrega se planea documentar aquí una v2 con más niveles y variedad de obstáculos, siguiendo el mismo formato de historial que los otros dos juegos.

---

## ▶️ Cómo jugar

Descarga o clona el repositorio y abre el archivo `index.html` de esta carpeta directamente en tu navegador — no requiere instalación ni servidor.

[◀ Volver al portafolio principal](../../README.md)
