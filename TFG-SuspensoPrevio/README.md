# AUT-SuspensoPrevio

Flujo de Power Automate encargado de gestionar comunicaciones asociadas a situaciones de suspenso previo.

## Objetivo

Automatizar la generación de avisos y convocatorias relacionadas con la audiencia o revisión previa cuando un expediente se encuentra en situación de suspenso.

## Disparador

Actualización de calificación o cambio de estado que identifica una situación de suspenso previo.

## Entradas principales

- Expediente.
- Estudiante.
- Calificación.
- Datos de la defensa.
- Información necesaria para la audiencia.

## Funcionamiento general

El flujo identifica el expediente afectado, prepara la comunicación correspondiente y envía el aviso al estudiante y/o a los responsables implicados.

## Salidas

- Correo automático de convocatoria o aviso.
- Expediente actualizado.
- Registro de la comunicación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
