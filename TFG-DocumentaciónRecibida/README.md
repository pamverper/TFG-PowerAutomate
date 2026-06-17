# AUT-DocumentaciónRecibida

Flujo de Power Automate encargado de registrar la documentación recibida asociada a un expediente de TFG.

## Objetivo

Automatizar el registro de documentos recibidos y actualizar el expediente correspondiente en SharePoint.

## Disparador

Recepción de un correo electrónico con documentación adjunta o información asociada a un expediente.

## Entradas principales

- Identificador del expediente.
- Archivos adjuntos.
- Tipo de documentación recibida.
- Remitente del correo.

## Funcionamiento general

El flujo identifica el expediente, registra la documentación en la lista correspondiente, actualiza el estado o los campos relacionados y envía una confirmación automática.

## Salidas

- Documento registrado.
- Expediente actualizado.
- Correo automático de confirmación.
- Trazabilidad de la recepción.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
