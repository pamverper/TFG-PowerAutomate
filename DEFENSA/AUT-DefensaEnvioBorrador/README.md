# AUT-DefensaEnvioBorrador

Flujo de Power Automate encargado de enviar borradores de convocatoria de defensa.

## Objetivo

Enviar comunicaciones provisionales con la propuesta de defensa para que puedan revisarse antes de emitir la convocatoria oficial.

## Disparador

Acción manual desde Power Apps mediante el botón de envío de borradores.

## Entradas principales

- Defensas pendientes de convocatoria.
- Estudiantes.
- Tutores.
- Miembros de tribunal.
- Fecha, hora y aula propuestas.

## Funcionamiento general

El flujo obtiene las defensas pendientes, prepara un correo provisional para cada una y lo envía a los destinatarios correspondientes como borrador de convocatoria.

## Salidas

- Correos de borrador de convocatoria.
- Registro de envío.
- Pruebas marcadas como borrador enviado, si procede.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
