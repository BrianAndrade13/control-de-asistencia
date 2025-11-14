# Mantenimiento de Software según Sommerville y Pressman

## Introducción

El mantenimiento de software es una fase esencial dentro del ciclo de vida del desarrollo. Su propósito es modificar y actualizar el sistema después de su entrega inicial, asegurando que continúe cumpliendo sus funciones correctamente ante cambios en los requerimientos, el entorno operativo o la tecnología.

Según Ian Sommerville y Roger Pressman, el mantenimiento no solo corrige errores, sino que también adapta y mejora el software para prolongar su utilidad y eficiencia. Esta etapa comienza una vez que el software ha sido entregado y puesto en producción, y puede extenderse durante años, dependiendo del uso y evolución del sistema.

---

# 1. Tipos de Mantenimiento de Software

A continuación se describen los cuatro tipos de mantenimiento planteados por Sommerville y Pressman, cada uno por separado.

---

## 1.1 Mantenimiento Correctivo

El mantenimiento correctivo se enfoca en corregir errores que no fueron detectados durante las fases de desarrollo y pruebas.

**Características:**

- Reacciona ante fallos reportados por usuarios o soporte.
- Soluciona bugs en el código fuente.
- Corrige defectos en el diseño o estructura del sistema.
- Atiende problemas de rendimiento o fallas inesperadas.

**Ejemplos:**

- Caídas de la aplicación.
- Errores de cálculo.
- Funcionalidades que no responden como deberían.

---

## 1.2 Mantenimiento Adaptativo

Este tipo de mantenimiento se realiza cuando el software necesita ajustarse a cambios externos.

**Se aplica cuando existen cambios en:**

- Sistemas operativos.
- Hardware o dispositivos.
- Librerías o frameworks.
- Normativas legales o procedimientos institucionales.

**Objetivo:**  
Mantener la compatibilidad del sistema en entornos cambiantes.

---

## 1.3 Mantenimiento Perfectivo

El mantenimiento perfectivo busca mejorar el software sin alterar su funcionalidad principal.

**Mejoras típicas:**

- Optimización del rendimiento.
- Refactorización del código.
- Mejoras en la interfaz de usuario (UI/UX).
- Aumento de la usabilidad.

**Origen de las mejoras:**

- Sugerencias de usuarios.
- Estudios de usabilidad.
- Métricas de rendimiento.

---

## 1.4 Mantenimiento Preventivo

El mantenimiento preventivo tiene un enfoque proactivo para evitar errores futuros.

**Acciones comunes:**

- Refactorizar código para hacerlo más limpio.
- Reducir dependencias innecesarias.
- Mejorar la documentación técnica.
- Realizar revisiones periódicas para detectar fallos potenciales.

**Objetivo:**  
Aumentar estabilidad y facilitar futuras modificaciones.

---

# 2. Costos del Mantenimiento

El mantenimiento puede representar entre **60% y 80%** del costo total del ciclo de vida del software.

## Factores que influyen en los costos (según Pressman)

- **Calidad del diseño y código original**  
  Un diseño modular y limpio reduce fallas futuras.

- **Documentación disponible**  
  Un sistema bien documentado es más fácil de modificar.

- **Complejidad del sistema**  
  Más interdependencias aumentan el costo de mantenimiento.

- **Rotación del personal / experiencia del equipo**

- **Cambios en requerimientos del cliente o entorno operativo**

Sommerville destaca que **un diseño modular reduce el costo total de mantenimiento**.

---

# 3. Etapas del Mantenimiento (Sommerville y Pressman)

## 3.1 Identificación del problema o mejora
Se detectan errores, necesidades nuevas o sugerencias de mejora provenientes de usuarios, soporte o monitoreo.

## 3.2 Análisis del impacto
Se evalúa el alcance y viabilidad del cambio, además del posible impacto en otros módulos.

## 3.3 Diseño de la solución
Se planifican los cambios en arquitectura, código o base de datos, y se definen estrategias de prueba.

## 3.4 Implementación
Se desarrolla la solución, se integra al sistema y se realizan pruebas unitarias e integradas.

## 3.5 Verificación y validación
Se revisa que los cambios cumplan los objetivos y no introduzcan nuevos errores. Incluye pruebas funcionales, de regresión y aceptación.

## 3.6 Entrega y documentación
Se actualiza documentación técnica, manuales de usuario y se despliega la nueva versión en producción.

---

# 4. Informe Técnico: Mantenimiento del Sistema de Control de Asistencia

## Introducción

El sistema de control de asistencia es fundamental para gestionar registros laborales o académicos. Para garantizar su correcto funcionamiento, seguridad y adaptación, requiere mantenimiento continuo.

---

# 5. Problemas Comunes Identificados

## 5.1 Fallas Técnicas

- Caídas del servidor  
- Fallos de sincronización  
- Problemas de conexión con la base de datos  

**Impacto:** pérdida de confiabilidad y necesidad de intervención inmediata.

---

## 5.2 Vulnerabilidades de Seguridad

Riesgos detectados:

- Contraseñas débiles  
- Falta de cifrado  
- Accesos no autorizados  

**Consecuencia:** Riesgo de filtraciones o manipulación de registros.

---

## 5.3 Cambios Tecnológicos o Normativos

Ejemplos:

- Nuevas leyes laborales  
- Hardware biométrico  
- Actualización de sistemas operativos  

**Impacto:** Necesidad de actualización constante.

---

## 5.4 Déficit de Funcionalidades y Mejoras

- Procesos internos no optimizados  
- Reportes limitados  
- Interfaz poco intuitiva  

**Afecta la experiencia del usuario y la eficiencia operativa.**

---

# 6. Tipos de Mantenimiento Aplicables

Cada problema identificado se aborda con un tipo específico de mantenimiento.

---

## 6.1 Mantenimiento Correctivo – Fallas Técnicas

Se aplica cuando ocurren errores en producción.  
**Ejemplo:** caída del servidor → análisis → reparación → restauración.

---

## 6.2 Mantenimiento Correctivo y Preventivo – Seguridad

- **Correctivo:** parchea brechas detectadas.
- **Preventivo:** mejora cifrado, actualiza librerías, endurece políticas de seguridad.

---

## 6.3 Mantenimiento Adaptativo – Cambios en el Entorno

Modifica el software para ajustarse a:

- Nuevos sistemas operativos  
- Nuevas normativas  
- Nuevos dispositivos biométricos  

---

## 6.4 Mantenimiento Perfectivo – Mejoras Funcionales

Permite optimizar:

- Algoritmos  
- Interfaz de usuario  
- Reportes avanzados  

---

# 7. Recomendaciones Generales

- Implementar mantenimiento periódico.  
- Establecer protocolos de seguridad robustos.  
- Documentar todos los cambios realizados.  
- Capacitar a personal técnico.  
- Realizar auditorías regulares.

---

# 8. Cambio Funcional Propuesto: Módulo de Reportes Automáticos

## Nombre del cambio funcional
**“Módulo de Reportes Automáticos y Exportación de Datos”**

## Problema que resuelve
La aplicación no cuenta con reportes automáticos ni exportación a PDF/Excel.  
Esto afecta a áreas administrativas y de control.

## Propósito del cambio
- Generar informes personalizados  
- Filtrar por usuario, fecha o estado  
- Exportar en PDF y Excel  
- Guardar historial de reportes

---

# 9. Implementación Técnica del Módulo

## 9.1 Análisis y diseño
Identificación de campos esenciales: usuario, fecha, hora, estado, observaciones.  
Diseño de UI con filtros configurables.

## 9.2 Desarrollo
- Nueva sección “Reportes”  
- Tablas dinámicas con SQL optimizado  
- Exportación con iText (PDF) y Apache POI (Excel)  
- Historial interno de reportes generados

## 9.3 Pruebas
- Exactitud de datos  
- Funcionamiento de filtros  
- Legibilidad de exportaciones  
- Integridad del formato  

## 9.4 Documentación
Actualización del manual de usuario y documentación técnica.

---

# 10. Beneficios Esperados

- Reducción de tiempo en generación de reportes  
- Eliminación de errores manuales  
- Mayor trazabilidad  
- Mayor productividad administrativa  

---

# 11. Impacto en la Mantenibilidad y Calidad

## 11.1 Mantenibilidad
- Arquitectura modular (MVC)  
- Código documentado  
- Uso de librerías estándar  

## 11.2 Calidad del sistema
- Mayor confiabilidad  
- Mejor experiencia de usuario  
- Mejor organización interna del sistema  

---

# 12. Justificación del Proyecto de Mantenimiento

El estudio evidenció fallas técnicas, vulnerabilidades, cambios normativos y carencias funcionales.  
Se aplicaron mantenimientos correctivo, adaptativo, preventivo y perfectivo.

Además, se planteó un módulo de reportes automáticos que mejora la eficiencia y reduce errores humanos.

---

# 13. Reflexión Final

El mantenimiento de software es una actividad continua que garantiza la vigencia, confiabilidad y eficiencia del sistema.

El caso estudiado demuestra que:

- El mantenimiento va más allá de corregir errores.  
- La arquitectura modular reduce costos futuros.  
- Las mejoras funcionales aumentan la usabilidad.  
- La documentación adecuada facilita nuevas actualizaciones.  

La implementación del módulo de reportes refuerza la calidad general del sistema y lo prepara para exigencias tecnológicas actuales.
