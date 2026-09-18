# Reto Tec 🎲

Juego de mesa de retos para 2-4 jugadores, en formato tablero de cruz. Vanilla HTML/CSS/JS, sin backend, todo en memoria del cliente.

## Cómo jugar
1. Elige el número de jugadores (2-4) e introduce sus nombres.
2. Cada jugador tiene 4 cartas boca abajo. En su turno, el jugador activo voltea una carta y decide:
   - **Hacer el reto**: se lanza el dado (1-6) y los puntos se multiplican por x1, x2 o x3 según la carta.
   - **Pasar**: la carta va al descarte, 0 puntos.
3. La carta usada se retira y se repone automáticamente desde el mazo.
4. El turno pasa al siguiente jugador.
5. La partida termina cuando el mazo se queda sin cartas para reponer. Se muestra el ranking final.

## Desarrollo local
Es un único archivo estático, `index.html`. Ábrelo directamente en el navegador o sirve la carpeta con cualquier servidor estático:

```bash
python3 -m http.server 8080
```

## Retos
El array de retos (`CHALLENGE_POOL`) está en `index.html` y es fácilmente editable para añadir, quitar o modificar retos y sus multiplicadores (x1, x2, x3).
