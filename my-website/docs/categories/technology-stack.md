---
title: Technology Stack
sidebar_label: Technology Stack
sidebar_position: 7
---

# Technology Stack

Feedback relacionado con las tecnologías utilizadas y decisiones técnicas.

---

## ✅ Lo que funciona

* **Orden conceptual**: Presentar primero la metodología de desarrollo y posteriormente el stack tecnológico ayuda a contextualizar mejor las decisiones técnicas.

* **Justificación de las decisiones**: Justificar claramente las tecnologías elegidas demuestra que las decisiones técnicas están alineadas con las necesidades del proyecto.

* **Uso de tecnologías probadas**: Priorizar APIs, herramientas y tecnologías ampliamente adoptadas facilita la integración, el soporte y la mantenibilidad del sistema.

* **Contemplar los riesgos del stack**: Incluir un análisis de riesgos asociado al stack tecnológico permite anticipar posibles problemas técnicos y planificar medidas de mitigación.

* **Contemplar el estudio previo**: Analizar la curva de aprendizaje de las tecnologías utilizadas ayuda a evaluar el impacto real en la planificación del proyecto.

* **Asociar las tecnologías a las diferentes partes del sistema**: Explicar con claridad cómo se integran las diferentes tecnologías dentro del sistema mejora la comprensión de la arquitectura del proyecto.

* **Tener en cuenta las condiciones de uso**: Analizar licencias y condiciones de uso de herramientas o librerías open source ayuda a evitar problemas legales o costes inesperados. Puesto que algunas herramientas son open-source y gratuitas dependiendo de si tu proyecto tiene como fin un beneficio económico o no

* **Contemplar que las herramientas puedan usarse durante todo el proyecto**: Tener en cuenta la sostenibilidad de créditos, licencias o recursos externos garantiza que las herramientas puedan mantenerse durante todo el desarrollo del proyecto.

* **Implementar CI/CD**: Implementar sistemas de integración continua y aseguramiento de calidad del código desde el inicio contribuye a mantener la estabilidad del proyecto a largo plazo.

* **Contemplar los diferentes proveedores de despliegue**: Analizar qué proveedor se ajusta más a nuestras necesidades, puesto que necesitamos entre otras cosas despliegues "congelados" (es decir, que desde que se despliegan, su contenido no varie)

* **Estrategia de Testing Estructurada**: Organizar el plan de pruebas siguiendo un orden lógico (pruebas unitarias, de integración, E2E, etc.) proporciona una visión clara de la robustez del software.

---

## ❌ Lo que no funciona

* **Justificar las decisiones**: Presentar el stack tecnológico sin justificar por qué se han elegido esas tecnologías genera dudas sobre las decisiones técnicas del proyecto.

* **Valorar el riesgo de la curva de aprendizaje**: Elegir tecnologías poco conocidas o poco adoptadas sin un motivo claro puede dificultar la integración y el mantenimiento del sistema. Además, no considerar la curva de aprendizaje de varias tecnologías simultáneamente puede afectar negativamente al ritmo de desarrollo.

* **No contemplar riesgos**: No analizar los riesgos asociados a las tecnologías utilizadas puede provocar problemas técnicos imprevistos durante el desarrollo.

* **Desconocimiento de las condiciones de uso**: No revisar las condiciones de uso o licencias de herramientas open source puede generar costes o limitaciones inesperadas.

* **No tener en cuenta la sostenibilidad de la herramienta**: No considerar la sostenibilidad de créditos o recursos externos puede provocar bloqueos técnicos antes de finalizar el proyecto.

* **No contemplar la calidad del código**: No establecer desde el inicio mecanismos de aseguramiento de calidad del código o integración continua puede generar problemas acumulados en fases posteriores del desarrollo.

* **No explicar bien los proveedores**: No analizar correctamente los proveedores de despligue con sus consecuentes riesgos y ventajas, puede acarrear problemas a la hora de desplegar

* **Malinterpretación del Código Duplicado en Tests**: Considerar el código repetido en los archivos de test como una penalización técnica. En el contexto de testing, la claridad y el aislamiento de las pruebas priman sobre la eliminación estricta de duplicación (DRY).


---
