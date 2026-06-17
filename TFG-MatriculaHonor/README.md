# AUT-MatriculaHonor

Flujo de Power Automate encargado de apoyar la asignación de Matrículas de Honor.

## Objetivo

Automatizar la revisión de candidatos a Matrícula de Honor y generar las comunicaciones necesarias según el resultado del proceso.

## Disparador

Ejecución manual desde Power Apps o activación asociada al cierre de calificaciones.

## Entradas principales

- Expedientes evaluados.
- Notas finales.
- Número máximo de Matrículas de Honor disponibles.
- Criterios de selección.
- Posibles empates.

## Funcionamiento general

El flujo consulta los expedientes candidatos, aplica las condiciones definidas y determina si puede asignarse Matrícula de Honor automáticamente o si existe alguna situación que requiere revisión, como falta de candidatos o empate en el corte.

## Salidas

- Matrículas de Honor asignadas cuando procede.
- Aviso por falta de candidatos.
- Aviso por empate o conflicto.
- Confirmación del resultado.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
