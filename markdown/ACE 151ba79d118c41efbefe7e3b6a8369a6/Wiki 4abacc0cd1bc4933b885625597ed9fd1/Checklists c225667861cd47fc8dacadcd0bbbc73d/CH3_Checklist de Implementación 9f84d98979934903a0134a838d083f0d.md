# CH3_Checklist de Implementación

```markdown

## Análisis
* [ ] Verificar que el código cumple con el análisis realizado previamente.
* [ ] El código cumple con comentarios de la historia de usuario correspondiente.

## Base de Datos
* [ ] Cada query a la base de datos cuenta con un catch para mostrar el error en caso de que suceda con su respectivo log para identificarlo en el servidor.
* [ ] Los nombres de las tablas y campos de las mismas deben ser llamados a través de su respectiva constante del archivo de constantes del proyecto.

## Seguridad
* [ ] La funcionalidad está correctamente protegida por roles/permisos indicados
* [ ] Si es una funcionalidad desprotegida se debe limitar el abuso por bots
* [ ] Las validaciones se realizan tanto en el front para usabilidad y en el back por seguridad
* [ ] No se utiliza el frontend como fuente de verdad, toda comprobación es realizada en el backend
* [ ] No se envía al cliente información adicional a la requerida
* [ ] No se agregan secretos al repositorio y no se guardan del lado del cliente
* [ ] La consola no muestra vulnerabilidades conocidas en los componentes utilizados al ejecutar un npm audit
* [ ] Todas las acciones que hagan una creación, actualización o eliminación en la base de datos deberán ser registradas en el logger sin incluir información sensible
* [ ] Registrar en el inventario de funcionalidades las actividades de la user story con sus respectivos permisos y roles

## Estilo
* [ ] Revisar ortografía de interfaz
* [ ] Se utiliza camelCase para nombrar variables, archivos y carpetas.
* [ ] Cada archivo es almacenado dentro de la carpeta correcta.
* [ ] El nombre del archivo no excede los 24 caracteres.
* [ ] Archivos de modelo, controlador, rutas, componentes, entre otros deben terminar con su respectivo identificador. Ejemplo: colaboradorRouter
* [ ] Se llama a constante en caso de que se utilice un nombre reiteradamente a lo largo de varios archivos.
* [ ] Los nombres de las variables son significativos.
* [ ] Variables son inicializadas con un valor.
* [ ] Cada variable, función o declaración está siendo utilizada.
* [ ] Nombres de clases inician con mayúscula.
* [ ] Se utilizan 4 espacios de identación en el código.
* [ ] Cada llave que se abre se cierra con otra a la misma altura.
* [ ] El código dentro de llaves de más de 1 línea debe estar correctamente identado.
* [ ] Si expresión dentro de () es muy larga, separarla en distintas líneas con el paréntesis que cierra a la altura del inicio de la línea en donde empezó expresión.
* [ ] No deben quedar líneas de código comentadas.
* [ ] Cada fín de línea cuenta con ;
* [ ] Se utiliza espaciado para separar palabras y caractéres especiales correctamente.
* [ ] El inicio de cada sección o función cuenta con 2 espacios de separación.
* [ ] Cadenas utilizan “” en HTML y ‘’ en JS.
* [ ] No romper cadena en varias líneas a pesar de que sea muy larga.
* [ ] Concatenar cadena corectamente. Ejemplo: ‘Hola {nombre}’
* [ ] Dejar espacio al inicio y final de un json. Ejemplo: { sol: ‘amarillo’ }
* [ ] No dejar espacios entre paréntesis ni corchetes. Ejemplo if(cond), arr = [1, 2, 3], console.log(var).
* [ ] El lenguaje de la interfaz sea el mismo que el del usuario final

## Lógica
* [ ] La lógica de comparadores es correcta (!=, ==).
* [ ] Cada ciclo tiene iniciación, incremento y un caso base correcto que no resultará en overflow.

## Comentarios
* [ ] Los comentarios realizados ayudan a que el lector entienda el comportamiento del código.
* [ ] Utilizar comentarios de sección /** */ para describir qué hace el código a continuación con sus respectivos parámetros de entrada y de salida.
* [ ] Comentario debe tener su línea independiente encima del código, no en la misma línea del código.
* [ ] Cada comentario inicia con un espacio separándolo de //

## Usabilidad
* [ ] El código considera aspectos de responsividad para distintos tamaños de pantalla.
* [ ] Cada selector de clase utiliza su propia línea antes de definir sus atributos.
* [ ] Cada clase debe tener un espacio antes de abrir llaves {}.
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