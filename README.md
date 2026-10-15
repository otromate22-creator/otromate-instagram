# otromate-instagram

Imágenes y videos públicos de Instagram de **Otro Mate**. Metricool necesita un link público de cada pieza, por eso este repo es **público**: cualquiera en internet puede ver lo que hay acá.

**Nunca subas acá** comprobantes, datos de clientes, capturas de chats, contraseñas ni nada privado. Solo piezas terminadas para publicar y fotos de producto.

## Carpetas
| Carpeta | Qué hay |
|---|---|
| `semanas/<AAAA-MM-DD del lunes>/` | Piezas terminadas de esa semana (PNG y MP4). También acá van las fotos que suben los dueños para que el agente arme la semana. |
| `lanzamiento/`, `lanzamiento-3/` | Piezas del lanzamiento. |

Las piezas se generan en el repo privado `otromate-agente` (ahí están los config, los textos y los captions en `semanas/<lunes>/textos.md`) y se copian acá con el mismo nombre.

## Link público de una pieza
```
https://raw.githubusercontent.com/otromate22-creator/otromate-instagram/main/semanas/<lunes>/<archivo>
```
Después de subir algo, GitHub puede tardar hasta 5 minutos en mostrar la versión nueva.

## Si estás editando este repo (persona o Claude)
- Antes de subir, traé lo último (`git pull --ff-only`): Ramiro y Gastón trabajan cada uno con su Claude.
- Si cambiás cómo se organizan las carpetas, actualizá este README y el de `otromate-agente`.
