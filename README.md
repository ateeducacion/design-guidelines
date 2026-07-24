# Guías de diseño del Área de Tecnología Educativa

Este repositorio reúne criterios compartidos para diseñar, generar y revisar materiales del Área de Tecnología Educativa (ATE):

- informes y documentos editables;
- documentos PDF;
- presentaciones;
- sitios y páginas web;
- plantillas, componentes y recursos gráficos.

El objetivo es mantener una identidad coherente, accesible y reconocible, tanto cuando el trabajo lo realiza una persona como cuando participa un agente de inteligencia artificial.

> [!IMPORTANT]
> Este repositorio no sustituye al Manual de Identidad Corporativa Gráfica del Gobierno de Canarias ni a la normativa aplicable. Ante cualquier contradicción, prevalecen las fuentes oficiales.

## Estructura

```text
.
├── DESIGN.md
├── design/
│   ├── informes/DESIGN.md
│   ├── presentaciones/DESIGN.md
│   └── web/DESIGN.md
├── skills/
│   ├── auditar-diseno/SKILL.md
│   ├── crear-informe/SKILL.md
│   ├── crear-presentacion/SKILL.md
│   └── crear-sitio-web/SKILL.md
├── references/
│   ├── ACCESIBILIDAD.md
│   ├── DESIGN-MD.md
│   └── FUENTES.md
├── assets/README.md
├── templates/README.md
└── CONTRIBUTING.md
```

## Cómo usar este repositorio

### Para personas

1. Lee [`DESIGN.md`](DESIGN.md), que contiene las reglas comunes.
2. Consulta el `DESIGN.md` específico del tipo de material.
3. Revisa las referencias normativas y de accesibilidad.
4. Parte de una plantilla aprobada cuando exista.
5. Ejecuta la lista de comprobación antes de publicar.

### Para agentes de IA

Los directorios de `skills/` siguen el formato abierto de Agent Skills. Cada skill indica qué documentos debe cargar, qué decisiones puede tomar y qué comprobaciones debe realizar.

Los archivos `DESIGN.md` usan el formato propuesto por Google para describir identidades visuales mediante tokens en YAML y criterios de aplicación en Markdown. La especificación está en fase `alpha`; las actualizaciones deberán revisar posibles cambios incompatibles.

Los encabezados normativos de los archivos `DESIGN.md` se mantienen en inglés para conservar la compatibilidad con su especificación y sus herramientas. El contenido y las instrucciones del repositorio están redactados en español.

## Orden de prioridad

Las decisiones se resolverán en este orden:

1. normativa vigente y requisitos legales;
2. Manual de Identidad Corporativa Gráfica del Gobierno de Canarias e instrucciones posteriores;
3. requisitos de accesibilidad;
4. [`DESIGN.md`](DESIGN.md) común;
5. `DESIGN.md` específico del formato;
6. plantilla aprobada para el proyecto;
7. decisión puntual documentada.

## Principios

- **Claridad:** cada pieza debe facilitar la comprensión y la toma de decisiones.
- **Accesibilidad:** no se considerará terminada una pieza que excluya a parte de su audiencia.
- **Consistencia:** los mismos elementos y patrones deben conservar significado y comportamiento.
- **Jerarquía:** títulos, datos, llamadas a la acción y conclusiones deben distinguirse sin depender solo del color.
- **Sobriedad:** se evitarán elementos decorativos que compitan con el contenido.
- **Trazabilidad:** las excepciones y decisiones relevantes deben quedar documentadas.
- **Reutilización:** se priorizarán componentes y plantillas mantenibles frente a soluciones aisladas.

## Estado del repositorio

Esta es una base inicial. Los valores tomados del manual oficial se identifican como tales; las reglas propias de ATE deberán validarse con ejemplos reales antes de considerarse estables.

## Referencias principales

- [Especificación de DESIGN.md](https://github.com/google-labs-code/design.md/blob/main/docs/spec.md)
- [Especificación de Agent Skills](https://agentskills.io/specification)
- [Manual de Identidad Corporativa Gráfica del Gobierno de Canarias](https://www.gobiernodecanarias.org/identidadgrafica/)
- [Zona oficial de descargas de identidad gráfica](https://www.gobiernodecanarias.org/identidadgrafica/descargas/)
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/)
- [Real Decreto 1112/2018](https://www.boe.es/eli/es/rd/2018/09/07/1112)

Consulta [`references/FUENTES.md`](references/FUENTES.md) para ver el inventario completo y su prioridad.

## Contribuciones

Las propuestas deben realizarse mediante pull request y explicar:

- el problema que resuelven;
- los formatos afectados;
- la fuente normativa o el criterio de diseño utilizado;
- el impacto en accesibilidad;
- ejemplos visuales cuando el cambio no pueda evaluarse solo con texto.

Consulta [`CONTRIBUTING.md`](CONTRIBUTING.md) antes de modificar las guías.
