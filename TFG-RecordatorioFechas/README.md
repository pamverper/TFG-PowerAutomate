# AUT-RecordatorioFechas

Flujo de Power Automate encargado de enviar recordatorios automáticos sobre fechas relevantes del procedimiento de TFG.

## Objetivo

Reducir el seguimiento manual de plazos mediante el envío automático de avisos relacionados con entregas, inscripción, memoria, presentación u otras fechas relevantes.

## Disparador

Ejecución programada según calendario o revisión periódica de fechas almacenadas en SharePoint.

## Entradas principales

- Calendario de convocatorias.
- Fechas límite.
- Expedientes afectados.
- Estudiantes y tutores destinatarios.

## Funcionamiento general

El flujo consulta las fechas registradas, comprueba qué avisos deben enviarse y genera los correos correspondientes a los participantes afectados.

## Salidas

- Correos automáticos de recordatorio.
- Registro de notificaciones enviadas.
- Apoyo al seguimiento de plazos.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
