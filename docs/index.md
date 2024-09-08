# Nombre del Proyecto

## Descripción

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso Básico](#uso-básico)
- [Arquitectura](#arquitectura)
- [Contribución](#contribución)
- [Licencia](#licencia)
- [Contacto o Soporte](#contacto-o-soporte)

## Instalación


## [MKDOCS Tutorial](mkdocs-tutorial.md)

## Estructura basica para la docuemntación

*Esta estructura es flexible y se puede adaptar según las necesidades y la naturaleza del proyecto. Lo importante es cuente con estas minima estructura que se muestra a continuación.*

``` bash
docs                                    # Directorio raíz de la documentación del proyecto.
├───assets                              # Directorio que incluye todos los recursos estáticos utilizados en los archivos .md (imágenes, etc.).
│   ├───common                          # Directorio donde se incluirán recursos compartidos, como imágenes y otros elementos comunes.
│   ├───documentacion funcional         # Directorio que incluirá recursos estáticos relacionados con la documentación funcional.
│   │   ├───diagramas                   # Directorio que incluirá imágenes de diagramas relacionados con funcionalidades del proyecto.
│   │   │   └───dfd                     # Directorio que incluirá imágenes de diagramas de flujo de datos (DFD) utilizados en la documentación funcional.
│   │   └───manual de usuario           # Directorio que incluirá las imágenes utilizadas en el manual de usuario.
│   ├───documentacion tecnica           # Directorio que incluirá recursos estáticos relacionados con la documentación técnica.
│   │   ├───batchs                      # Directorio que incluirá imágenes o recursos relacionados con procesos batch.
│   │   ├───db                          # Directorio que incluirá imágenes o recursos relacionados con la documentación de la base de datos.
│   │   │   ├───procedures              # Directorio que incluirá imágenes o recursos sobre los procedimientos almacenados (procedures).
│   │   │   ├───tablas                  # Directorio que incluirá imágenes o recursos sobre las tablas de la base de datos.
│   │   │   └───vistas                  # Directorio que incluirá imágenes o recursos sobre las vistas de la base de datos.
│   │   ├───diagramas                   # Directorio que incluirá imágenes de todos los diagramas del proyecto.
│   │   │   ├───der                     # Directorio que incluirá imágenes del diagrama de entidad-relación (DER) de la base de datos.
│   │   │   └───diccionario de datos    # Directorio que incluirá imágenes del diccionario de datos.
│   │   └───tuproyecto                  # Directorio que respetará la estructura de directorios de nuestro proyecto para organizar los recursos estáticos.
│   └───stylesheets                     # Directorio donde se incluirán hojas de estilo (CSS) utilizadas en la documentación.
├───documentacion funcional             # Directorio que incluirá solo los documentos funcionales.
│   ├───diagramas                       # Directorio que incluirá diagramas en formato markdown sobre funcionalidades del proyecto.
│   │   └───dfd                         # Directorio que incluirá diagramas de flujo de datos (DFD) de la documentación funcional.
│   └───manual de usuario               # Directorio que incluirá los documentos del manual de usuario.
├───documentacion tecnica               # Directorio que incluirá toda la documentación por parte de desarrollo.
│    ├───batchs                         # Directorio que incluirá documentación sobre procesos batch de nuestro aplicativo.
│    ├───db                             # Directorio que incluirá documentación sobre nuestra(s) base(s) de datos.
│    │   ├───procedures                 # Directorio que incluirá documentación sobre los procedimientos almacenados (procedures) de nuestra base de datos.
│    │   ├───tablas                     # Directorio que incluirá documentación sobre las tablas de nuestra base de datos.
│    │   └───vistas                     # Directorio que incluirá documentación sobre las vistas de nuestra base de datos.
│    ├───diagramas                      # Directorio que incluirá documentación sobre todos los diagramas en markdown de nuestro proyecto.
│    │   ├───der                        # Directorio que incluirá el diagrama de entidad-relación (DER) de nuestra base de datos.
│    │   └───diccionario de datos       # Directorio donde se incluirá el diccionario de datos.
│    └───tuproyecto                     # Directorio que respetará la estructura de directorios de nuestro proyecto para organizar la documentación.
├───catalog-info.yml                    # Archivo que define y describe los componentes y entidades para que Backstage los consuma.
├───mkdocs.yml                          # Archivo de configuración de MkDocs que define la estructura y los estilos del sitio de documentación.

```

# Propositos de los directorios

## [Directorio batch](./documentacion%20tecnica/batchs/index.md)

## [Directorio db](./documentacion%20tecnica/db/index.md)

## [Directorio diagramas](./documentacion%20tecnica/diagramas/index.md)

## [Directorio assets](./assets/index.md)



