# Tilcayo — El rescate en la selva

Juego de plataformas hecho con [Phaser 3](https://phaser.io/). Tilcayo, un pequeño ocelote,
cruza la selva para rescatar a su familia, que un cazador encerró en una jaula en lo alto de su templo.

## Cómo jugar

Abre `part5.html` (o `index.html`) desde un servidor local, por ejemplo:

```bash
python3 -m http.server 8000
# y entra a http://localhost:8000
```

> Abrir el archivo con doble clic (`file://`) no carga las imágenes: hace falta un servidor.

### Controles

| Tecla | Acción |
|---|---|
| ← → | Caminar |
| ↑ / ESPACIO | Saltar |
| X | Atacar con espadas (con poder) |
| R | Reiniciar |

- Come carne para transformarte en guerrero y atacar con espadas durante 30 s.
- Salta sobre el jefe para quitarle vida.
- De vez en cuando cae comida del cielo.

## Partes

| Archivo | Contenido |
|---|---|
| `part1.html` | Escenario de la selva |
| `part2.html` | Tilcayo en la selva |
| `part3.html` | Poder de la carne (guerrero con espadas) |
| `part4.html` | Salto y torreta enemiga |
| `part5.html` | **Juego completo**: créditos, menú, historia, tormenta, jefe final, pirámide y rescate |
| `part6.html` – `part10.html`, `game.html` | Tutorial original de Phaser 3 (base del proyecto) |

## Créditos

- Jaime Dennis Guzman
- Leonardo Herrera Dante
- Neils Laime Balderrama
