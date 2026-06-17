# AUT-AutorizaciónIngles

Flujo de Power Automate encargado de gestionar solicitudes de autorización para realizar la defensa del TFG en inglés.

## Objetivo

Registrar la solicitud de defensa en inglés asociada a un expediente y dejar constancia de dicha petición en el sistema.

## Disparador

Recepción de un correo electrónico con la solicitud de autorización.

## Entradas principales

- Identificador del expediente.
- Correo del estudiante.
- Información de la solicitud.
- Observaciones asociadas a la defensa en inglés.

## Funcionamiento general

El flujo identifica el expediente correspondiente, actualiza la información del registro en SharePoint y envía una confirmación automática al estudiante o al remitente de la solicitud.

## Salidas

- Expediente actualizado.
- Observación o marca asociada a la defensa en inglés.
- Correo automático de confirmación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
