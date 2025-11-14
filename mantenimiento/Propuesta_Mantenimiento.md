Mantenimiento de Software según Sommerville y Pressman

1. Introducción
   El mantenimiento de software es una fase esencial dentro del ciclo de vida del
   desarrollo. Su propósito es modificar y actualizar el sistema después de su entrega
   inicial, asegurando que continúe cumpliendo sus funciones correctamente ante cambios
   en los requerimientos, el entorno operativo o la tecnología.
   Según Ian Sommerville y Roger Pressman, el mantenimiento no solo corrige errores,
   sino que también adapta y mejora el software para prolongar su utilidad y eficiencia.
   Esta etapa comienza una vez que el software ha sido entregado y puesto en producción,
   y puede extenderse durante años, dependiendo del uso y evolución del sistema.
2. Tipos de Mantenimiento
   Sommerville y Pressman clasifican el mantenimiento en cuatro tipos principales:
   2.1 Correctivo
   Este tipo de mantenimiento se enfoca en corregir errores que no fueron detectados
   durante las fases de desarrollo y pruebas. Estos errores pueden incluir fallos en el
   código fuente (bugs), defectos en el diseño del sistema o problemas de rendimiento. Es
   un mantenimiento reactivo, ya que se realiza una vez que el problema ha sido
   identificado por los usuarios o el equipo de soporte.
   2.2 Adaptativo
   El mantenimiento adaptativo se realiza cuando el software necesita ajustarse a cambios
   externos, como nuevas versiones de sistemas operativos, cambios en el hardware,
   actualización de librerías o frameworks, o nuevas normativas legales. Este tipo de
   mantenimiento permite que el software siga siendo funcional en entornos cambiantes.
   2.3 Perfectivo
   El mantenimiento perfectivo busca mejorar el software sin alterar su funcionalidad
   principal. Las mejoras pueden estar orientadas a optimizar el rendimiento, mejorar la
   eficiencia del código o aumentar la usabilidad para el usuario final. Este tipo de
   mantenimiento responde a sugerencias de mejora, estudios de usabilidad o análisis de
   métricas de rendimiento.
   2.4 Preventivo
   El mantenimiento preventivo tiene un enfoque proactivo. Su objetivo es evitar futuros
   errores mediante refactorización del código, eliminación de dependencias innecesarias y
   mejora de la documentación técnica. Este tipo de mantenimiento busca aumentar la
   estabilidad y facilitar futuras modificaciones.
3. Costos del Mantenimiento
   El mantenimiento de software puede representar entre el 60% y el 80% del costo total
   del ciclo de vida del sistema.
   Factores que influyen en los costos (según Pressman):
   • Calidad del diseño y del código original: un diseño bien estructurado y un
   código limpio reducen la necesidad de correcciones.
   • Documentación disponible: la existencia de documentación clara y completa
   facilita la comprensión del sistema por parte de nuevos desarrolladores.
   • Complejidad del sistema: sistemas con muchas interdependencias o lógica
   compleja requieren más tiempo para ser modificados.
   • Rotación del personal y experiencia del equipo: la pérdida de conocimiento
   técnico por cambios en el equipo puede aumentar los costos.
   Cambios en los requerimientos del cliente o del entorno operativo: la evolución de las
   necesidades del usuario obliga a realizar ajustes continuos.
   Sommerville destaca que un diseño modular y bien documentado puede reducir
   significativamente los costos de mantenimiento
4. Etapas del Mantenimiento
   El proceso de mantenimiento, según Sommerville y Pressman, se compone de varias
   etapas que aseguran que los cambios realizados sean efectivos y seguros:
   4.1 Identificación del problema o mejora
   Se detectan errores, necesidades nuevas o sugerencias de mejora. La fuente puede ser el
   usuario final, el equipo de soporte o herramientas de monitoreo.
   4.2 Análisis del impacto
   Se evalúa el alcance de las modificaciones necesarias, su viabilidad técnica y el impacto
   que pueden tener en otras partes del sistema.
   4.3 Diseño de la solución
   Se planifican los cambios que se deben realizar en la arquitectura del sistema, en el
   código fuente o en la base de datos. Esta etapa incluye la definición de estrategias de
   prueba.
   4.4 Implementación
   Se lleva a cabo la codificación de los cambios, su integración con el sistema existente y
   la ejecución de pruebas unitarias y de integración.
   4.5 Verificación y validación
   Se verifica que los cambios realizados cumplan con los objetivos planteados y que no
   introduzcan nuevos errores. Se realizan pruebas funcionales, de regresión y de
   aceptación.
   4.6 Entrega y documentación
   Finalmente, se actualizan los manuales de usuario, la documentación técnica y se
   despliega la nueva versión del software al entorno de producción.
   Informe Técnico: Mantenimiento del Sistema de Control de Asistencia
5. Introducción
   El sistema de control de asistencia es una herramienta fundamental para la gestión del
   tiempo laboral, el cumplimiento normativo y la eficiencia operativa en las
   organizaciones. Sin embargo, como todo sistema informático, requiere mantenimiento
   constante para garantizar su correcto funcionamiento, seguridad y adaptabilidad a los
   cambios tecnológicos y legales.
6. Problemas Comunes Identificados
   Durante el análisis del sistema de control de asistencia, se han detectado los siguientes
   problemas recurrentes:
   2.1 Fallas técnicas
   Se presentan errores en la aplicación o el hardware que interrumpen el registro normal
   de asistencias. Entre los más frecuentes se encuentran:
   • Caídas del servidor
   • Fallos de sincronización entre dispositivos
   • Interrupciones en la conexión con bases de datos
   Estos problemas afectan la confiabilidad del sistema y requieren intervención inmediata
   para restaurar la funcionalidad.
   2.2 Vulnerabilidades de seguridad
   Se han identificado riesgos como contraseñas débiles, falta de cifrado en la transmisión
   de datos y accesos no autorizados. Estas vulnerabilidades comprometen la integridad de
   la información y pueden derivar en filtraciones o manipulaciones de registros.
   Fuente: geovictoria.com
   2.3 Cambios en requisitos tecnológicos o normativos
   La evolución de las regulaciones laborales y la incorporación de nuevas tecnologías
   (como hardware biométrico o actualizaciones de sistemas operativos) exigen que el
   software se adapte para mantener su compatibilidad y cumplimiento legal.
   2.4 Déficit de funcionalidades y mejoras
   Se observan carencias en el rendimiento general del sistema y en sus características
   funcionales. Ejemplos incluyen:
   • Falta de optimización en procesos internos
   • Ausencia de informes avanzados
   • Interfaz poco intuitiva para el usuario
   Estas limitaciones afectan la experiencia del usuario y reducen la eficiencia operativa.
7. Tipos de Mantenimiento Aplicables
   Para abordar los problemas identificados, se aplican distintos tipos de mantenimiento,
   cada uno con objetivos específicos:
   3.1 Mantenimiento Correctivo – Fallas Técnicas
   Este tipo de mantenimiento se aplica para corregir errores que se presentan después de
   la entrega del sistema. Por ejemplo, ante una caída del servidor, se identifica el fallo, se
   repara y se restablece el servicio.
   F 3.2 Mantenimiento Correctivo y Preventivo – Vulnerabilidades de Seguridad
   El mantenimiento correctivo se encarga de parchear brechas detectadas, como accesos
   no autorizados o fallos de autenticación. El mantenimiento preventivo, por su parte,
   refuerza el sistema mediante actualizaciones periódicas, cifrado de datos y políticas de
   seguridad más estrictas.
   Fuente: cpl.thalesgroup.com
   3.3 Mantenimiento Adaptativo – Cambios en el Entorno
   Cuando surgen nuevos requisitos tecnológicos o normativos, se aplica mantenimiento
   adaptativo. Este implica modificar el software para que funcione correctamente con
   nuevos sistemas operativos, dispositivos biométricos o formatos de datos. Así se
   garantiza la compatibilidad continua con el entorno actual.
   3.4 Mantenimiento Perfectivo – Mejoras de Rendimiento y Funcionalidad
   Para optimizar el sistema y agregar nuevas características, se utiliza mantenimiento
   perfectivo. Este tipo de mantenimiento permite:
   • Mejorar algoritmos de procesamiento
   • Rediseñar la interfaz de usuario
   • Incorporar informes personalizados
   Estas mejoras responden a las necesidades de los usuarios y mantienen al software
   actualizado y competitivo.
8. Recomendaciones Generales
   • Implementar un plan de mantenimiento periódico que combine acciones
   correctivas, preventivas y perfectivas.
   • Establecer protocolos de seguridad robustos, incluyendo autenticación
   multifactor y cifrado de datos.
   • Documentar todos los cambios realizados para facilitar futuras intervenciones.
   • Capacitar al personal técnico en nuevas tecnologías y normativas aplicables.
   • Realizar auditorías regulares para detectar fallos antes de que afecten la
   operación.
   Cambio Funcional Propuesto: Implementación del Módulo de Reportes
   Automáticos de Asistencia
9. Nombre del cambio funcional
   “Módulo de Reportes Automáticos y Exportación de Datos”
10. Descripción del cambio y problema que resuelve
    Actualmente, la aplicación de control de asistencia cumple adecuadamente con el
    registro diario de entrada y salida de los usuarios. Sin embargo, presenta una limitación
    significativa: no cuenta con un sistema de generación automática de reportes ni con la
    posibilidad de exportar los datos a formatos estándar como PDF o Excel.
    El cambio funcional propuesto consiste en el desarrollo e integración de un módulo de
    reportes automáticos, capaz de generar informes personalizados filtrando por usuario,
    rango de fechas y estado de asistencia (presente, ausente o tardanza). Además, permitirá
    exportar los reportes generados en formatos PDF y Excel, facilitando la entrega de
    información a las áreas administrativas y de control.
11. Implementación técnica del módulo
    3.1 Análisis y diseño del módulo
    Se identificarán los campos necesarios del registro de asistencia: nombre del usuario,
    fecha, hora de entrada, hora de salida, estado de asistencia y observaciones.
    Posteriormente, se diseñará una interfaz intuitiva con filtros configurables para que el
    usuario seleccione los criterios del reporte.
    3.2 Desarrollo de la funcionalidad
    • Se creará una nueva sección en el menú principal denominada “Reportes”.
    • Se implementará la generación dinámica de tablas en tiempo real a partir de
    consultas SQL optimizadas.
    • Se integrarán botones de exportación a PDF y Excel, utilizando librerías
    específicas como iText para PDF y Apache POI para Excel.
    • Los reportes generados se almacenarán en un historial interno, permitiendo su
    consulta y descarga posterior.
    3.3 Pruebas y validación
    Se realizarán pruebas funcionales y de integración para verificar:
    • La exactitud de los datos mostrados
    • El correcto funcionamiento de los filtros
    • La legibilidad de los reportes exportados
    • La integridad del formato en ambos tipos de archivo
    3.4 Actualización de la documentación
    Se actualizará el manual de usuario para incluir instrucciones sobre el uso del nuevo
    módulo. Además, se registrarán los cambios en la documentación técnica y en el
    historial de versiones del sistema.
12. Mejora que corrige y beneficios esperados
    • Reducción del tiempo de generación de reportes: los usuarios podrán obtener
    información en segundos, sin recurrir a procesos manuales.
    • Eliminación de errores humanos: la automatización garantiza la exactitud de los
    datos exportados.
    • Mayor trazabilidad y control: los reportes históricos facilitan la revisión de
    asistencia en periodos anteriores.
    • Mayor productividad: los supervisores y responsables administrativos podrán
    concentrarse en el análisis y la toma de decisiones, en lugar de recopilar datos
    manualmente.
13. Impacto en la mantenibilidad y calidad del sistema
    5.1 Mantenibilidad
    El diseño del módulo se realizará bajo una arquitectura modular basada en el patrón
    MVC (Modelo–Vista–Controlador), separando la lógica de negocio de la interfaz
    gráfica. Esto permitirá realizar futuras actualizaciones o ajustes sin afectar las demás
    partes del sistema. Además, al utilizar librerías estándar, se asegura compatibilidad y
    facilidad de mantenimiento a largo plazo.
    5.2 Calidad del sistema
    El cambio funcional propuesto mejora la confiabilidad y la usabilidad del sistema,
    brindando información más clara, accesible y verificable. También mejora la
    experiencia del usuario final al proporcionar un entorno más completo, funcional y
    orientado a resultados. Asimismo, contribuye a la calidad interna del software, ya que el
    código del nuevo módulo estará documentado, reutilizable y alineado con las buenas
    prácticas de desarrollo.
    Justificación del Proyecto de Mantenimiento y Mejora del Sistema de Control de
    Asistencia
    El presente trabajo responde a la necesidad de mantener y mejorar el sistema de control
    de asistencia, abordando problemas técnicos, funcionales y de seguridad que afectan su
    operatividad y eficiencia. A partir del análisis de mantenimiento según Sommerville y
    Pressman, se identificaron fallas comunes como caídas del servidor, vulnerabilidades de
    seguridad, cambios en requisitos normativos y déficit de funcionalidades. Para cada
    caso se aplicaron tipos de mantenimiento específicos: correctivo, adaptativo, preventivo
    y perfectivo.
    Como mejora funcional, se propone el desarrollo del módulo de reportes automáticos y
    exportación de datos, que permitirá generar informes personalizados y exportarlos en
    formatos PDF y Excel. Esta solución optimiza el tiempo de trabajo, reduce errores
    humanos y mejora la trazabilidad de la información.
    La implementación técnica se basa en arquitectura modular MVC, garantizando
    mantenibilidad, escalabilidad y calidad del sistema.
    Reflexión Final
    El desarrollo de este proyecto permitió comprender de forma práctica la importancia del
    mantenimiento de software dentro del ciclo de vida de un sistema. Analizar el caso del
    Sistema de Control de Asistencia evidenció que el mantenimiento no se limita
    únicamente a corregir errores, sino que es una actividad estratégica que asegura la
    continuidad, calidad y evolución del producto.
    Durante el proceso, fue posible identificar los distintos tipos de mantenimiento descritos
    por Sommerville y Pressman, entendiendo que cada uno cumple una función específica
    en la conservación del software. En este caso, el mantenimiento perfectivo y adaptativo
    resultó fundamental para responder a las nuevas necesidades de los usuarios, como la
    generación automática de reportes y la exportación de datos, mejorando así la eficiencia
    y usabilidad del sistema.
    Asimismo, este trabajo resaltó el valor de una arquitectura modular y bien documentada
    para reducir costos y facilitar futuras actualizaciones. Implementar el módulo de
    reportes automáticos no solo resolvió un problema funcional, sino que también
    fortaleció la mantenibilidad y calidad general del sistema, haciéndolo más robusto y
    alineado con las exigencias tecnológicas actuales.
    En conclusión, este proyecto permitió apreciar que el mantenimiento de software es una
    tarea continua que garantiza la vigencia, confiabilidad y eficiencia de los sistemas.
    Aplicar buenas prácticas y una planificación adecuada en esta etapa es esencial para
    prolongar la vida útil del software y asegurar su aporte real a los objetivos
    institucionales.
