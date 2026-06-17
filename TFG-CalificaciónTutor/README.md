# AUT-CalificaciónTutor

Flujo de Power Automate encargado de registrar la calificación aportada por el tutor del TFG.

## Objetivo

Automatizar la incorporación de la nota del tutor al expediente del estudiante.

## Disparador

Recepción o registro de la calificación del tutor.

## Entradas principales

- Identificador del expediente.
- Nota del tutor.
- Datos del estudiante.
- Datos del tutor.

## Funcionamiento general

El flujo localiza el expediente correspondiente y actualiza el campo de calificación del tutor en SharePoint. Esta información se utiliza posteriormente en el cálculo o revisión de la calificación final.

## Salidas

- Nota del tutor registrada.
- Expediente actualizado.
- Trazabilidad de la actualización.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
