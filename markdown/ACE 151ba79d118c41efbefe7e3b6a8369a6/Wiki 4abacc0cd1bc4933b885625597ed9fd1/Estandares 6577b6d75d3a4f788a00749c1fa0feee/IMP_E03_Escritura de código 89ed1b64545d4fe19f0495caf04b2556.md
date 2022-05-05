# IMP_E03_Escritura de código

### Nombrar variables

En general, el idioma de preferencia es el inglés, ya que es cómo viene toda la documentación, los lenguajes y las librerías. En caso de que se haga referencia a un término de regla de negocio que no pueda expresarse de forma clara en inglés, se usará español.

En general, evitar usar abreviaturas a menos que se explique en comentarios o sea muy claro su significado. Buscar que los nombres sean descriptivos en lugar de abreviados.

Variables: camelCase

Funciones y métodos: camelCase

Clases: PascalCase

Formato JSON: snake_case

Nombre de los archivos: snake_case.formato

Nombres de los archivos de componentes: PascalCase.jsx

### Prácticas de escritura

Estas son prácticas que se busca que todo el equipo utilice para estandarizar el formato del código. Sin embargo, se consideran guías más que reglas estrictas.

En caso de que se identifique un caso en el que una de estas prácticas sea un obstáculo o comprometa la legibilidad del código, puede hacerse caso omiso de dicha práctica.

Se pueden usar plug-ins para darle un auto formateo, pero no se recomienda porque cada miembro del equipo puede tener un plug-in que use diferentes estándares y eso puede ser un problema a la hora de hacer commits, y en la lectura de los PR.

- indentación por espacios (4 espacios)
- cada función debe de preceder una línea de separación
- cada clase debe de preceder dos líneas de separación
- todos los imports deben de estar al inicio del archivo
- los imports deben de categorizarse
- cada categoría de import debe de preceder una línea de separación
- los imports que no pertenezcan a ninguna categoría, forman una categoría que se puede referirse como “otros”
- por defecto, para los strings, usar comillas simples (‘’), pero no es una regla de fuego
- tener un máximo de 125 caracteres por línea de código. En caso de tener más puede considerarse hacer uso de backslash (\) para continuar en la siguiente línea o dividir las acciones lógicas que se hacen en más líneas

Específico en archivos JavaScript

- las funciones o métodos dentro de otras funciones o clases deben de estar en formato de función de flecha (param1, param2, …) => { }
- en caso de necesitar exportar funciones, hacerlo en la declaración de la función o clase y no al final del archivo export function NombreDeFuncion() { }
- en caso de tener un único parámetro en una función de flecha, no es necesario colocar los paréntesis param => { }

[Bitácora de cambios (1)](IMP_E03_Escritura%20de%20co%CC%81digo%2089ed1b64545d4fe19f0495caf04b2556/Bita%CC%81cora%20de%20cambios%20(1)%205c9fbc3639454d81affb64afbdc589ef.csv)