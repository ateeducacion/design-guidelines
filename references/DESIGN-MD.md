# Referencia sobre `DESIGN.md`

## Qué es

`DESIGN.md` es una propuesta abierta para describir sistemas de diseño de forma legible por personas y agentes de IA. Combina:

- un encabezado YAML con metadatos y tokens;
- reglas, principios y ejemplos redactados en Markdown;
- herencia entre una guía común y guías específicas.

La especificación de referencia está publicada por Google Labs y se encuentra en fase `alpha`:

- https://github.com/google-labs-code/design.md
- https://github.com/google-labs-code/design.md/blob/main/docs/spec.md

## Convenciones de este repositorio

- El archivo raíz `DESIGN.md` contiene las reglas comunes.
- Cada formato tiene su propio `design/<formato>/DESIGN.md`.
- Las guías específicas declaran `extends: ../../DESIGN.md`.
- Los encabezados de la especificación se mantienen en inglés.
- El contenido normativo y explicativo se redacta en español.
- Los valores no validados deben marcarse con `status: draft`.

## Uso por agentes

Un agente debe cargar los archivos en este orden:

1. `DESIGN.md` de la raíz.
2. `DESIGN.md` del formato solicitado.
3. Referencias normativas aplicables.
4. Plantillas o recursos concretos del proyecto.

No debe inferir variantes del logotipo, colores institucionales ni excepciones que no estén documentadas.

## Mantenimiento

Antes de actualizar la sintaxis:

1. comprobar la versión vigente de la especificación;
2. revisar cambios incompatibles;
3. validar que los archivos siguen siendo YAML y Markdown correctos;
4. documentar la migración en el pull request.
