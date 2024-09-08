# Documentación de la Base de Datos

En este documento se detalla la estructura y los elementos importantes de la base de datos utilizada por la aplicación. Cada sección debe proporcionar información específica para asegurar una comprensión clara de la base de datos.

## Estructura de Carpetas

- **`tablas/`**: Contiene archivos Markdown que documentan todas las tablas de la base de datos.
- **`vistas/`**: Contiene archivos Markdown que documentan todas las vistas de la base de datos.
- **`procedures/`**: Contiene archivos Markdown que documentan todos los procedimientos almacenados y triggers.

## Estructura del Documento

### 1. Descripción General

Proporciona una visión general de la base de datos.

### 2. Tablas

Lista y describe cada tabla en la base de datos. La documentación de cada tabla se encuentra en la carpeta `tablas/`.

- **Nombre de la Tabla**: `NombreDeLaTabla.md`
  - **Descripción**: Breve descripción de la tabla y su propósito.
  - **Columnas**:
    - `NombreColumna1` (Tipo de Dato): Descripción de la columna.
    - `NombreColumna2` (Tipo de Dato): Descripción de la columna.
  - **Llaves Primarias**: Lista de las columnas que forman la clave primaria.
  - **Llaves Foráneas**: Detalles sobre las claves foráneas y las tablas relacionadas.

### Índices

Detalla los índices creados en la base de datos. La documentación sobre índices debe estar incluida en los archivos de tabla en la carpeta `tablas/` si se documentan por separado.

- **Nombre del Índice**: `NombreDelIndice`
  - **Tabla Asociada**: `NombreDeLaTabla`
  - **Columnas**: Lista de columnas incluidas en el índice.
  - **Tipo de Índice**: (Ej. Índice Único, Índice Compuesto, etc.)

### 3. Vistas

Describe las vistas creadas en la base de datos. La documentación de cada vista se encuentra en la carpeta `vistas/`.

- **Nombre de la Vista**: `NombreDeLaVista.md`
  - **Descripción**: Breve descripción de la vista y su propósito.
  - **Consulta SQL**: Consulta SQL que define la vista.

### 4. Procedimientos Almacenados y Triggers

Proporciona información sobre los procedimientos almacenados y triggers. La documentación de cada uno se encuentra en la carpeta `procedures/`.

- **Nombre del Procedimiento**: `NombreDelProcedimiento.md` (o `NombreDelTrigger.md`)
  - **Descripción**: Breve descripción de lo que hace el procedimiento o trigger.
  - **Parámetros**: Lista de parámetros, si los hay.
  - **Consulta SQL**: Consulta SQL que define el procedimiento o trigger.

---

## Ejemplo de Documentación para Cada Carpeta

### `tablas/Elementos.md`

``` markdown
# Documentación de la Tabla: `Elementos`

## Descripción
Contiene información sobre los elementos de la aplicación.

## Columnas
- `idElemento` (INT): Identificador único del cliente.
- `desElemento` (VARCHAR): Nombre del cliente.
- `fechaAlta` (DATE): Fecha de nacimiento del cliente.

## Llaves Primarias
- `idElemento`

## Llaves Foráneas
- Ninguna.
```
