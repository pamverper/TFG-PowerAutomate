# AUT-BajaMutuoAcuerdo

Flujo de Power Automate encargado de tramitar la baja de una adjudicación por mutuo acuerdo entre estudiante y tutor.

## Objetivo

Automatizar el registro de la baja del expediente cuando estudiante y tutor comunican la finalización de la adjudicación por mutuo acuerdo.

## Disparador

Recepción de un correo electrónico con la solicitud de baja.

## Entradas principales

- Identificador del expediente.
- Datos del estudiante.
- Datos del tutor.
- Motivo o texto de la solicitud.

## Funcionamiento general

El flujo localiza el expediente afectado, actualiza su estado en SharePoint y registra la información necesaria para dejar constancia de la baja.

## Salidas

- Expediente actualizado.
- Estado modificado a cerrado o equivalente.
- Notificación automática de confirmación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
