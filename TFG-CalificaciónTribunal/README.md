# AUT-CalificaciónTribunal

Flujo de Power Automate encargado de registrar la calificación emitida por el tribunal.

## Objetivo

Automatizar el registro de la nota del tribunal y actualizar la información del expediente correspondiente.

## Disparador

Recepción de un correo o registro con la calificación del tribunal asociada a un expediente.

## Entradas principales

- Identificador del expediente.
- Nota del tribunal.
- Datos de la defensa.
- Información del estudiante.

## Funcionamiento general

El flujo identifica el expediente, registra la calificación del tribunal y actualiza los campos necesarios en SharePoint. Cuando procede, también calcula o actualiza la nota final.

## Salidas

- Nota del tribunal registrada.
- Expediente actualizado.
- Nota final calculada o actualizada.
- Registro de la operación.

## Requisitos y adaptación

Para importar o reutilizar este flujo es necesario revisar las conexiones de Power Automate, las referencias a listas de SharePoint, los nombres de columnas, las direcciones de correo y los identificadores internos del entorno.

## Consideraciones

Este flujo forma parte de un prototipo académico de apoyo a la gestión administrativa del TFG. No sustituye el procedimiento oficial ni debe utilizarse con datos personales reales sin la adaptación y validación previa correspondiente.
[README.md](https://github.com/user-attachments/files/29058800/README.md)
