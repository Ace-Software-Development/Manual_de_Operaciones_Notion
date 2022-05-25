# CH3_Checklist de Implementación

```markdown
# Seguridad
* [ ] La funcionalidad está correctamente protegida por roles/permisos
* [ ] Si es una funcionalidad desprotegida se debe limitar el abuso por bots
* [ ] Las validaciones se realizan tanto en el front para usabilidad y en el back por seguridad
* [ ] No se utiliza el frontend como fuente de verdad, toda comprobación es realizada en el backend
* [ ] No se envía al cliente información adicional a la requerida
* [ ] No se agregan secretos al repositorio y no se guardan del lado del cliente
* [ ] La consola no muestra vulnerabilidades conocidas en los componentes utilizados al ejecutar un npm audit
* [ ] Todas las acciones que hagan una creación, actualización o eliminación en la base de datos deberán ser registradas en el logger sin incluir información sensible
* [ ] Registrar en el inventario de funcionalidades las actividades de la user story con sus respectivos permisos y roles

## Usabilidad
* [ ] Visibilidad del estado del sistema, el usuario debe recibir feedback cuando realiza una acción, y siempre en un espacio de tiempo razonable.
* [ ] Coincidencia entre el sistema y el mundo real, es importante que uses palabras y conceptos que le sean familiares al usuario y le permitan comprender rápidamente qué está pasando.
* [ ] Dale al usuario el control y la libertad, dale al usuario el control y la libertad de realizar las acciones que desee incluso de dale la capacidad de deshacer acciones que puede haber tomado por error.
* [ ] Consistencia y estándares, el usuario no debe estar preguntándose siempre si ese botón enviará el correo, o si es un botón o un enlace, o si ese elemento es clicable o no.
* [ ] Prevención de errores.
* [ ] Reconocer en lugar de recordar, evitar utilizar u ocultar opciones detrás de menus hovers o modales. Evitar la carga mental en los usuarios. Usar palabras que el usuario reconozca y campos autocompletados.
* [ ] Flexibilidad y eficiencia de uso, realizar una interfaz flexible que permita ser modificada por los usuarios con mas experiencia y dejar una predefinida para los nuevos.
* [ ] Estética y diseño minimalista, toda la información mostrada en la interfaz debe ser necesaria y útil en el momento correcto.
* [ ] Ayuda al usuario a roconocer diagnosticar y recuperarse de los errores, facilitar la experiencia del usuario cuando suceden errores.
* [ ] Ayuda y documentación, incluir FAQ's para evitar llamadas de servicio técnico. Añadir explicaciones en los campos complejos de los formularios, incluir tooltips para aclaraciones de los textos.
* [ ] Maquetado web, incluir IDs y nombre de campo en el maquetado web. Los componentes deben ser responsivos y legibles en los dispositivos incluidos en las developer tools.
* [ ] Utilizar permisos para mostrar las acciones permitidas, implementar retroalimentacion de las acciones. (alerts, tooltips, dialogs, icons y modals).
```

[Bitácora de cambios (2)](CH3_Checklist%20de%20Implementacio%CC%81n%209f84d98979934903a0134a838d083f0d/Bita%CC%81cora%20de%20cambios%20(2)%202e448ff7e3134a9bae6fff075c5e59ca.csv)