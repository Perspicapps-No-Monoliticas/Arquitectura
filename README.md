# Entrega 001  Grupo 1: Diseño y Arquitectura de dominio
## Instrucciones de uso
 * Para intalar desde el ambiente local
   * Instalar Java 8 o superior y agregar el JDK en la variable de entorno PATH
   * Instalar la extensión [Context Mapper](https://marketplace.visualstudio.com/items?itemName=contextmapper.context-mapper-vscode-extension) para Visual Studio Code
   * Instalar  [Graphviz](https://www.graphviz.org/)
   * Abrir Visual Studio Code en la raiz del proyecto.
   * Para generar los diagarmas abrir el .cml deaseado
   * Presionar CTRL+Shit + p y buscar "Generate Graphical Context Map"
   * Seleccionar el formato deseado PNG, SVG o DOT
   * El diagrama será generado.
  * Para usar desde gitPod
       * Ingrese a https://perspicapps-arquitectur-zsdhjg07hqu.ws-us117.gitpod.io
       * Seleccione su cuenta de GitHub junto con su repositorio.
       * Una vez en la consola de gitPod
       * Para generar los diagarmas abrir el .cml deaseado
       * Presionar CTRL+Shit + p y buscar "Generate Graphical Context Map"
       * Seleccionar el formato deseado PNG, SVG o DOT
       * El diagrama será generado.
## Estructura del proyecto

     📂Perspicapps-No-Monoliticas/ 
     ├── 📂src/main                    # Código fuente del proyecto
     │   ├── 📂cml/                    # Archivos que representan los modelos de dominio en diferentes estados
     │   │   ├── 📄 asIs.cml           # Representación del modelo de dominio en el estado actual (As-Is)
     │   │   ├── 📄 domains.cml        # Definición de entidades, relaciones y reglas de negocio del sistema
     │   │   └── 📄 toBe.cml           # Representación del modelo de dominio en el estado futuro deseado (To-Be)
     ├── 📂images/                     # Directorio para almacenar imágenes y diagramas relacionados con el proyecto
     |   ├── 📄 asIsEventStorming.png  # Diagrama de Event Storming que representa el modelo de dominio "As-Is"
     |   ├── 📄 asIs_ContextMap.png    # Diagrama de Context Map que representa los límites del contexto "As-Is"
     |   ├── 📄 toBeEventStorming.png  # Diagrama de Event Storming que representa el modelo de dominio "To-Be"
     |   └── 📄 toBe_ContextMap.png    # Diagrama de Context Map que representa los límites del contexto "To-Be"
     ├── 📄 .gitpod.yml                # Configuración del entorno de desarrollo en Gitpod
     └── 📂README.md                   # Documentación principal del proyecto 

## Donde encontrar los fragmentos de código para cada item de calificación
### Documentación de dominios y sub-dominios
 * El alumno identificó y documentó correctamente todos los dominios y sub-dominios usando el DSL de ContextMapper
     * [src/main/cml/domains.cml](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/src/main/cml/domains.cml)
     ![image](https://github.com/user-attachments/assets/d44e7efb-2612-48b6-b361-7a4136968b26)

 * El alumno identificó y plasmó el vision statement para todos los dominios usando el DSL de ContextMapper
     * [src/main/cml/domains.cml](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/src/main/cml/domains.cml)
     * ![image](https://github.com/user-attachments/assets/2025b443-05aa-4670-b11e-d6d8fd18767b)

 * El alumno identificó y documentó correctamente los tipos de sub-dominios usando el DSL de ContextMapper.
     * [src/main/cml/domains.cml](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/src/main/cml/domains.cml)
     * ![image](https://github.com/user-attachments/assets/a75ba21a-e9c5-4834-b539-016632d99085)

### Documentación del lenguaje ubicuo
 * El alumno identificó y documentó correctamente todos los actores, eventos, comandos, modelo de lectura, sistemas externos y definiciones relevantes para el flujo de “anonimización, ingestión y enriquecimiento de datos” S-IS usando el método EventStorming.
    * [images/asIsEventStorming.png](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/images/asIsEventStorming.png)
    * ![image](https://github.com/user-attachments/assets/60b4dd4f-5318-4213-86ff-be27ad843fe5)
 * El alumno identificó y documentó correctamente todos los actores, eventos, comandos, modelo de lectura, sistemas externos y definiciones relevantes para el flujo de “anonimización, ingestión y enriquecimiento de datos” TO-BE usando el método EventStorming.
    *  [images/toBeEventStorming.png](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/images/toBeEventStorming.png)
    *  ![image](https://github.com/user-attachments/assets/8db044fc-62f4-49eb-92f5-8b5faa4dcb44)

### Documentación de contextos acotados
 * El alumno identificó y documentó correctamente todos los contextos usando el DSL del ContextMapper para el AS-IS
    *   [src/main/cml/asIs.cml](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/src/main/cml/asIs.cml)
    *   ![image](https://github.com/user-attachments/assets/63fd22a0-d54a-40ce-aa55-17d2ed8b7e76)
 * El alumno identificó y documentó correctamente todos los las relaciones y tipos de integración entre contextos usando el DSL del ContextMapper para el AS-IS
    *   [src/main/cml/asIs.cml](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/src/main/cml/asIs.cml)
    *   ![image](https://github.com/user-attachments/assets/029f498d-4b0d-47b0-951a-5c530b0a1313)
*   El alumno identificó y documentó correctamente todos los contextos usando el DSL del ContextMapper para el TO-BE   
    * [src/main/cml/toBe.cml](https://github.com/Perspicapps-No-Monoliticas/Arquitectura/blob/main/src/main/cml/toBe.cml)
    * ![image](https://github.com/user-attachments/assets/8962a11d-f3dd-4fea-8b66-f2f3cf9879a8)
*   El alumno identificó y documentó correctamente todos los las relaciones y tipos de integración entre contextos usando el DSL del ContextMapper para el TO-BE
    * ![image](https://github.com/user-attachments/assets/589545f1-8e00-47f0-9e45-31b7262cd818)
      
