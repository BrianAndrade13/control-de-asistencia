Aplicación de Control de Asistencia: Análisis, Requerimientos y Uso de Control de Versiones
1. Introducción

La Aplicación de Control de Asistencia es un sistema orientado a automatizar los procesos de registro de asistencia en entornos educativos mediante el uso de códigos QR, validación de horarios y mecanismos de auditoría. Su objetivo principal es facilitar el trabajo docente, optimizar la gestión académica diaria y proporcionar a los estudiantes una herramienta confiable para consultar su historial de asistencia.

Este sistema está dirigido a instituciones educativas que buscan modernizar y digitalizar sus procesos internos mediante soluciones eficientes, seguras y escalables. Su diseño integra principios de ingeniería de software, buenas prácticas de documentación y el uso adecuado de control de versiones.

2. Objetivos del Sistema

Los objetivos que guiaron el desarrollo de la aplicación son los siguientes:
=======
Aplicación de Control de Asistencia

Proyecto académico – Ingeniería de Software
Control y gestión de asistencia estudiantil mediante QR

La Aplicación de Control de Asistencia es un sistema orientado al registro y seguimiento de asistencia estudiantil empleando códigos QR y validación de horarios.
Su propósito es agilizar el proceso de control en aula, facilitar el trabajo del docente y ofrecer a los estudiantes un acceso rápido y ordenado a su historial.

Está pensada para instituciones educativas que requieren una herramienta moderna, confiable y segura para el monitoreo académico diario.

Objetivos del proyecto

Desarrollar una aplicación funcional para registrar asistencias por sesión.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

Desarrollar una herramienta funcional para registrar asistencias por sesión de clase.

Aplicar principios de ingeniería de software, incluyendo requerimientos, pruebas y validación.

<<<<<<< HEAD
Utilizar un sistema de control de versiones mediante Git y GitHub.

Documentar el avance del caso utilizando estándar profesional en formato Markdown.
=======
Documentar el caso con estándares profesionales en Markdown.

Garantizar un registro seguro, verificable y eficiente.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

Garantizar un registro seguro, verificable y ágil de la asistencia estudiantil.

<<<<<<< HEAD
3. Requerimientos del Sistema
3.1 Requerimientos funcionales

Registrar asistencia mediante el escaneo de códigos QR.

Permitir registro manual con estados: Presente, Tarde y Ausente.

Validar que el registro se realice únicamente dentro de la ventana horaria establecida.
=======
Registro de asistencia mediante código QR.

Registro manual con los estados: Presente, Tarde y Ausente.

Validación automática de la ventana horaria permitida.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

Generación de reportes filtrables y exportación en formato CSV.

<<<<<<< HEAD
Enviar notificaciones automáticas cuando un estudiante supere umbrales de inasistencias o tardanzas.

Registrar cambios y modificaciones en una bitácora de auditoría.

Permitir cerrar o anular sesiones de clase según permisos del docente.
=======
Notificaciones al superar límites de inasistencias o tardanzas.

Registro de modificaciones en una bitácora de auditoría.

Cierre y anulación de sesiones según permisos del docente.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

3.2 Requerimientos no funcionales

<<<<<<< HEAD
Interfaz intuitiva, accesible y optimizada tanto para web como para dispositivos móviles.

Tiempo de respuesta menor a 2 segundos en el registro de asistencia.

Alta disponibilidad (≥ 99 %) durante el horario académico.

Seguridad mediante HTTPS, autenticación basada en roles y registros inmutables.
=======
Interfaz accesible y clara en web y dispositivos móviles.

Tiempo de respuesta menor a 2 segundos por registro.

Disponibilidad mínima del 99 % durante el horario académico.

Seguridad mediante HTTPS y autenticación por roles.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

Compatibilidad con navegadores modernos, Android y iOS.

<<<<<<< HEAD
4. Pruebas Funcionales

A continuación se presenta una tabla de casos de prueba diseñados para validar la funcionalidad del sistema:

Caso de prueba	Entrada	Resultado esperado	Validación
CP1 – Registro válido por QR	Escaneo correcto del QR	Marca “Presente” en ≤ 2 s	✔ Correcto
CP2 – Fuera de horario	Escaneo fuera de la ventana permitida	Registro rechazado	✔ Correcto
CP3 – Duplicado de QR	Escaneo repetido del mismo QR	Error: “QR ya registrado”	✔ Correcto
CP4 – Corrección manual	Estado modificado por docente	Bitácora registra usuario, fecha y motivo	✔ Correcto
CP5 – Notificación por umbral	Estudiante supera límite	Se envía notificación automática	✔ Correcto
5. Tipo de Mantenimiento Propuesto
Mantenimiento Perfectivo

El mantenimiento realizado se centra en mejorar las funcionalidades existentes sin alterar el propósito central del sistema. Este tipo de mantenimiento permite refinar procesos internos, optimizar el rendimiento y mejorar la experiencia de los usuarios.
=======
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
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

Mejoras implementadas o sugeridas

Panel de estadísticas con indicadores de asistencia.

Filtros avanzados en los reportes.

Exportación de reportes a PDF y visualizaciones gráficas.

Generación automática de códigos QR dinámicos por sesión.

Modo offline temporal con sincronización posterior.

<<<<<<< HEAD
Estas mejoras contribuyen a aumentar la eficiencia operativa y accesibilidad de los datos, además de reforzar la calidad general del sistema.
=======
Estas mejoras fortalecen la eficiencia, accesibilidad y calidad del sistema.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

6. Reflexión sobre el Uso del Control de Versiones

<<<<<<< HEAD
El control de versiones desempeñó un papel fundamental en la organización del proyecto. A través de Git y GitHub fue posible:

Registrar cambios mediante commits descriptivos.

Comparar versiones de manera segura (por ejemplo, DRS_v1 vs DRS_v2).

Facilitar el trabajo colaborativo sin riesgo de pérdida de información.

Mantener la documentación del caso en un repositorio centralizado.

El uso disciplinado del control de versiones garantiza orden, trazabilidad y coordinación durante el ciclo de vida del software, además de permitir auditoría y mantenimiento continuo.
=======
El control de versiones fue esencial para organizar el desarrollo del proyecto y mantener un historial claro y verificable.
Por medio de Git y GitHub se logró:

· Registrar cambios mediante commits descriptivos.
· Comparar versiones (por ejemplo, DRS_v1 y DRS_v2).
· Colaborar sin riesgo de pérdida de información.
· Centralizar toda la documentación del caso en un repositorio único.

El uso adecuado de Git asegura orden, trazabilidad y continuidad durante el ciclo de vida del software.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

7. Tipos de Sistemas de Control de Versiones
7.1 Sistemas locales

<<<<<<< HEAD
Cada desarrollador mantiene su propio historial en su máquina.

Ventajas: simplicidad y rapidez.

Desventajas: alto riesgo de pérdida y poca colaboración.
=======
· El historial se almacena en la máquina del desarrollador.
· Ventajas: simplicidad y rapidez.
· Desventajas: riesgo de pérdida y limitada colaboración.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

7.2 Sistemas centralizados

<<<<<<< HEAD
Un servidor principal almacena el repositorio.

Ventajas: control centralizado y seguridad.

Desventajas: dependencia total del servidor.

Ejemplo: Subversion (SVN).
=======
· Un servidor principal almacena el repositorio.
· Ventajas: control centralizado y consistencia.
· Desventajas: dependencia total del servidor.
· Ejemplo: Subversion (SVN).
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

7.3 Sistemas distribuidos

<<<<<<< HEAD
Cada desarrollador posee una copia completa del repositorio.

Ventajas: trabajo sin conexión, rapidez y flexibilidad.

Ejemplo: Git (el sistema más utilizado en la actualidad).

8. Elementos y Operaciones Básicas en Git

Repositorio: Contiene el historial de cambios del proyecto.

Working Copy: Área de trabajo local del desarrollador.

Commit: Registra un conjunto de cambios en el historial.

Log: Muestra el registro de versiones y modificaciones.

Checkout: Permite cambiar de rama o recuperar versiones anteriores.

Branch: Crea una línea paralela para funcionalidades nuevas.

Push/Pull: Sincroniza cambios entre repositorio local y remoto.

9. GitHub en el Proyecto
=======
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
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

GitHub fue utilizado como plataforma principal para:

<<<<<<< HEAD
Centralizar todos los documentos del caso de estudio.

Subir versiones actualizadas del DRS y del Plan de Pruebas.

Mantener un historial ordenado y limpio del proyecto.

Facilitar la revisión y colaboración entre estudiantes y docentes.
=======
· Centralizar los documentos y versiones.
· Subir actualizaciones del DRS y del Plan de Pruebas.
· Mantener un repositorio organizado y legible.
· Facilitar la revisión y colaboración con otros usuarios.
>>>>>>> 966793dbdd5f711a9fa9701fa98b429359d9fcad

10. Autor

Brian Enric Andrade Muño
