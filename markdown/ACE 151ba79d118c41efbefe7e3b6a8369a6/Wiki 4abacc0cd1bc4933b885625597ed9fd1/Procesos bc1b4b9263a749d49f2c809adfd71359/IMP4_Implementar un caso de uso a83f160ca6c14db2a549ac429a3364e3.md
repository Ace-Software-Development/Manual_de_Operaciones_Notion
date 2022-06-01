# IMP4_Implementar un caso de uso

**Proceso para casos de uso**

**Asignación de caso de uso**

- En cada planeación se asignan los casos de uso a trabajar para cada miembro del equipo
- En caso de que un miembro del equipo se adelante y quiera trabajar en otro caso de uso, tendrá que entrar en contacto con el team leader.
- En caso de trabajar con Jira: Todos los casos de uso serán asignados en Jira al responsable, si un miembro quiere hacer un caso que no tenga asignado, informar al team leader.
- En caso de trabajar con Excel: Los asignados al caso de uso deberán agregar su nombre en el item de trabajo correspondiente en el plan de trabajo.

**Diseño y análisis**

- Para esta fase se usará la plantilla: [Plantilla Caso de uso](https://docs.google.com/document/d/1oGmXnyKv7paqNbtzmYlohwevpQBuphJ19f7QtLzqyko/edit)
- Llenar la plantilla hasta la sección de pruebas.
- Una vez llena, enviar el documento a algún miembro del equipo para que la valide.

**Implementación**

- Generar una branch remota en github con el nombre del caso de uso y su número en Jira o Excel.
- Nombrar variables, hacer comentarios, etc. en base al estándar: [https://jsdoc.app/](https://jsdoc.app/)
- Informar a los demás miembros del equipo en caso de que se vaya a hacer un cambio que pueda afectar a los demás.

**Pruebas**

- **Llevar a cabo las pruebas definidas en la plantilla Caso de uso.**
- Una vez que todas las pruebas hayan sido exitosas, hacer push a la branch remota.
- Hacer un pull request sin conflictos a develop y notificar a un miembro del equipo para que revise el código.
- El miembro del equipo responsable deberá llevar a cabo las pruebas de la misma forma y verificar que todas sean exitosas.
- Una vez que exista validación por parte del miembro se hará el merge y el caso de uso se dará por concluido en: [Requerimientos](https://docs.google.com/spreadsheets/d/11b8R4eX2zTpGUFKEB9DdAY1GEvhSiYRjEp2GKOfoY9A/edit#gid=262762532)
- En caso de que no se cumpla con lo requerido podra ejecutarse el proceso de rollback [P32 Rollback de Git](P32%20Rollback%20de%20Git%202def9ed783854191833873f66c47a127.md)

**Notas extra**

- Marcar todo el proceso en Jira, actualizar el estado (En diseño, In progress, etc.)
- Hacer el time tracking en Jira cada vez que se trabaje en el caso de uso.
- Notificar al AO de cualquier cambio realizado a la base de datos.
- Llenar la [matriz de trazabilidad](https://docs.google.com/spreadsheets/d/11b8R4eX2zTpGUFKEB9DdAY1GEvhSiYRjEp2GKOfoY9A/edit#gid=262762532)