# IMP_E01_Estandarización del desarrollo

## Flujo general de trabajo

- Se identifica la tarea a realizar
- Se crea o actualiza una incidencia en Jira
- Se asigna a un Sprint de desarrollo
- Se asigna un responsable a la incidencia
- Si involucra cambios en el código, se crea una branch de “develop” con el nombre de la incidencia
- Se trabaja en la incidencia y cambia el estatus a “en progreso”
- Una vez el responsable haya hecho los cambios necesarios en la branch, hace push de la branch al repositorio y crea un Pull Request (PR). Luego asigna el PR y la incidencia a otro miembro del equipo y se cambia el estatus a “en revisión”
- Si se hacen cambios que puedan comprometer otras funcionalidades o son muchos cambios los que se hacen, se asigna a un tercer miembro del equipo para otra revisión.
- Una vez que todos los revisadores estén de acuerdo que los cambios al código funcionan como deberían y no introducen bugs, se acepta la petición del PR y se hace “merge” con la branch “development”. Se cambia el estatus de la incidencia a “esperando despliegue”
- Se hace una revisión general de la branch “development” de que todas las funcionalidades nuevas funcionen correctamente.
- El Architect Owner revisa la configuración
- Se hace el despliegue a producción

[Bitácora de cambios (1)](IMP_E01_Estandarizacio%CC%81n%20del%20desarrollo%20fa6d7345d78c418c9a08073e0b573893/Bita%CC%81cora%20de%20cambios%20(1)%20d77f3c5be9744c3ab5d7591843e422bd.csv)