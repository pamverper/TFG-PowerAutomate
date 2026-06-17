# AUT-DudasReenvio

Flujo de Power Automate encargado de reenviar consultas de estudiantes para su tratamiento mediante el sistema de apoyo con inteligencia artificial.

## Objetivo

Estructurar la consulta recibida y enviarla al correo puente o escenario externo encargado de procesarla mediante Make.com y OpenAI.

## Disparador

Recepción de un correo electrónico con una duda o consulta de un estudiante.

## Entradas principales

- Correo del estudiante.
- Texto de la pregunta.
- Asunto del mensaje.
- Información de contexto disponible.

## Funcionamiento general

El flujo extrae la consulta del correo recibido, la transforma en un formato estructurado y la reenvía al sistema externo de procesamiento.

## Salidas

- Correo puente con la consulta estructurada.
- Consulta preparada para procesamiento mediante IA.
- Registro inicial de la consulta.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
