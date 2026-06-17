# AUT-DudasRegistro

Flujo de Power Automate encargado de registrar la respuesta generada para una consulta y gestionar su envío o escalado.

## Objetivo

Recibir la respuesta generada por el sistema de IA, registrar la consulta en SharePoint y decidir si se responde automáticamente al estudiante o si debe revisarla el coordinador.

## Disparador

Recepción de un correo o mensaje con la respuesta generada por Make.com/OpenAI.

## Entradas principales

- Correo del estudiante.
- Pregunta original.
- Respuesta generada.
- Indicador de escalado.
- Información de revisión manual, si procede.

## Funcionamiento general

El flujo interpreta la respuesta recibida. Si la consulta está cubierta por la información verificada, envía la respuesta al estudiante. Si requiere revisión, avisa al coordinador y comunica al estudiante que su consulta será revisada manualmente.

## Salidas

- Consulta registrada.
- Respuesta enviada al estudiante o aviso de revisión manual.
- Notificación al coordinador si procede.
- Trazabilidad de la consulta.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
