# tati

Geometry Dash casero (HTML + CSS + JS, sin dependencias).

- `index.html` — el juego completo: 5 niveles, modo **Wave** (mantén pulsado para subir)
  y modo **Cubo** (clic para saltar, con doble salto), portales de cambio de modo,
  música chiptune generada con Web Audio y menú de selección de nivel.

## Controles

- **Wave:** mantén clic / espacio / ↑ para subir, suelta para bajar.
- **Cubo:** clic / espacio / ↑ para saltar (un salto extra en el aire).
- **R:** reiniciar el nivel.

## Desarrollo

Es un sitio estático: se publica la raíz del repositorio tal cual.

```sh
netlify dev --port 8889
```
