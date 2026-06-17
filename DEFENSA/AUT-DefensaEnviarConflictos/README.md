# AUT-DefensaEnviarConflictos

Flujo de Power Automate encargado de comunicar conflictos detectados durante la planificación de defensas.

## Objetivo

Informar al coordinador o a los participantes implicados cuando se detectan conflictos de disponibilidad, asignación, tribunal, horario o aula.

## Disparador

Detección de conflictos durante la preparación o revisión de la propuesta de defensas.

## Entradas principales

- Propuesta de defensas.
- Restricciones de disponibilidad.
- Datos de tutores y tribunales.
- Fechas, horas y aulas asignadas.
- Conflictos detectados.

## Funcionamiento general

El flujo recopila los conflictos identificados y genera una comunicación para facilitar su revisión antes de enviar convocatorias definitivas.

## Salidas

- Correo o aviso con conflictos detectados.
- Información preparada para revisión manual.
- Apoyo a la corrección de la planificación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.

