# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 2 - Modelo de Información y Diagrama de Contexto

## 👥 Integrantes del equipo
- Darek Aljuri (darekalma)
- Valentina Ruiz (valeruizto)
- Santiago Soler (san1tago)

## 🧠 Descripción general del trabajo
El objetivo del Taller 2 fue modelar la estructura de información y el contexto operativo del caso base "Clínica Salud Viva", mediante la elaboración de un Modelo Entidad-Relación (ERD) y un Diagrama de Contexto de Negocio. El propósito fue identificar las entidades principales del dominio clínico, sus relaciones y los flujos de información entre actores y sistemas, asegurando coherencia con los procesos administrativos y clínicos descritos.

La actividad se desarrolló inicialmente analizando el caso base, identificando las entidades nucleares (Paciente, Cita, Médico, Especialidad y Factura) y las interacciones entre actores (paciente, médico, asistente, aseguradora) y sistemas (agendamiento, ERP, base de datos y notificaciones). Posteriormente, se estructuró el modelo conceptual y se organizaron los flujos de información con enfoque en claridad, trazabilidad y alineación con buenas prácticas de modelado.

---
## 🔧 Proceso de desarrollo
Explique cómo realizaron el trabajo: qué decisiones tomaron, qué herramientas utilizaron, qué aspectos modelaron primero y cómo lo fueron ajustando.
re
## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- Cómo se estructura el modelo entregado
- Cómo representa las necesidades del cliente
- Qué supuestos se tomaron

## 📈 Diagrama final entregado
> (Inserte aquí una imagen o enlace al modelo-final.drawio / .asta / PDF)

## 📋 Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Ej: Paciente        | Actor | Usuario que agenda una cita médica | Cliente |

## 🔍 Investigación complementaria
### Tema investigado:
Modelo Entidad-Relación en la industria y Diagramas de Contexto bajo el enfoque C4.

### Resumen:

El Modelo Entidad-Relación (ER), introducido por Peter Chen en 1976, continúa siendo una herramienta fundamental para el modelado conceptual de datos en sistemas empresariales. En la práctica industrial, suele utilizarse notación Crow’s Foot por su claridad al representar cardinalidades y dependencias entre entidades. Este tipo de modelado permite alinear los requerimientos del negocio con la estructura de información antes de su implementación técnica.

Por otra parte, los Diagramas de Contexto han evolucionado en marcos modernos como el C4 Model, donde el nivel "System Context" describe cómo un sistema interactúa con usuarios y sistemas externos. Este enfoque facilita la comunicación entre áreas técnicas y de negocio al enfocarse en flujos de información y responsabilidades, sin entrar en detalles de infraestructura o implementación.

En el sector salud, estándares como HL7 FHIR demuestran cómo entidades como "Appointment" (Cita) deben estructurarse para permitir interoperabilidad entre plataformas clínicas y aseguradoras. Esto evidencia la importancia de un modelo conceptual sólido que pueda escalar hacia integraciones reales.

---

## 📚 Referencias
- [1] Apellido, Nombre. *Título*. Año. URL o DOI.
- [2] Fuente oficial BPMN: https://www.omg.org/spec/BPMN/

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
