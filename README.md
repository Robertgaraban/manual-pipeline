# Pipeline documental para manuales de formación

**Tipo:** herramienta propia.

**Estado:** en uso interno y evolución continua — noviembre de 2026.

Este pipeline convierte contenido en Markdown en manuales PDF y DOCX, con versionado, trazabilidad de cada entrega y extracción de texto —con OCR cuando es necesario— de los documentos de origen. Lo diseñé para producir y mantener material técnico de formación mediante un proceso reproducible.

## Problema

Un manual técnico debe mantener alineados el programa, las fuentes, las explicaciones, las figuras, la bibliografía y la presentación editorial. Cuando cada revisión se realiza manualmente, es fácil perder trazabilidad, introducir diferencias entre formatos o repetir trabajo ya resuelto.

## Flujo

1. Se organizan las fuentes autorizadas y el contenido base.
2. Se extrae texto de PDF y DOCX; el OCR se utiliza cuando el documento lo requiere.
3. El contenido se estructura en Markdown separado de las plantillas.
4. Se generan PDF y DOCX desde la misma base.
5. Cada salida conserva versión, fuentes utilizadas y resultado de los controles.
6. La revisión editorial y técnica decide si la entrega se acepta.

## Decisiones de diseño

- Separar fuentes, contenido, plantillas, material gráfico y salidas.
- Mantener una única base editorial para reducir diferencias entre PDF y DOCX.
- Automatizar lo repetible y conservar revisión humana para contenido y presentación.
- Registrar versiones y comprobaciones para poder reproducir una entrega.
- Mantener privados el catálogo, los manuales y los documentos de origen.

## Qué demuestra esta ficha

- La arquitectura de un proceso documental reproducible.
- La separación entre contenido, presentación y evidencia de origen.
- El uso de Markdown, scripts, Pandoc y OCR dentro de un flujo controlado.
- La aplicación de criterios de aceptación a documentación técnica.

## Qué no publica

Nombres ni códigos de cursos, homologaciones, centros de formación, número de manuales, documentos de origen, contenido de los manuales, infraestructura ni código privado. Esta ficha tampoco ofrece acceso al código.

## Mi papel

Conceptualicé el flujo, definí la arquitectura y los criterios de aceptación, organicé la ejecución con agentes especializados y revisé las entregas.

## Autor

Robert Garabán — Consultor de IA aplicada y Product Owner.

[Perfil profesional](https://www.linkedin.com/in/robertgaraban/)
