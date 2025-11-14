Aplicación de Control de Asistencia

Proyecto académico – Ingeniería de Software
Control y gestión de asistencia estudiantil mediante QR

La Aplicación de Control de Asistencia es un sistema orientado al registro y seguimiento de asistencia estudiantil empleando códigos QR y validación de horarios.
Su propósito es agilizar el proceso de control en aula, facilitar el trabajo del docente y ofrecer a los estudiantes un acceso rápido y ordenado a su historial.

Está pensada para instituciones educativas que requieren una herramienta moderna, confiable y segura para el monitoreo académico diario.

Objetivos del proyecto

Desarrollar una aplicación funcional para registrar asistencias por sesión.

Aplicar principios de ingeniería de software: requerimientos, pruebas y validación.

Utilizar control de versiones mediante Git y GitHub.

Documentar el caso con estándares profesionales en Markdown.

Garantizar un registro seguro, verificable y eficiente.

Requerimientos principales
Requerimientos funcionales

Registro de asistencia mediante código QR.

Registro manual con los estados: Presente, Tarde y Ausente.

Validación automática de la ventana horaria permitida.

Generación de reportes filtrables y exportación en formato CSV.

Notificaciones al superar límites de inasistencias o tardanzas.

Registro de modificaciones en una bitácora de auditoría.

Cierre y anulación de sesiones según permisos del docente.

Requerimientos no funcionales

Interfaz accesible y clara en web y dispositivos móviles.

Tiempo de respuesta menor a 2 segundos por registro.

Disponibilidad mínima del 99 % durante el horario académico.

Seguridad mediante HTTPS y autenticación por roles.

Compatibilidad con navegadores modernos, Android y iOS.

Tabla de pruebas funcionales
Caso de prueba	Entrada	Resultado esperado	Validación
CP1 – Registro válido por QR	Escaneo válido	Marca “Presente” en ≤ 2 segundos	Correcto
CP2 – Fuera de horario	Escaneo fuera de ventana	Registro rechazado	Correcto
CP3 – Duplicado de QR	Mismo QR dos veces	Muestra “QR ya registrado”	Correcto
CP4 – Corrección manual	Estado modificado por docente	Bitácora registra usuario, fecha y motivo	Correcto
CP5 – Notificación por umbral	Estudiante supera el límite	Se envía notificación automática	Correcto
Tipo de mantenimiento propuesto
Mantenimiento Perfectivo

Este mantenimiento busca mejorar las funciones actuales y optimizar la experiencia del usuario sin modificar los objetivos base del sistema.

Mejoras implementadas o sugeridas

Panel de estadísticas con indicadores de asistencia.

Filtros avanzados para reportes.

Exportación en PDF y visualizaciones gráficas.

Generación automática de códigos QR dinámicos por sesión.

Modo offline temporal con sincronización posterior.

Estas mejoras fortalecen la eficiencia, accesibilidad y calidad del sistema.

Reflexión sobre el control de versiones

El control de versiones fue esencial para organizar el desarrollo del proyecto y mantener un historial claro y verificable.
Por medio de Git y GitHub se logró:

· Registrar cambios mediante commits descriptivos.
· Comparar versiones (por ejemplo, DRS_v1 y DRS_v2).
· Colaborar sin riesgo de pérdida de información.
· Centralizar toda la documentación del caso en un repositorio único.

El uso adecuado de Git asegura orden, trazabilidad y continuidad durante el ciclo de vida del software.

Tipos de sistemas de control de versiones
Sistemas locales

· El historial se almacena en la máquina del desarrollador.
· Ventajas: simplicidad y rapidez.
· Desventajas: riesgo de pérdida y limitada colaboración.

Sistemas centralizados

· Un servidor principal almacena el repositorio.
· Ventajas: control centralizado y consistencia.
· Desventajas: dependencia total del servidor.
· Ejemplo: Subversion (SVN).

Sistemas distribuidos

· Cada usuario posee una copia completa del repositorio.
· Ventajas: trabajo sin conexión, flexibilidad y buena velocidad.
· Ejemplo: Git.

Elementos y operaciones básicas en Git
Elemento	Descripción
Repositorio	Historial completo del proyecto
Working Copy	Área de trabajo local
Commit	Guarda cambios de manera permanente
Log	Muestra el historial del proyecto
Checkout	Cambia de rama o versión
Branch	Crea una línea paralela de desarrollo
Push/Pull	Sincroniza cambios entre local y remoto
GitHub en el proyecto

GitHub permitió:

· Centralizar los documentos y versiones.
· Subir actualizaciones del DRS y del Plan de Pruebas.
· Mantener un repositorio organizado y legible.
· Facilitar la revisión y colaboración con otros usuarios.

Autor

Brian Enric Andrade Muñoz
