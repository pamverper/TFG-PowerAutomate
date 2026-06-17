# AUT-DefensaRestriccionesRegistro

Flujo de Power Automate encargado de registrar restricciones de disponibilidad para la organización de defensas.

## Objetivo

Automatizar el registro de las restricciones comunicadas por los participantes, de forma que puedan utilizarse en la planificación de defensas.

## Disparador

Envío de formulario o recepción de datos de disponibilidad.

## Entradas principales

- Profesor o participante.
- Fechas no disponibles.
- Franjas horarias restringidas.
- Convocatoria asociada.
- Observaciones.

## Funcionamiento general

El flujo recibe la información de disponibilidad, identifica al participante y crea un registro en la lista de restricciones de SharePoint.

## Salidas

- Restricción registrada en SharePoint.
- Información disponible para planificación.
- Confirmación de registro, si procede.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
