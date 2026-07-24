---
spec: https://github.com/google-labs-code/design.md/blob/main/docs/spec.md
version: 0.1.0
status: draft
name: Sitios y páginas web
description: Criterios para servicios, sitios y contenidos web de ATE.
extends: ../../DESIGN.md
tokens:
  layout:
    content-max-width: "1200px"
    reading-max-width: "72ch"
  breakpoints:
    small: "576px"
    medium: "768px"
    large: "992px"
---

# Sitios y páginas web

## Arquitectura y navegación

- Organizar el contenido según las tareas de la audiencia, no según la estructura interna del organismo.
- Usar nombres de sección concretos y predecibles.
- Mantener navegación, cabecera y pie consistentes.
- Incluir migas de pan cuando la profundidad lo justifique.
- Evitar páginas duplicadas y enlaces a versiones obsoletas.
- Proporcionar una búsqueda útil cuando el volumen de contenido lo requiera.

## Diseño adaptable

- Diseñar primero para pantallas pequeñas y ampliar progresivamente.
- Evitar desplazamiento horizontal en anchos habituales.
- Mantener objetivos táctiles suficientemente grandes y separados.
- No ocultar información esencial en la versión móvil.
- Probar orientación vertical y horizontal.

## Contenido

- Usar un único `h1` descriptivo por página.
- Mantener una jerarquía de encabezados lógica, sin saltos por motivos visuales.
- Limitar el ancho de lectura de textos largos.
- Escribir enlaces descriptivos; evitar “aquí” o URLs visibles como texto principal.
- Indicar tipo y tamaño de los archivos descargables.
- Mostrar fecha de actualización cuando sea relevante.

## Formularios

- Asociar cada campo con una etiqueta visible.
- Explicar formato y obligatoriedad antes de que se produzca el error.
- Mostrar errores junto al campo y un resumen al inicio cuando proceda.
- Conservar los datos introducidos tras un error.
- No bloquear pegar contraseñas ni usar gestores de contraseñas.
- Confirmar el resultado y explicar los siguientes pasos.

## Interacción

- Todas las funciones deben ser operables con teclado.
- El foco debe ser visible y seguir un orden lógico.
- No iniciar audio o vídeo automáticamente.
- Permitir pausar contenido en movimiento.
- Evitar cambios inesperados de contexto al seleccionar o enfocar controles.
- Usar componentes nativos antes de crear controles personalizados.

## Rendimiento y resiliencia

- Optimizar imágenes y servir formatos adecuados.
- Cargar solo recursos necesarios.
- Evitar dependencias de terceros sin justificación, revisión de privacidad y plan de mantenimiento.
- Mantener la funcionalidad principal con conexiones lentas y errores parciales.
- Definir páginas de error útiles y con vías de recuperación.

## Accesibilidad y cumplimiento

- Tomar WCAG 2.2 como referencia técnica, sin rebajar las obligaciones legales aplicables.
- Verificar al menos navegación por teclado, foco, contraste, zoom, reflujo, nombres accesibles y mensajes de error.
- Usar HTML semántico y ARIA solo cuando sea necesario.
- Publicar una declaración de accesibilidad cuando sea exigible.
- No considerar suficiente una puntuación automática: combinar herramientas y revisión manual.

## Privacidad y seguridad

- Recoger solo los datos necesarios.
- Explicar finalidad, conservación y destinatarios de forma comprensible.
- Evitar rastreadores y cookies no esenciales por defecto.
- No incluir datos personales en URLs, registros públicos o analítica.
- Aplicar actualizaciones y revisar dependencias periódicamente.

## Lista de comprobación

- [ ] La página responde a una tarea clara de la audiencia.
- [ ] La jerarquía de encabezados es correcta.
- [ ] Todas las funciones operan con teclado y foco visible.
- [ ] El contenido funciona con zoom y reflujo.
- [ ] Formularios y errores son comprensibles y recuperables.
- [ ] Imágenes y recursos están optimizados.
- [ ] Se han revisado privacidad, seguridad y dependencias.
- [ ] Las comprobaciones automáticas se han complementado con revisión manual.
