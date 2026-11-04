# Baile Flow — V28.1

Base: V27.2. Conserva la clave de datos existente y todas las funciones anteriores.

## Cambios

- Recuperación excepcional en otro nivel: opción explícita de autorización al registrar una reposición. La excepción queda anotada en el historial; las restricciones habituales siguen activas por defecto.
- Segunda matrícula de Samba: sugerencia de $16.000 por cuatro clases cuando existe otra matrícula activa de Samba con un ciclo concurrente. La matrícula principal conserva $24.000.
- Ciclos parciales de 1, 2, 3 o 4 clases: importe proporcional respecto al valor base editable (por ejemplo, dos clases adicionales = $8.000).
- Cada matrícula conserva ciclos, asistencias y reposiciones independientes. No se recalculan pagos ni ciclos antiguos.
- Se reserva el proyecto de acceso de administrador, profesor y estudiante para una futura versión; no se ha habilitado acceso externo.

## Publicación

Exporta un backup antes de subir los cinco archivos de esta carpeta a la raíz del repositorio GitHub. Comprueba el rótulo `V28`. Prueba un ciclo de dos clases en la segunda matrícula y una reposición excepcional con tus datos.

## Cambios V28.1
Al inactivar una alumna se cierran todas las reposiciones pendientes; al inactivar una modalidad, solo las de esa modalidad. El historial de faltas, presencias y pagos permanece. También se revisan matrículas ya inactivas sin reabrir pendientes cerradas.
