# G10_Registrar un defecto

## **Objetivo**

Llevar un registro y monitoreo de los defectos.

## **Criterios de entrada**

- Defecto o no conformidad.

## **Procedimiento**

1. Acceder al [DefectLog](../../DefectLog%20f78724bec45744b3b5627fda80160521.md).
2. Añadir una nueva fila en la tabla.
3. Llena los siguientes campos:
    1. ID: ID del defecto anterior +1
    2. Nombre: Nombre representativo del defecto.
    3. Estado:
        - Pending: Aún no se empieza.
        - Working on it: Ya se está trabajando en la solución.
        - Done: Ya se resolvió el defecto.
    4. Fecha de detección: Fecha en la que se halló el defecto.
    5. Proyecto: Proyecto en el que se detectó el defecto (solo para productos de trabajo).
    6. Responsable del defecto: Encargado de dar solución al defecto (dueño del producto o asset).
    7. Severidad: 
        - Necessary: El defecto debe resolverse, sin embargo no compromete el flujo de trabajo.
        - Urgent: El defecto debe atenderse prioritariamente porque representa un retraso en el flujo de trabajo.
        - Emergency: El defecto debe atenderse inmediatamente porque detiene el flujo de trabajo.
    8. Tipo: Corresponde directamente con el criterio de la checklist que no se aprobó. Los tipos de criterio son:
        - Valor
        - Definición
        - Formato y gramática
        - Gestión de la configuración
    9. Acción correctiva: Es la acción que se tomó para solucionar el defecto. 
    

## **Criterios de salida**

- [DefectLog](../../DefectLog%20f78724bec45744b3b5627fda80160521.md) actualizado

## **Responsable**

Auditores

## Bitácora de cambios

[Untitled](G10_Registrar%20un%20defecto%20b4264c111ef94064b4a19744c3aee61e/Untitled%20Database%20b1352e6b9c9b46d3ab29796f3c3e11ad.csv)