# AUT-CalificaciónDisponible

Flujo de Power Automate encargado de notificar al estudiante que la calificación del TFG está disponible.

## Objetivo

Automatizar el envío de la comunicación al estudiante cuando la calificación puede ser consultada.

## Disparador

Cambio de estado o actualización del expediente en SharePoint indicando que la calificación está disponible.

## Entradas principales

- Expediente.
- Estudiante.
- Nota o estado de calificación.
- Correo del estudiante.

## Funcionamiento general

El flujo detecta que la calificación del expediente ya se encuentra disponible y envía un correo informativo al estudiante.

## Salidas

- Correo automático al estudiante.
- Registro de la notificación enviada.
- Trazabilidad de la comunicación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
