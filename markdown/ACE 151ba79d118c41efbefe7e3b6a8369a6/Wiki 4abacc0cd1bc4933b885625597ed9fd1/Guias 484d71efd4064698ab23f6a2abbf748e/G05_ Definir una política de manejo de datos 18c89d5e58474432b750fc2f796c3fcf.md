# G05_ Definir una política de manejo de datos

Autor: Cutberto Arizabalo Nava

Área de CMMI: PP (SP 2.3)

Esta guía permitirá que cada equipo de trabajo defina su política de manejo de datos.

Una política de manejo de datos le permite a los interesados (como lo son los dueños del sistema y los usuarios) conocer que tipos de datos se almacenan, así como la forma en que se protegen.

Para establecer la política de manejo de datos, es necesario tomar como punto de partida la política de manejo de datos del socio formador, por lo que dicha política debe ser solicitada e incluida en nuestra política. 

Para comenzar con la política de datos, lo primordial es identificar los datos que están involucrados en la política. Para esto, se recomienda enlistarlos en una tabla con un formato similar al siguiente: 

| Dato | Formato |
| --- | --- |
| Contraseña de la cuenta | Cadena de texto encriptada con SHA256 |
| Análisis médico de un paciente | Archivo PDF |
| Reservación de espacio deportivo | Cadena de texto |

Adicional a esto, es importante incluir las especificaciones de seguridad y privacidad con las que contará el lugar en el que se almacenan los datos (esto depende de tu proveedor de Nube o Servicios). 

Por ejemplo, si se usa Back4App, se debe mencionar cual es la forma en la que dicho servicio almacena y resguarda los datos, además de referenciar la propia política de uso de datos del servicio.

Asimismo, es necesario mencionar qué personas van a tener acceso a cada tipo de dato.

Por ejemplo: En NefroVida se debe mencionar quienes pueden ver el historial médico de un paciente.  

También es importante mencionar los mecanismos que se utilizaran para la obtención de los datos, así como su reproducción y distribución.

Por ejemplo: 

- La obtención de los datos se hará a través de un formulario en la aplicación web. Dicho formulario enviará los datos al servidor de Back4App utilizando el protocolo HTTP, a través del API de Parse Server para JavaScript.  Dichas peticiones solo serán resueltas si el usuario se encuentra autenticado y su usuario cuenta con los permisos respectivos.
- El acceso a los datos se hará a través de la aplicación web, utilizando peticiones HTTP por medio de la API de Parse Server. Dichas peticiones solo serán resueltas si el usuario se encuentra autenticado y su usuario cuenta con los permisos respectivos.

[Bitácora de cambios (1)](G05_%20Definir%20una%20poli%CC%81tica%20de%20manejo%20de%20datos%2018c89d5e58474432b750fc2f796c3fcf/Bita%CC%81cora%20de%20cambios%20(1)%200a029ebc0400475eb808d52b070b1fb3.csv)