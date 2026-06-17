# AUT-AdjudicaciónAutomática

Flujo de Power Automate encargado de apoyar el registro automático de la adjudicación de un Trabajo Fin de Grado.

## Objetivo

Automatizar la creación inicial del expediente de TFG cuando se recibe la información de adjudicación, asociando estudiante, tutor y título del trabajo en el repositorio de SharePoint.

## Disparador

Recepción de un correo electrónico con los datos necesarios para iniciar la adjudicación.

## Entradas principales

- Correo del estudiante.
- Correo del tutor.
- Título del TFG.
- Información básica del expediente.

## Funcionamiento general

El flujo extrae los datos del correo recibido, busca la información del estudiante y del tutor en las listas correspondientes de SharePoint y crea un nuevo expediente con el estado inicial de adjudicado.

## Salidas

- Expediente creado en SharePoint.
- Asociación entre estudiante, tutor y trabajo.
- Estado inicial registrado.
- Confirmación o trazabilidad de la operación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
