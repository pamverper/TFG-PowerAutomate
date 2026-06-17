# AUT-DefensaRecepciónPropuesta

Flujo de Power Automate encargado de procesar la propuesta de planificación de defensas recibida desde el sistema externo.

## Objetivo

Registrar automáticamente en SharePoint las pruebas de defensa propuestas, a partir de la planificación generada externamente.

## Disparador

Recepción de un correo electrónico con la propuesta de defensas generada por Make.com/OpenAI.

## Entradas principales

- Propuesta de defensas.
- Expedientes.
- Fechas y horas asignadas.
- Aulas.
- Tutores y miembros de tribunal.
- Información estructurada en JSON o formato equivalente.

## Funcionamiento general

El flujo interpreta la propuesta recibida, recorre cada defensa incluida y crea los registros correspondientes en la lista de pruebas de SharePoint.

## Salidas

- Pruebas de defensa registradas.
- Confirmación automática del registro.
- Información disponible para revisión y convocatoria.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
