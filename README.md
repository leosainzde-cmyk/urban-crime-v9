# Urban Crime V9

Un juego sandbox urbano de estilo GTA/Crime sim hecho en Three.js + HTML5, con:

- ciudad grande y más realista
- coches conducibles
- NPCs que hablan con voz sintética
- inventario con varias armas
- salud, munición y recarga
- tiendas con interacción
- mejor rendimiento y limpieza de errores

## Cómo ejecutarlo

1. Abre la carpeta del proyecto.
2. Sirve la web con un servidor local:

```bash
python3 -m http.server 8000
```

3. En el navegador visita:

```text
http://localhost:8000/
```

## Controles

- WASD: mover
- Ratón: mirar
- Click izquierdo: disparar
- E: interactuar / entrar o salir del vehículo
- Shift: correr
- R: recargar
- I: inventario
- 1-8: cambiar arma
- Esc: menú / bloqueo del cursor

## Nota

Este proyecto usa módulos ES importados desde CDN (`three` + `PointerLockControls`), por lo que debe ejecutarse desde un servidor web y no como archivo local directo.
