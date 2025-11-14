# Aplicación de Control de Asistencia: Análisis, Requerimientos y Uso de Control de Versiones

## 1. Introducción

La Aplicación de Control de Asistencia es un sistema orientado a automatizar los procesos de registro de asistencia en entornos educativos mediante el uso de códigos QR, validación de horarios y mecanismos de auditoría. Su objetivo principal es facilitar el trabajo docente, optimizar la gestión académica diaria y proporcionar a los estudiantes una herramienta confiable para consultar su historial de asistencia.

Este sistema está dirigido a instituciones educativas que buscan modernizar y digitalizar sus procesos internos mediante soluciones eficientes, seguras y escalables. Su diseño integra principios de ingeniería de software, buenas prácticas de documentación y el uso adecuado de control de versiones.

---

## 2. Objetivos del Sistema

- Desarrollar una herramienta funcional para registrar asistencias por sesión de clase.  
- Aplicar principios de ingeniería de software, incluyendo requerimientos, pruebas y validación.  
- Utilizar un sistema de control de versiones mediante Git y GitHub.  
- Documentar el avance del caso utilizando estándar profesional en formato Markdown.  
- Garantizar un registro seguro, verificable y ágil de la asistencia estudiantil.

---

## 3. Requerimientos del Sistema

### 3.1 Requerimientos funcionales

- Registrar asistencia mediante el escaneo de códigos QR.  
- Permitir registro manual con los estados: **Presente**, **Tarde** y **Ausente**.  
- Validar que el registro se realice únicamente dentro de la ventana horaria establecida.  
- Generación de reportes filtrables y exportación en formato CSV.  
- Enviar notificaciones automáticas cuando un estudiante supere umbrales de inasistencias o tardanzas.  
- Registrar cambios y modificaciones en una bitácora de auditoría.  
- Permitir cerrar o anular sesiones de clase según permisos del docente.

### 3.2 Requerimientos no funcionales

- Interfaz intuitiva, accesible y optimizada tanto para web como para dispositivos móviles.  
- Tiempo de respuesta menor a 2 segundos por registro.  
- Alta disponibilidad (≥ 99 %) durante el horario académico.  
- Seguridad mediante HTTPS, autenticación basada en roles y registros inmutables.  
- Compatibilidad con navegadores modernos, Android y iOS.

---

## 4. Pruebas Funcionales

A continuación se presenta una tabla de casos de prueba diseñados para validar la funcionalidad del sistema:

| Caso de prueba              | Entrada                          | Resultado esperado                           | Validación |
|-----------------------------|----------------------------------|-----------------------------------------------|------------|
| **CP1 – Registro válido por QR** | Escaneo correcto del QR         | Marca “Presente” en ≤ 2 s                     | ✔ Correcto |
| **CP2 – Fuera de horario**       | Escaneo fuera de la ventana     | Registro rechazado                            | ✔ Correcto |
| **CP3 – Duplicado de QR**        | Escaneo repetido del mismo QR   | Error: “QR ya registrado”                     | ✔ Correcto |
| **CP4 – Corrección manual**      | Estado modificado por docente    | Bitácora registra usuario, fecha y motivo     | ✔ Correcto |
| **CP5 – Notificación por umbral**| Estudiante supera límite         | Se envía notificación automática              | ✔ Correcto |

---

## 5. Tipo de Mantenimiento Propuesto

### **Mantenimiento Perfectivo**

El mantenimiento realizado se centra en mejorar las funcionalidades existentes sin alterar el propósito central del sistema. Este tipo de mantenimiento permite refinar procesos internos, optimizar el rendimiento y mejorar la experiencia de los usuarios.

### Mejoras implementadas o sugeridas

- Panel de estadísticas con indicadores de asistencia.  
- Filtros avanzados en los reportes.  
- Exportación de reportes a PDF y visualizaciones gráficas.  
- Generación automática de códigos QR dinámicos por sesión.  
- Modo offline temporal con sincronización posterior.

Estas mejoras contribuyen a aumentar la eficiencia operativa y accesibilidad de los datos, además de reforzar la calidad general del sistema.

---

## 6. Reflexión sobre el Uso del Control de Versiones

El control de versiones desempeñó un papel fundamental en la organización del proyecto. A través de Git y GitHub fue posible:

- Registrar cambios mediante commits descriptivos.  
- Comparar versiones de manera segura (por ejemplo, **DRS_v1** vs **DRS_v2**).  
- Facilitar el trabajo colaborativo sin riesgo de pérdida de información.  
- Mantener la documentación del caso en un repositorio centralizado.  

El uso disciplinado del control de versiones garantiza orden, trazabilidad y coordinación durante el ciclo de vida del software, además de permitir auditoría y mantenimiento continuo.

---

## 7. Tipos de Sistemas de Control de Versiones

### 7.1 Sistemas locales

- Cada desarrollador mantiene su propio historial en su máquina.  
- **Ventajas:** simplicidad y rapidez.  
- **Desventajas:** alto riesgo de pérdida y poca colaboración.

### 7.2 Sistemas centralizados

- Un servidor principal almacena el repositorio.  
- **Ventajas:** control centralizado y seguridad.  
- **Desventajas:** dependencia total del servidor.  
- **Ejemplo:** Subversion (SVN).

### 7.3 Sistemas distribuidos

- Cada desarrollador posee una copia completa del repositorio.  
- **Ventajas:** trabajo sin conexión, rapidez y flexibilidad.  
- **Ejemplo:** Git (el sistema más utilizado en la actualidad).

---

## 8. Elementos y Operaciones Básicas en Git

- **Repositorio:** contiene el historial de cambios del proyecto.  
- **Working Copy:** área de trabajo local del desarrollador.  
- **Commit:** registra un conjunto de cambios en el historial.  
- **Log:** muestra el registro de versiones y modificaciones.  
- **Checkout:** permite cambiar de rama o recuperar versiones anteriores.  
- **Branch:** crea una línea paralela para funcionalidades nuevas.  
- **Push/Pull:** sincroniza cambios entre repositorio local y remoto.

---

## 9. GitHub en el Proyecto

GitHub fue utilizado como plataforma principal para:

- Centralizar todos los documentos del caso de estudio.  
- Subir versiones actualizadas del DRS y del Plan de Pruebas.  
- Mantener un historial ordenado y limpio del proyecto.  
- Facilitar la revisión y colaboración entre estudiantes y docentes.

---

## 10. Autor

**Brian Enric Andrade Muño**

