# Defecto que llega a producción.

Categoría: Técnico
Consecuencias: - Presentar problemas e incidencias del lado del cliente.
- Se perjudica la operación del negocio.
- Se afecta la experiencia de usuario para el cliente.
Fecha de definición: 10/03/2022
ID: 4
Impact: 10
Interno: Yes
Magnitud: 1
Plan de mitigación: - Pruebas unitarias previas a cada integración de código.
- Revisión del listado de funcionalidad previo al despliegue.
- Validación de un tercero en ambiente de pruebas.
- Realizar un backup de la BD antes del despliegue.
Plan de respuesta: - Dependiendo del defecto, priorizar la fecha de corrección.
- Considerar un rollback del despliegue dependiendo del defecto.
- Restaurar la BD.
Prob: 0.1
Responsable: AO
Statu: Atendido con Plan de Mitigación
Status: Identificado