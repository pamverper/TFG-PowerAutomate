# AUT-CambioEstado

Flujo de Power Automate encargado de notificar cambios de estado en los expedientes de TFG.

## Objetivo

Automatizar el envío de comunicaciones cuando un expediente cambia de estado, evitando que el coordinador tenga que informar manualmente a los participantes.

## Disparador

Modificación de un elemento en la lista de expedientes de SharePoint.

## Entradas principales

- Expediente modificado.
- Estado anterior o estado actualizado.
- Estudiante asociado.
- Tutor asociado.
- Destinatarios de la notificación.

## Funcionamiento general

El flujo detecta el cambio de estado, obtiene los datos necesarios del expediente y genera una notificación automática para informar del avance del procedimiento.

## Salidas

- Correo automático de cambio de estado.
- Registro de notificación.
- Expediente con trazabilidad actualizada.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
