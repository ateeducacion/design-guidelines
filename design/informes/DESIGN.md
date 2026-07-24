---
spec: https://github.com/google-labs-code/design.md/blob/main/docs/spec.md
version: 0.1.0
status: draft
name: Informes y documentos
description: Criterios para informes en PDF y documentos editables.
extends: ../../DESIGN.md
tokens:
  page:
    size: "A4"
    margin: "20mm"
  typography:
    body-size: "10.5pt"
    line-height: "1.35"
    h1-size: "22pt"
    h2-size: "16pt"
    h3-size: "12pt"
---

# Informes y documentos

## Estructura recomendada

1. Portada institucional sobria.
2. Ficha de control: título, versión, fecha, autoría y estado.
3. Resumen ejecutivo.
4. Índice cuando el documento sea extenso.
5. Contexto, objetivos y alcance.
6. Desarrollo y resultados.
7. Conclusiones y acciones.
8. Referencias y anexos.

## Maquetación

- Usar formato A4 salvo requisito explícito.
- Mantener márgenes suficientes para impresión, anotación y encuadernación.
- Evitar encabezados y pies recargados.
- Numerar páginas, excepto la portada si la plantilla lo establece.
- No dejar títulos aislados al final de página.
- Evitar líneas viudas y huérfanas cuando el procesador lo permita.
- Usar saltos de página y estilos; nunca líneas en blanco repetidas para maquetar.

## Estilos

- Aplicar estilos semánticos de título, encabezados, cuerpo, cita, lista y pie.
- No simular encabezados únicamente con negrita y tamaño.
- Mantener numeración de secciones automática cuando sea necesaria.
- Crear tablas de contenido a partir de estilos estructurales.

## Tablas

- Usar tablas solo para datos relacionados por filas y columnas.
- No usar tablas para maquetar páginas.
- Repetir la fila de encabezado en páginas sucesivas.
- Evitar celdas combinadas cuando dificulten la lectura asistida.
- Indicar unidades en el encabezado, no repetidas en cada celda.
- Alinear números por decimal cuando sea útil.

## PDF accesible

- Exportar como PDF etiquetado cuando la herramienta lo permita.
- Definir título del documento y metadatos básicos.
- Comprobar el orden de lectura.
- Usar marcadores derivados de los encabezados.
- Añadir texto alternativo a imágenes informativas.
- Definir el idioma principal.
- No proteger el PDF de forma que impida el acceso mediante tecnologías de apoyo.
- Verificar enlaces, formularios y tablas después de exportar.

## Documento editable

- Entregar el archivo fuente cuando se requiera actualización posterior.
- No fijar contenido mediante cuadros de texto salvo necesidad justificada.
- Usar listas automáticas y referencias cruzadas.
- Evitar fuentes no disponibles en los equipos corporativos.
- Incluir instrucciones de actualización para campos automáticos complejos.

## Lista de comprobación

- [ ] El resumen ejecutivo permite comprender decisiones y resultados.
- [ ] Los estilos estructurales se usan correctamente.
- [ ] El índice y la numeración se actualizan automáticamente.
- [ ] Las tablas tienen encabezados y estructura comprensible.
- [ ] El PDF está etiquetado y tiene orden de lectura lógico.
- [ ] Los metadatos, enlaces y marcadores son correctos.
- [ ] El documento se ha revisado en pantalla y, cuando proceda, impreso.
