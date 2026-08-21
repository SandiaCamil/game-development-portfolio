<div align="center">

<img src="../../assets/logos/dungeonmathquest-logo.svg" alt="Logo DungeonMathQuest" width="480"/>

![Genero](https://img.shields.io/badge/Género-Platformer_educativo-4a3f7a?style=flat-square)
![Tech](https://img.shields.io/badge/Tech-HTML5_Canvas_%2B_JS-00f5d4?style=flat-square)
![Niveles](https://img.shields.io/badge/Niveles-10-ffd23f?style=flat-square)
![Versiones](https://img.shields.io/badge/Versiones_documentadas-3-3ddc97?style=flat-square)

[![Jugar versión final](https://img.shields.io/badge/JUGAR_VERSIÓN_FINAL-00f5d4?style=for-the-badge&logoColor=black)](https://sandiacamil.github.io/game-development-portfolio/games/dungeonmathquest/)

[Volver al portafolio](../../README.md)

</div>

---

## En qué se enfoca

Este juego nace para resolver un problema puntual: repasar operaciones aritméticas combinadas (suma, resta, multiplicación, división y paréntesis) suele ser tedioso cuando se hace con ejercicios sueltos en papel. La idea fue convertir ese repaso en una razón para seguir jugando — 10 niveles con temática de aventura de plataformas, dirigidos a estudiantes de secundaria, donde resolver bien la cuenta es literalmente lo que te deja avanzar de plataforma.

- Preguntas de opción múltiple integradas en el mapa (cofres), no en una lista aparte.
- Feedback inmediato: se sabe al instante si el cofre elegido tenía la respuesta correcta.
- Puntuación final sobre 10, con un rango narrativo según el desempeño (de "Sigue practicando" a "Gran Maestro del Reino").

## Sobre el juego

Un dragón numérico encerró el reino en una torre de acertijos. El jugador escala la torre saltando entre plataformas y debe tocar el **cofre con la respuesta correcta** de cada operación combinada — los demás cofres son señuelos que hacen perder el intento si se tocan primero.

- **De qué trata:** escalar una torre resolviendo matemáticas mientras se controla a un personaje en un entorno de plataformas.
- **Objetivo del jugador:** completar los 10 niveles eligiendo siempre el cofre correcto, para obtener el mejor rango posible al final.
- **Mecánica principal:** movimiento lateral + salto entre plataformas, combinado con la resolución de una operación aritmética por nivel.

## Controles

| Acción | Tecla |
|---|---|
| Moverse a la izquierda | `←` / `A` |
| Moverse a la derecha | `→` / `D` |
| Saltar | `↑` / `W` / `ESPACIO` |
| Avanzar / continuar | Botón en pantalla |

También tiene botones táctiles en pantalla para jugar desde el celular.

## Sistema de puntaje

| Puntaje | Rango |
|---|---|
| 10/10 | Gran Maestro del Reino |
| 8-9/10 | Caballero Calculador |
| 6-7/10 | Aprendiz Valiente |
| 4-5/10 | Escudero en Entrenamiento |
| menos de 4 | Sigue practicando |

## Tecnología

- HTML5 (`<canvas>` para el renderizado del personaje y las plataformas)
- CSS3 (estética retro pixel-art, fuentes `Press Start 2P` y `VT323`)
- JavaScript vanilla — física de salto, colisiones plataforma/cofre, generación de niveles y validación de operaciones

---

## Historial de versiones

<table>
<tr><th align="left">Versión</th><th align="left">Qué cambió</th><th align="center">Jugar</th></tr>
<tr>
<td><b>v1 — Quiz</b></td>
<td>Prototipo inicial: sin plataformas ni movimiento del personaje. Se mostraba la operación y 4 posibles resultados para elegir. Sirvió para validar la lógica de generación de operaciones y el sistema de puntaje antes de invertir tiempo en física.</td>
<td align="center"><a href="https://sandiacamil.github.io/game-development-portfolio/games/dungeonmathquest/versions/v1-quiz.html">Jugar</a></td>
</tr>
<tr>
<td><b>v2 — Nivel plano</b></td>
<td>Primer entorno de plataformas real: el personaje ya se mueve y salta físicamente, y hay que tocar el cofre correcto entre varios distribuidos en el nivel. Todos los cofres están al ras del suelo — el salto existe pero el diseño de nivel aún no lo exige.</td>
<td align="center"><a href="https://sandiacamil.github.io/game-development-portfolio/games/dungeonmathquest/versions/v2-flatlevel.html">Jugar</a></td>
</tr>
<tr>
<td><b>v3 — Final</b></td>
<td>Se agregaron plataformas a distinta altura, obligando a saltar entre ellas. Se sumaron cofres falsos como factor de riesgo y controles táctiles para jugar desde el celular.</td>
<td align="center"><a href="https://sandiacamil.github.io/game-development-portfolio/games/dungeonmathquest/">Jugar</a></td>
</tr>
</table>

### v1 — Quiz

<div align="center">
<img src="versions/v1-quiz.png" width="420"/>
<br/><sub>Pantalla de bienvenida — se elige la respuesta entre 4 opciones, sin plataformas</sub>
</div>

### v2 — Nivel plano

<div align="center">
<table>
<tr>
<td align="center"><img src="versions/v2-flatlevel-intro.png" width="380"/><br/><sub>Pantalla de bienvenida</sub></td>
<td align="center"><img src="versions/v2-flatlevel.png" width="380"/><br/><sub>Gameplay — cofres al ras del suelo</sub></td>
</tr>
</table>
</div>

### v3 — Final

<div align="center">
<table>
<tr>
<td align="center"><img src="screenshots/v3-menu.png" width="380"/><br/><sub>Pantalla de bienvenida</sub></td>
<td align="center"><img src="screenshots/v3-gameplay.png" width="380"/><br/><sub>Gameplay — plataformas y operación combinada</sub></td>
</tr>
</table>
</div>

---

[Volver al portafolio principal](../../README.md)
