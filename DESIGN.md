---
spec: https://github.com/google-labs-code/design.md/blob/main/docs/spec.md
version: 0.1.0
status: draft
name: Guías de diseño de ATE
description: Reglas comunes para documentos, presentaciones y productos web del Área de Tecnología Educativa.
tokens:
  color:
    canarias-blue: "#0C2C84"
    canarias-yellow: "#FFCC00"
    link: "#0768AC"
    text: "#1F2937"
    muted: "#5F6B7A"
    background: "#FFFFFF"
    surface: "#F5F7FA"
    border: "#D7DEE7"
    success: "#237A3B"
    warning: "#8A5A00"
    danger: "#B42318"
  typography:
    sans: "Arial, Helvetica, sans-serif"
    serif: "Georgia, 'Times New Roman', serif"
  spacing:
    xs: "4px"
    sm: "8px"
    md: "16px"
    lg: "24px"
    xl: "32px"
  radius:
    sm: "4px"
    md: "8px"
---

# Sistema de diseño común

## Alcance

Estas reglas se aplican a informes, PDF, documentos Word, presentaciones y páginas web de ATE. Los archivos específicos de cada formato pueden ampliar estas reglas, pero no contradecirlas.

## Identidad institucional

- Usar únicamente versiones oficiales del símbolo, logotipo y firmas del Gobierno de Canarias.
- No redibujar, deformar, recolorear ni reconstruir logotipos.
- Mantener el área de respeto y los tamaños mínimos establecidos en el manual oficial.
- No usar el amarillo institucional para texto normal sobre blanco.
- No presentar un material interno como publicación institucional definitiva sin la validación correspondiente.

Los valores de color incluidos en este archivo son una base operativa. Antes de producir plantillas definitivas deben contrastarse con los archivos maestros y el manual oficial vigente.

## Color

- Usar el azul institucional como color principal y el amarillo como acento.
- Reservar los colores semánticos para estados: éxito, aviso y error.
- No transmitir información exclusivamente mediante color.
- Mantener una relación de contraste mínima de 4.5:1 para texto normal y 3:1 para texto grande y componentes gráficos esenciales.
- Verificar el contraste sobre el fondo real, incluidas imágenes, degradados y transparencias.

## Tipografía

- Priorizar familias disponibles de forma estable en los entornos de destino.
- Usar una sola familia principal y, como máximo, una secundaria justificada.
- Evitar texto justificado, mayúsculas sostenidas en párrafos y bloques largos en cursiva.
- Mantener una jerarquía limitada y coherente de títulos, subtítulos, cuerpo, notas y pies.
- No reducir el tamaño del texto para encajar contenido que debería editarse o dividirse.

## Lenguaje y contenido

- Escribir en español claro, directo e inclusivo.
- Explicar siglas en su primera aparición.
- Preferir títulos informativos frente a títulos genéricos.
- Presentar primero las conclusiones o acciones cuando la audiencia las necesite para decidir.
- Evitar párrafos extensos, tecnicismos innecesarios y duplicidades.
- Usar fechas completas cuando pueda existir ambigüedad.

## Imágenes e iconos

- Usar recursos con licencia compatible y conservar la atribución cuando proceda.
- Incluir texto alternativo útil para imágenes informativas.
- Marcar como decorativos los recursos que no aporten información.
- Evitar iconos sin etiqueta cuando su significado no sea universal.
- No incluir texto importante dentro de imágenes si puede representarse como texto real.

## Datos y gráficos

- Titular los gráficos con la conclusión principal, no solo con el nombre de la variable.
- Incluir fuente, periodo, unidad y universo de los datos.
- Usar etiquetas directas cuando reduzcan la dependencia de leyendas.
- Evitar gráficos tridimensionales y efectos que distorsionen proporciones.
- Proporcionar una tabla o descripción equivalente cuando sea necesaria para la accesibilidad.

## Componentes y patrones

- Los enlaces deben distinguirse del texto que los rodea y describir su destino.
- Los avisos deben incluir un título y no depender solo del color o de un icono.
- Las tablas deben tener encabezados claros, unidades explícitas y estructura sencilla.
- Las llamadas a la acción deben usar verbos concretos.
- Los elementos repetidos deben conservar posición, nombre y comportamiento.

## Lista de comprobación común

- [ ] La identidad institucional procede de archivos oficiales.
- [ ] La jerarquía visual permite localizar lo importante rápidamente.
- [ ] El contraste se ha verificado.
- [ ] El contenido no depende solo del color, la posición o la forma.
- [ ] Las imágenes tienen tratamiento de accesibilidad adecuado.
- [ ] Los datos indican fuente, fecha y unidad.
- [ ] Los enlaces y llamadas a la acción describen su propósito.
- [ ] No hay texto cortado, solapado ni excesivamente reducido.
- [ ] Se ha revisado ortografía, lenguaje claro y consistencia terminológica.
- [ ] Las excepciones están documentadas.
