# P45_Proceso de inspección de código

## Objetivo[](https://ace-software-development.github.io/Manual-de-Operaciones/docs/Plantillas/PL03_Creaci%C3%B3n%20de%20Procesos#objetivo)

Realizar una inspección al código de un componente de un proyecto, para así encontrar posibles defectos y dar paso a su resolución.

## **Consideraciones a tomar**

El componente debe haber pasado por las siguientes fases de desarrollo:

1. Análisis
2. Diseño
3. Implementación
4. Pruebas

El moderador/a, inspectores y secretario/a deben tener acceso al Defect Log de cada equipo y a su repositorio.

| Equipo | Defect Log | Repositorio |
| --- | --- | --- |
| BlackJack | Defect Log BlackJack | Repositorio Blackjack |
| Full House | Defect Log Full House | Repositorio Full House |
| Flor Imperial | Defect Log Flor Imperial | Repositorio móvil Flor Imperial
Repositorio web Flor Imperial |

## **Criterios de entrada**

1. Componente a inspeccionar

## **Procedimiento**

| Fase | Actividad  | Encargado  | Área del CMMI |
| --- | --- | --- | --- |
| Preparación | Genera una copia del formato de inspección en la carpeta de inspecciones. | AO | VER 1.2 |
| Preparación | Selecciona a una persona por equipo que no haya participado en la implementación del componente para realizar la inspección. | AO | VER 1.2 |
| Preparación  | Asigna roles a cada persona de las que escogiste. Los roles son: 
    - Moderador: Dirige la                  inspección
    - Inspectores: Analizan el código
    - Secretario: Toma notas de la inspección, reporta los defectos del equipo en el Defect Log de cada equipo y reporta las acciones correctivas. | AO | VER 1.2 |
| Inspección | Abre el formato de inspección creado por el AO del equipo al que se inspeccionará. | Moderador/a, inspectores y secretario/a | VER 1.1 |
| Inspección | Indica el inicio de la inspección y empieza a cronometrar el tiempo. | Moderador | VER 1.1 |
| Inspección | Lee el formato de inspección y usa la checklist de código para reportar los nuevos defectos. | Inspector | VER 3.1 |
| Discusión  | Al terminar la inspección se revisan los defectos encontrados por los inspectores y se ve si más de un inspector encontró el mismo defecto. | Moderador/a, inspectores | VER 3.2 |
| Discusión | Copia los defectos encontrados por cada inspector en el Defect Log del equipo.  | Secretario/a | VER 1.1, VER 1.3 |
| Finalización | Deja el registro en el ‣ , donde se reporte:
    - El componente que se revisó. 
    - La personas que participaron en la inspección.
    - El costo de la inspección,
    - El número de defectos encontrados en la inspección
    - El link al formato de inspección. 
    - La fecha en la que se realizó la inspección  | Secretario/a | VER 3.2 |
| Comunicación | Comunica los resultados al equipo. | Moderador |  |
| Actualización de la checklist | Determina si todos los campos de la checklist de código fueron útiles o hacen falta nuevos aspectos a tomar en cuenta. | Moderador/a, inspectores y secretario/a | VER 3.2. OPF |
| Actualización de la checklist | Actualiza la checklist de código con los aspectos que se usarán para futuras inspecciones.  | Secretario | VER 3.2, OPF |

## **Criterios de salida**

1. Checklist de inspección actualizada.
2. Log de defectos del equipo desarrollador actualizado.
3. Acciones correctivas.
4. Nuevo registro en el [](../../Log%20de%20inspecciones%20fd4602cc1cdc4cbcaad14c24a810a4cc.csv) 
5. Nuevo  [formato de inspección](https://docs.google.com/spreadsheets/d/11FFdJXF6vc_Tg0CcchvbWvLiBh8K0CibRki52i5AJMA/edit#gid=0) 

## **Métricas**

1. Número total de defectos
2. Costo en minutos de la inspección
3. Densidad de defectos por KLOC

## **Responsable**

1. Architecture owner

## Bitácora de cambios

[Untitled](P45_Proceso%20de%20inspeccio%CC%81n%20de%20co%CC%81digo%20912506cec1464fccaebeb996c1498b42/Untitled%20Database%205d55644014d34c1abace7570047f8e43.csv)