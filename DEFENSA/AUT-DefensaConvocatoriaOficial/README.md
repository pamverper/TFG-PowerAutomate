# AUT-DefensaConvocatoriaOficial

Flujo de Power Automate encargado de enviar la convocatoria oficial de defensa.

## Objetivo

Automatizar el envío de la convocatoria oficial a los participantes de una defensa y actualizar el estado de la prueba correspondiente.

## Disparador

Acción manual desde Power Apps sobre una defensa concreta.

## Entradas principales

- Expediente.
- Estudiante.
- Tutor.
- Miembros del tribunal.
- Fecha y hora de defensa.
- Aula.
- Datos de la convocatoria.

## Funcionamiento general

El flujo obtiene la información de la prueba de defensa, genera el correo oficial de convocatoria y lo envía a los destinatarios correspondientes. Después actualiza la prueba para reflejar que la convocatoria oficial ha sido enviada.

## Salidas

- Correo oficial de convocatoria.
- Prueba de defensa actualizada.
- Registro de envío.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
