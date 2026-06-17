# AUT-DefensaConsolidaciónEnvio

Flujo de Power Automate encargado de consolidar la información necesaria para preparar la planificación de defensas.

## Objetivo

Recopilar los datos de expedientes, tutores, tribunales, restricciones y calendario para enviarlos en formato estructurado al sistema encargado de generar una propuesta de planificación.

## Disparador

Acción manual desde Power Apps mediante el botón de preparación de planificación de defensas.

## Entradas principales

- Expedientes inscritos o pendientes de defensa.
- Tutores.
- Posibles miembros de tribunal.
- Restricciones de disponibilidad.
- Calendario de la convocatoria.
- Aulas disponibles.

## Funcionamiento general

El flujo consulta las listas de SharePoint, agrupa la información relevante y genera un JSON o correo puente con los datos consolidados. Esta información puede ser procesada posteriormente en Make.com y OpenAI.

## Salidas

- Datos consolidados en formato estructurado.
- Correo puente para procesamiento externo.
- Base de entrada para la propuesta de planificación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
