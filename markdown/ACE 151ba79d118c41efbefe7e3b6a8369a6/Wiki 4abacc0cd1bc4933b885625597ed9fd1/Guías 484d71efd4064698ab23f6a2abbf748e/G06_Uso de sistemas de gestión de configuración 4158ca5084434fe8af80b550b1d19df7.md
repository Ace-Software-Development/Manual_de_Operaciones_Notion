# G06_Uso de sistemas de gestión de configuración

| Autor | ‣  |
| --- | --- |
| Responsable | ‣  |

# Descripción

---

Esta guía explicará cómo almacenar y recuperar elementos de configuración en los sistemas de gestión de la configuración que utiliza Ace Software.

# Objetivos

---

- Definir cuáles son los sistemas de gestión de la configuración utilizados en el departamento
- Explicar la estructura de los sistemas compartidos
- Explicar cómo almacenar elementos de configuración en los mismos sistemas
- Explicar cómo recuperar elementos de configuración en los mismos sistemas

## Criterios para identificar sistemas de gestión de la configuración

---

- Sistemas que almacenan los elementos de configuración identificados en la guía

[G03_Identificación de e**lementos de la configuración y líneas base**](G03_Identificacio%CC%81n%20de%20elementos%20de%20la%20configuraci%2081ed479aea0d45db89846463687d2a6f.md)

- Sistemas utilizados por los miembros del departamento para recuperar elementos de la configuración

## Sistemas de gestión de la configuración

---

- **Notion**
    
    ### ¿Qué es Notion?
    
    Notion es un software de gestión de proyectos y toma de notas.
    
    ### Estructura
    
    **Página Principal de Ace**
    
    ![Untitled](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Untitled.png)
    
    En la [Página principal](../../../ACE%20151ba79d118c41efbefe7e3b6a8369a6.md) del departamento hay acceso a:
    
    - Wiki
        - En la Wiki encontrarás procesos, plantillas checklists, guías, políticas, estándares, roles y una descripción del departamento, sus equipos y actividades.
        - Es aquí donde podrás acceder a los elementos de configuración más importantes de Ace.
    - Mejora Continua
        - En esta sección encontrarás:
            - Forma de Trabajo
            - CMMI
            - Biblioteca de Recursos
    - TimeLog
        - En esta página se encuentran los tiempos registrados de cada uno de los 4 proyectos, así como del CMMI.
        - Las instrucciones para registrar tiempos se encuentran en la página principal del TimeLog.
    - DefectLog
        - Es una matriz con los defectos encontrados y su severidad.
    - Log de Auditorías
        - Es una matriz con las auditorías que se realizan entre equipos. Es importante registrar el documento que contiene el resumen de la auditoría.
    - Repositorio de métricas
        - Se encuentran las métricas que utiliza el departamento y las mediciones que han hecho los equipos basándose en esas métricas.
    - SCAMPI ACE
        - Contiene el resumen y evidencia del avance de las diferentes áreas del CMMI.
    - Matriz de Configuración
        - Matriz que contiene los registros de configuración (procesos, guías, estándares, plantillas, checklists, etc.) tanto de los equipos como del departamento.
    - Tareas CMMI
        - Kanban Board que contiene tareas del CMMI y su progreso actual.
    
    ### Registro de elementos
    
    Nuestro sistema de Notion permite a cada miembro del departamento registrar nuevas políticas, guías, estándares, registros y elementos de configuración en general. 
    
    Para conocer las políticas de cambios y revisión de los elementos de la configuración, revisar los siguientes elementos:
    
    [E01_E**lementos de configuración y líneas base.**](../Esta%CC%81ndares%206577b6d75d3a4f788a00749c1fa0feee/E01_Elementos%20de%20configuracio%CC%81n%20y%20li%CC%81neas%20base%2014bf0cdb2ba24eb2b0002ae5b08bc493.md)
    
    [P23_Revisión de cambio en item de la Wiki](https://www.notion.so/P23_Revisi-n-de-cambio-en-item-de-la-Wiki-c8d92fb8afa7421b81f8cdd652b6f100)
    
    [P20_Creación o modificación de ítem de la wiki](../Procesos%20bc1b4b9263a749d49f2c809adfd71359/P20_Creacio%CC%81n%20o%20modificacio%CC%81n%20de%20i%CC%81tem%20de%20la%20wiki%201c63004a533c4261979129dee36c2501.md)
    
- **GitHub**
    
    ### ¿Qué es?
    
    GitHub, Inc. es un proveedor de alojamiento de Internet para el desarrollo de software y el control de versiones mediante Git.
    
    En la [cuenta de GitHub](https://github.com/Ace-Software-Development) del departamento se encontrarán los repositorios de los proyectos, así como el [Manual de Operaciones](https://github.com/Ace-Software-Development/Manual_de_Operaciones_Notion/tree/main/markdown/ACE%20151ba79d118c41efbefe7e3b6a8369a6), en el cual se guarda una copia de seguridad de nuestra página de Notion cada 12 horas.
    
    ### Acceso a repositorios
    
    Cualquier usuario de GitHub que sea parte de la organización Ace Software Development será capaz de acceder a los repositorios que almacena. 
    
    ![Untitled](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Untitled%201.png)
    
    En caso de no ser parte de la organización, el *maintainer* de la misma deberá darte acceso directo para visualizar los repositorios y equipos privados. 
    
    **Acceder al repositorio de un equipo**
    
    1. Ir a la pestaña *Teams*
        
        ![Untitled](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Untitled%202.png)
        
    2. Acceder a algún equipo (ejemplo: Campanario)
    3. Ir a la pestaña *Repositories.* En ella podrás visualizar los proyectos a los que tienes acceso. En caso de querer acceder a algún repositorio que no aparece, contactar al Architecture Owner del equipo. 
        
        ![Untitled](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Untitled%203.png)
        
    
- **Google Drive**
    
    ### ¿Qué es?
    
    Google Drive es un servicio de almacenamiento y sincronización de archivos desarrollado por Google.
    
    ### Unidad Compartida Departamental
    
    Como departamento tenemos una [unidad compartida](https://drive.google.com/drive/u/1/folders/0AL39qAgoCl2_Uk9PVA) en la que se encuentran diagramas de arquitectura, contenido multimedia, documentos formales de proyectos y documentos pertenecientes a la fase inicial del departamento.
    
    ### Estructura
    
    ![Untitled](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Untitled%204.png)
    
    Para acceder a cualquier carpeta y documento de la unidad compartida, contactar a la persona encargada de la misma para solicitar acceso. 
    
    A continuación, los documentos más significativos que se podrán encontrar en las carpetas de la unidad compartida del departamento.
    
    - Cartas de confidencialidad
        - Cartas de confidencialidad firmadas por cada integrante del departamento.
    - CMMI
        - **Plan de liberaciones del CMMI**
        - Áreas y sus integrantes
        - **DevGap Analysis (provisto por los profes)**
    - Encuestas
        - De felicidad
        - De cambio de roles
        - Departamentales
    - Entregable plan de trabajo
        - Archivos zip con el plan de trabajo terminado de los equipos
    - Ética
        - Código de ética y otros documentos
    - Imagen
        - Logos del departamento
        - Footer del correo electrónico
    - Juntas
        - Minutas de juntas de roles
    - Lecturas
        - Plan de comunicación
    - Pendientes
        - Lista de pendientes del CMMI (desactualizada)
    - Presentación Inicial
        - Videos de presentación de socio formadores
        - Expectativas iniciales
    - Plantillas de correos
        - Plantilla para correos a socio formadores y profesores
    - Plantillas de documentos
        - Matriz RACI
        - Retrospective
        - Iteración
        - **WBS**
        - Acta de Proyecto
    - Procesos
        - Plan del departamento
    - Projects
        - Cada equipo tiene un carpeta; sin embargo, Flor Imperial es el único que trabaja en esta. Los demás equipos tienen sus unidades compartidas, como se verá más adelante.
            - **Planeación y avance de iteración**
            - Videos de juntas con el socio
            - Documentos de diseño de arquitectura (algunos)
            - **Casos de Uso (algunos)**
    - Videos Avance 1
        - Experiencias individuales del primer bloque
        
    
    ### Unidades Compartidas de Equipos
    
    [Full House (NefroVida)](https://drive.google.com/drive/u/1/folders/0AJaEPGWkgQRpUk9PVA) 
    
    [BlackJack (Aluminio Monarca)](https://drive.google.com/drive/u/1/folders/0AP0ySRxyhtwWUk9PVA)
    
    En ambas Unidades Compartidas se encontrarán todos los documentos importantes de los equipos como planeación de iteraciones, progresos, y más. La estructura de archivos en ambas es similar a la que tiene la unidad compartida departamental.
    
- **Jira (Flor Imperial)**
    
    ### ¿Qué es?
    
    Jira Software proporciona herramientas de planificación y hojas de ruta para que los equipos puedan gestionar a los interesados, los presupuestos y los requisitos de las funciones desde el primer día.
    
    ### Estructura
    
    En el tablero de [Jira](https://a01701370.atlassian.net/jira/software/projects/CAM/boards/1/roadmap) puedes acceder a lo siguiente desde la barra lateral: 
    
    ![Untitled](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Untitled%205.png)
    
    - Hoja de ruta
        - Se encuentra el progreso de tareas y bloques de tareas con respecto al tiempo.
    - Backlog
        - Visualización de tareas terminadas por sprint
    - Tablero
        - Kanban Board con información del progreso de las tareas
    

## Recuperación de los elementos de configuración.

---

Se deberá tener un mecanismo de "rollbacks" o recuperación de versiones anteriores de los productos bajo gestión de la configuración.

[P32 Rollback de Git](../Procesos%20bc1b4b9263a749d49f2c809adfd71359/P32%20Rollback%20de%20Git%202def9ed783854191833873f66c47a127.md) 
[P22_Rollback de Wiki](../Procesos%20bc1b4b9263a749d49f2c809adfd71359/P22_Rollback%20de%20Wiki%20bf25946982ff489caa0a189e216fe0f1.md) 

[Bitácora de cambios (1)](G06_Uso%20de%20sistemas%20de%20gestio%CC%81n%20de%20configuracio%CC%81n%204158ca5084434fe8af80b550b1d19df7/Bita%CC%81cora%20de%20cambios%20(1)%20036188e9d09c409f967a3afc4652a5fe.csv)