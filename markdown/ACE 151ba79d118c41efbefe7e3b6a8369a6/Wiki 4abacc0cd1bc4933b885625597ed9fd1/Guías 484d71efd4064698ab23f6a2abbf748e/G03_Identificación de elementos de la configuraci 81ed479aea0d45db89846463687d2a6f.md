# G03_Identificación de elementos de la configuración y líneas base

| Autor | Paulina Cardoso Fuentes |
| --- | --- |
| Responsable | Jorge Alan Ramírez Elías |

# Descripción

---

Esta guía ayudará para elegir los elementos que deben ser gestionados, identificarlos únicamente  y definir los responsables de ejecutar continuamente esta guía

# Objetivos

---

- Definir qué elementos entran bajo gestión de configuración y criterios para identificarlos

## Criterios para identificar elementos de configuración

---

- Productos de trabajo que se pueden utilizar por dos o más equipos.
- Productos de trabajo que se espera que cambien a lo largo del tiempo
debido a errores o a cambios en los requisitos.
- Productos de trabajo que son dependientes entre sí (es decir, un
cambio en uno implica un cambio en los otros).
- Productos de trabajo críticos para el éxito del proyecto.

## Productos de trabajo bajo Gestión de Configuración

---

### Productos entregados al cliente

- Código fuente
- Manuales de usuario
- Wireframes
- Documentos técnicos
- Diagramas

### Productos de trabajo interno

- Guías
- Procesos
- Políticas
- Plantillas
- Checklists
- Estándares
- WBS
- Mapa de procesos

### Herramientas y activos esenciales del entorno de trabajo del
proyecto

- Base de datos
- Stack tecnológicos

## Identificadores

---

Todos los elementos y productos de trabajo bajo Gestión de Configuración deberán de tener un identificador único para distinguir cada uno de ellos. 

En la siguiente tabla se muestra cómo se deberá de identificar cada producto de trabajo. 

| Producto | Identificador |
| --- | --- |
| Guías | G##_ |
| Procesos | P##_ |
| Políticas | PO##_ |
| Plantillas | PL##_ |
| Checklists | CH##_ |
| Estándares | E##_ |
| WBS | WBS##_ |
| Mapa de procesos | MP##_ |
| Código fuente | C##_ |
| Manuales de usuario | M##_ |
| Wireframes | WF##_ |
| Documentos técnicos | DT##_ |
| Diagramas | D##_ |
| Base de datos | BD##_ |
| Stack tecnológicos | ST##_ |

En el caso de los productos de trabajo de los equipos, se deberá poner como prefijo el identificador de cada equipo. El glosario para los identificadores por equipo es el siguiente.

| Equipo | Identificador |
| --- | --- |
| Blackjack | BKJ_ |
| Full House | FH_ |
|  Flor Imperial | IMP_ |

**Ejemplo:** BKJ_G01_Guía del servidor

## Nivel de los elementos de configuración

---

Todos los elementos de configuración pueden tener 3 niveles, los que se definen a continuación:

1. **Nivel dinámico**
    
    No existe ningún control ni gestión sobre el elemento de configuración. Para que un elemento de configuración de nivel dinámico pase a nivel controlado debe haber un proceso/mecanismo que permita tener un historial de cambios y versiones.
    
2. **Nivel controlado**
    
    Nivel intermedio donde existe cierto control sobre los elementos de configuración pero que aún no han sido verificados. Para que un elemento de configuración entre o salga de nivel controlado se debe de pasar por un proceso de verificación. 
    
    Si el ítem de configuración esta almacenado en **Github** se seguirá el siguiente proceso:
    
    [P04_**Revision de pull request**](../Procesos%20bc1b4b9263a749d49f2c809adfd71359/P04_Revision%20de%20pull%20request%209d3b4ef1e74a4028b85cb2cf1c30b926.md) 
    
    Si el ítem de configuración esta almacenado en **Notion** o **Drive** se seguirá el siguiente proceso:
    
    [P25_Auditorías a assets y productos de trabajo](../Procesos%20bc1b4b9263a749d49f2c809adfd71359/P25_Auditori%CC%81as%20a%20assets%20y%20productos%20de%20trabajo%20386d7b5b7b17435eb70e22f8f6ee7f08.md) 
    
3. **Nivel estático**
    
    El conjunto de todos los elementos de configuración en nivel estático en una instancia de tiempo forman una línea base. Una línea base es un snapshot o una versión de los elementos de configuración que han sido aprobados y gestionados previamente en el nivel controlado.
    

## Líneas base identificadas

### ¿Qué es una línea base?

Una línea base son aquellos elementos de la configuración que han sido *identificados, validados y revisados*. Las líneas base nos sirven como un punto de inicio para modificaciones y desarrollos posteriores. Corresponden a la última versión del elemento de configuración que ya ha pasado por una etapa de revisión y validación para poder ser usado por el departamento o stakeholders. 

La línea base de los proyectos de cada equipo se controla directamente mediante Git. El repositorio de cada proyecto trabaja con un flujo de trabajo con la propuesta de [Vincent Driessen](https://aulasoftwarelibre.github.io/taller-de-git/gitflow/). En este esquema, hay dos ramas principales con un tiempo de vida indefinido:

- **main (*origin/main*):** el código apuntado por *HEAD* siempre contiene un estado listo para producción.
- **develop (*origin/develop*):** el código apuntado por *HEAD* siempre contiene los últimos cambios desarrollados para la próxima versión del software. También se le puede llamar *rama de integración*. No es necesariamente estable.

Cuando el código de la rama de desarrollo es lo suficientemente estable, se integra con la rama main y una nueva versión es lanzada.

Adicionalmente están las ramas auxiliares para labores concretas como la creación de funcionalidades. Estas ramas tienen tiempo definido y cuando ya no son necesarias se eliminan. 

- ***auxiliar:*** En esta rama va todo aquello que esté en desarrollo. Desde nuevas funcionalidades, arreglos de bugs, refactors de diseño, etc. Toda la implementación debe de iniciar en este tipo de ramas, ser revisado y validado y posteriormente pasarse a la rama *develop.*

### Líneas base en el departamento

- [Línea base del departamento](../../Wiki%204abacc0cd1bc4933b885625597ed9fd1.md)
- [Línea base de Blackjack](https://github.com/Ace-Software-Development/blackjack_monarca)
- [Línea base de Full House](https://github.com/Ace-Software-Development/fullhouse-nefrovida)
- [Línea base de Flor Imperial Web](https://github.com/Ace-Software-Development/florimperial_campanario_web_react)
- [Línea base de Flor Imperial Móvil](https://github.com/Ace-Software-Development/florimperial_campanario_mobile)

[Bitácora de cambios](G03_Identificacio%CC%81n%20de%20elementos%20de%20la%20configuraci%2081ed479aea0d45db89846463687d2a6f/Bita%CC%81cora%20de%20cambios%20dd28bbb609c744bebd4a214aeac3cadb.csv)