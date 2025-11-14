Aplicación de Control de Asistencia
Descripción del caso

La Aplicación de Control de Asistencia es un sistema diseñado para registrar y gestionar la asistencia estudiantil mediante el uso de códigos QR y validación de horarios.
Su propósito es automatizar el proceso de control en el aula, facilitar la labor del docente y ofrecer a los estudiantes un acceso rápido a su historial.

El sistema está orientado a instituciones educativas que buscan una herramienta moderna, confiable y segura para el seguimiento académico diario.

Objetivos

Desarrollar una aplicación funcional para registrar asistencias por sesión de clase.

Aplicar principios de ingeniería de software: requerimientos, pruebas y validación.

Utilizar control de versiones mediante Git y GitHub.

Documentar el caso siguiendo estándares profesionales en formato Markdown.

Garantizar un registro seguro, verificable y rápido de la asistencia estudiantil.

Requerimientos principales
Requerimientos funcionales

Registrar asistencia mediante escaneo de código QR.

Permitir el registro manual con estados: Presente, Tarde y Ausente.

Validar que el registro se realice dentro de la ventana horaria establecida.

Generar reportes por curso o estudiante y exportarlos en formato CSV.

Enviar notificaciones cuando un estudiante supere umbrales de inasistencias o tardanzas.

Registrar toda modificación en una bitácora de auditoría.

Cerrar y anular sesiones de clase según permisos del docente.

Requerimientos no funcionales

Interfaz clara, accesible y optimizada para web y dispositivos móviles.

Respuesta rápida en el registro (menos de 2 segundos).

Alta disponibilidad (≥ 99 %) en horario académico.

Seguridad mediante HTTPS, autenticación por roles y registros inmutables.

Compatibilidad con navegadores modernos y sistemas Android/iOS.

Tabla de pruebas funcionales
Caso de prueba Entrada Resultado esperado Validación
CP1 – Registro válido por QR Escaneo de QR correcto Marca “Presente” en ≤ 2 segundos ✅ Correcto
CP2 – Fuera de horario Escaneo después de la ventana permitida Registro rechazado ✅ Correcto
CP3 – Duplicado de QR Escaneo del mismo QR dos veces Muestra error “QR ya registrado” ✅ Correcto
CP4 – Corrección manual Estado modificado por docente Bitácora registra usuario, fecha y motivo ✅ Correcto
CP5 – Notificación por umbral Estudiante supera límite Envío automático de notificación ✅ Correcto
Tipo de mantenimiento propuesto
Mantenimiento Perfectivo

Este mantenimiento se centra en mejorar la funcionalidad existente y optimizar la experiencia del usuario sin modificar el propósito principal del sistema.

Mejoras implementadas o sugeridas

Panel de estadísticas con indicadores de asistencia.

Filtros avanzados para reportes.

Exportación en PDF y visualizaciones gráficas.

Generación automática de códigos QR dinámicos por sesión.

Modo offline temporal para docentes con sincronización posterior.

Estas mejoras permiten aumentar la eficiencia operativa, mejorar la accesibilidad de los datos y elevar la calidad del sistema.

Reflexión sobre el control de versiones

El control de versiones fue fundamental para organizar el desarrollo del proyecto, documentar cambios y mantener un historial claro y trazable.
Gracias a Git y GitHub se pudieron:

Registrar cada cambio mediante commits descriptivos.

Comparar versiones (por ejemplo, DRS_v1 vs DRS_v2).

Colaborar sin riesgo de perder información.

Mantener toda la documentación del caso en un solo repositorio.

El uso adecuado del control de versiones garantiza orden, respaldo y coordinación durante todo el ciclo de vida del software.

Tipos de sistemas de control de versiones
Sistemas locales

Cada desarrollador administra su propio historial en su máquina.

Ventajas: Simples y rápidos.

Desventajas: Alto riesgo de pérdida; poca colaboración.

Sistemas centralizados

Un servidor principal aloja el repositorio.

Ventajas: Control centralizado, seguridad.

Desventajas: Dependencia del servidor.

Ejemplo: Subversion (SVN).

Sistemas distribuidos

Cada desarrollador posee una copia completa del repositorio.

Ventajas: Trabajo sin conexión, rapidez, flexibilidad.

Ejemplo: Git.

Elementos y operaciones básicas en Git

Repositorio: Almacén del historial del proyecto.

Working Copy: Área de trabajo local.

Commit: Guarda cambios en el historial.

Log: Muestra la evolución del proyecto.

Checkout: Permite cambiar de rama o versión.

Branch: Crea una línea paralela para nuevas funciones.

Push/Pull: Sincroniza cambios entre local y remoto.

GitHub en el proyecto

GitHub permitió:

Centralizar todos los documentos del caso.

Subir versiones actualizadas del DRS y del Plan de Pruebas.

Mantener un repositorio limpio, ordenado y con historial visible.

Facilitar la revisión y colaboración entre estudiantes o docentes.

Autor

Brian Enric Andrade Muñoz
