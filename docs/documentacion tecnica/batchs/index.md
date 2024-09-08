# Documentación de Jobs en el Directorio `batchs`

En este directorio se encuentran los archivos Markdown correspondientes a los jobs que se ejecutan en el aplicativo. Cada archivo debe especificar la siguiente información:

## Estructura del Archivo Markdown

### 1. Aplicación

Indica si la aplicación corre en `Bacs` o `BANCO_HIPOTECRIO`.

### 2. Grupo

Especifica el grupo al que pertenece el job.

### 3. Nombre del Job

Especifica el nombre del job.

### 4. Variable

Lista las variables relevantes para el job.

### 5. Descripción General

Ofrece una descripción general del job, explicando su propósito y funcionamiento.

---

## Ejemplo de Archivo Markdown

``` markdown
# Documentación del Job: `NombreDelJob`

## Aplicación
`Bacs` (Genialo `BANCO_HIPOTECRIO`)

## Grupo
`GrupoEjemplo`

## Nombre del Job
`NombreDelJob`

## Variable
- `Variable1`: Descripción de la variable.
- `Variable2`: Descripción de la variable.

## Descripción General
Este job realiza [breve descripción de las tareas y funciones del job]. Se encarga de [detalles sobre el propósito del job y cómo interactúa con otros componentes o sistemas].
```
