# 🎓 Proceso de Inscripción Intersemestral – FESC

## 🎯 Objetivo
Diseñar y modelar el **proceso completo de inscripción a cursos intersemestrales** en la FESC, aplicando los conceptos de **diagramas de actividades UML** para identificar puntos críticos y proponer mejoras técnicas.

---

## ⚙️ Actores del Proceso
- **Estudiante:** Inicia la inscripción, selecciona materias y realiza el pago.  
- **Sistema Académico:** Valida prerrequisitos, verifica cupos y registra inscripciones.  
- **Coordinación Académica:** Gestiona excepciones y autorizaciones especiales.  
- **Docente:** Recibe listado de inscritos y actualiza su grupo.  
- **Tesorería:** Procesa pagos y genera recibos oficiales.

---

## 🧩 Modelado del Proceso

### 🔹 Versión AS-IS (Proceso Actual)
Flujo con validaciones manuales y pasos secuenciales:

- Revisión de prerrequisitos y cupos con intervención humana.  
- Cálculo de pagos realizado por Tesorería.  
- Activación del aula virtual después de la conciliación de pago.  
- Comunicación tardía con docentes.

📄 **Archivo:** `diagrama_inscripcion_v1.puml`

---

### 🔹 Versión TO-BE (Proceso Optimizado)
Flujo automatizado con validaciones paralelas y pagos integrados:

- Validaciones automáticas mediante reglas de negocio.  
- Pasarela de pago con **confirmación en tiempo real (webhook)**.  
- Integración con LMS para activar el aula virtual automáticamente.  
- Notificaciones inmediatas a docentes y estudiantes.

📄 **Archivo:** `diagrama_inscripcion_v2.puml`

---

## 📊 Comparativa de Métricas

| Métrica | AS-IS | TO-BE | Mejora |
|----------|------:|------:|--------|
| Actividades totales | 29 | 26 | Reducción por automatización |
| Puntos de decisión | 6 | 5 | Decisiones más claras |
| Fork/Join | 2 | 3 | Mayor paralelización |
| Actores | 5 | 5 | Misma estructura |
| Automatización | Media | Alta | Integración API y pagos automáticos |
| Facilidad de uso | Media | Alta | Interfaz guiada y pagos integrados |

📊 **Archivo:** `metricas_proceso.xlsx`

---

## 🚀 Conclusiones
El modelo **TO-BE** mejora la eficiencia general del proceso, reduce errores humanos y acelera la confirmación de inscripciones mediante automatización e integración de sistemas.  
El estudiante obtiene una experiencia más fluida, mientras que la institución optimiza sus tiempos de validación y conciliación.

---

## 📂 Archivos del Proyecto

| Archivo | Descripción |
|----------|-------------|
| `diagrama_inscripcion_v1.puml` | Diagrama del proceso actual (AS-IS). |
| `diagrama_inscripcion_v2.puml` | Diagrama optimizado (TO-BE). |
| `diagrama_inscripcion_v1.png` | Diagrama del proceso actual (AS-IS). |
| `diagrama_inscripcion_v2.png` | Diagrama optimizado (TO-BE). |
| `metricas_proceso.xlsx` | Análisis de métricas comparativas. |
| `mejoras_propuestas.pptx` | Presentación resumen (5 diapositivas). |
| `diagrama_inscripcion.drawio` | Diagrama v1 y v2 en drawio. |

---

## 👨‍💻 Autor
**Néstor Iván Granados Valenzuela**  
Estudiante de Ingeniería de Software  
📅 Año: 2025
