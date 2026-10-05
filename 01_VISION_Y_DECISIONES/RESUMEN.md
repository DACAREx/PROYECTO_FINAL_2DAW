# RESUMEN DEL PROYECTO

Proyecto final de 2º DAW. Web pública y gratuita de enfrentamientos entre
personajes ficticios (anime, manga, videojuegos, cómics, películas, series...).

## Cómo funciona
- El usuario elige dos personajes (ej: Saitama vs Levi).
- La app devuelve un ganador, un nivel de ventaja y una explicación.
- El resultado está PREVIAMENTE guardado en la base de datos.
- Cada enfrentamiento tiene varias explicaciones escritas de antemano.
- Se muestra una explicación elegida al azar con probabilidad ponderada por votos.

## Comunidad
- Los usuarios votan explicaciones y el resultado (de acuerdo / no de acuerdo).
- Pueden comentar y enviar propuestas de nuevas explicaciones.
- Las propuestas NO se publican solas: el administrador las acepta o rechaza.
- Si se acepta, pasa a ser explicación oficial votable.

## Lo que NO es
- No es un simulador de combate.
- No calcula ganadores con estadísticas.
- El usuario no configura el combate.
- No usa IA dentro de la app (la IA solo ayuda durante el desarrollo).

## Alcance
- Objetivo final: ~90 personajes. Se empieza con 10-20.
- Pixel art propio.
- Usuarios, login, votos, comentarios, propuestas, panel de administración.
- Realizable por UNA sola persona. Prioridad: proyecto terminado > proyecto enorme.

## Arquitectura (provisional)
Frontend -> API REST -> Backend -> Base de datos
Posible stack: HTML/CSS/JS, Vue.js, PHP/Laravel, MySQL/MariaDB, Git/GitHub.
