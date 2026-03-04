---
title: Devising a Project
sidebar_label: DP
sidebar_position: 1
---

##  [Primera Mitad S1] - Fecha: 26/02/2026

###  1. Nuestro Feedback Directo
*Anotaciones sobre lo que los profesores han comentado específicamente sobre nuestra presentación y proyecto.*

* 🟢 **Fortalezas (Qué hemos hecho bien):**
  * **Killer Opener y Cierre:** El "killer" funciona porque deja claro lo que aportamos. Muy buen eslogan/alegato final.
  * **Gestión Agile:** Buena adaptación del sprint (aunque falta aclarar el método para las weeklys).

*  **Debilidades (Qué tenemos que mejorar/corregir):**
  * **Gestión del tiempo (Crítico):** Peor imposible. Más de 5 minutos solo con la idea inicial y demasiado detalle innecesario en la metodología. Necesitamos planes de contingencia por si el grupo anterior se pasa de tiempo.
  * **Foco y Priorización:** Explicar login y registro no es core; hay cosas más interesantes. Hay que aplicar "First things first" (poner primero lo importante, de izquierda a derecha y de arriba a abajo).
  * **Métricas y Commitment Agreement:** Las métricas actuales son demasiado generales (blanco y negro). Medir el rendimiento requiere diferenciar roles (no es lo mismo evaluar a un coordinador, a un dev o a un documentador).
  * **Seguimiento de Riesgos:** Falta información clave sobre los problemas encontrados. Hay que especificar si eran riesgos ya identificados, su estado (resuelto/en proceso), porcentajes de resolución (no solo "lecciones aprendidas") y usar métricas para evaluar las medidas de contención.
  * **Herramientas y QA:** Cuidado con SonarQube/análisis estático y la cobertura (depende de muchos factores). Cuidado con hacer pruebas de rendimiento en producción (pueden fundir los créditos, son para preproducción).
  * **Formas y Visuales:** Queda raro contar los problemas de un compañero estando presente. En el Gantt hay poco contraste (poco texto negro sobre color) y hay huecos desaprovechados. Faltó mostrar gráficas de evolución del código.

* 🛠️ **Acciones Tomadas / A realizar (Planificación próxima semana):**
  * **⚠️ IMPORTANTE - Usuarios Piloto:** Durante el S2 se nos asignarán 2 grupos de usuarios piloto internos. Tendremos una tarea extra: realizar un máximo de 6 horas de revisión a otro grupo. Debe haber al menos 2 personas por caso de uso core. Hay que establecer un modelo de gestión y una fecha tope para enviar/recibir este feedback.
  * **DEMO y Presentación (16 minutos clavados):** La próxima semana hay que hacer una DEMO real (directo o vídeo, pero nada de mockups). Reestructurar la presentación para incluir el "Killer opener", stack tecnológico (con despliegue de entregas), y análisis financiero breve (presupuesto y competencia).
  * **Retrospectiva del S1:** Análisis detallado del S1 completado vs. previsto, evolución del código (gráficas), desviaciones de los miembros (anonimizadas) y revisión del plan para detallar profundamente el S2 (y por encima el S3).
  * **Revisión de Métricas:** Crear una "tier list" anónima y definir métricas de rendimiento realistas y específicas por rol. Explicitar los sistemas de CI/CD.
  * **Pipeline de Calidad (Feedback Antiguo Alumno):** Asegurar un buen pipeline de CI/CD desde ya para garantizar la calidad del código; aunque cueste al principio, ahorrará mucho tiempo después.

###  2. Feedback General (Conocimiento Transversal)
*Anotaciones objetivas y aprendizajes generales comentados durante las exposiciones del resto de grupos.*

* **Requisitos y Evaluación:**
  * **Soporte Visual:** Comprobar la checklist sobre la presentación, no sobre el discurso. Si no hay soporte visual de algo exigido = SUSPENSO.
  * **Cumplimiento:** Que se note que cada miembro cumple el commitment agreement.
  * **Comportamiento:** Tolerancia cero a hablar mientras exponen los compañeros.

* **Negocio y Finanzas:**
  * **Análisis de Costes (CAPEX vs OPEX):** Diferenciar entre costes de capital (compras amortizables, ej. servidores) y costes operativos (servicios contratados no amortizables).
  * **Salarios:** Diferenciar claramente entre salario neto, bruto y el coste real para la empresa (que incluye Seguridad Social y es casi el doble del neto).

* **Gestión de Proyecto y Equipo:**
  * **Usuarios Piloto:** Deben ser de todo tipo, con perfiles más y menos técnicos. Es vital recibir su feedback y responder ante ellos (entrevistas).
  * **Trazabilidad S1/S2:** Para el S1 no basta con un Gantt; hay que especificar qué está hecho, qué no, y cómo se ha solucionado. El S2 debe venir ultra detallado.
  * **Riesgos:** Mantener siempre el hilo conductor y dejar muy claro cómo se solucionan los riesgos y cómo se aplican esas soluciones.
  * **Team Building:** Recomendación de hacer "team meetings" (quedadas de grupo más relajadas).

---

##  [Entrega 2: S1] - Fecha: 19/02/2026

###  1. Nuestro Feedback Directo
*Anotaciones sobre lo que los profesores han comentado específicamente sobre nuestra presentación y proyecto.*

* 🟢 **Fortalezas (Qué hemos hecho bien):**
  * **Diseño y fluidez:** Diseño muy bueno, limpio y atractivo. Exposición muy bien hilada, coherente y fluida. 
  * **Producto visual:** Muy buenos mockups. Buen uso de colores intensos en la matriz DAFO.
  * **Enganche inicial:** Les ha gustado mucho el comienzo y cómo se presentó la idea de la app.
  * **Validación real (Gran punto):** Muy bien valorado el hecho de salir a la calle e ir a una residencia a hablar con un usuario real.

* 🔴 **Debilidades (Qué tenemos que mejorar/corregir):**
  * **Falta de síntesis en la idea:** Hace falta resumir la idea en una sola frase (Elevator pitch).
  * **Carencias visuales y de datos:** Alguna slide necesita estar mejor ilustrada (ej: pros y contras). Al planning de los sprints (Gantt) le falta texto explicativo.
  * **Análisis de competencia:** Cuidado al hablar de competidores "legacy"; no usar argumentos subjetivos (como "interfaz moderna e intuitiva"), sino centrarse en el CORE y el diferenciador real.
  * **Commitment Agreement:** Faltaba información clave (por ejemplo, mencionar herramientas como Clockify).

* 🛠️ **Acciones Tomadas / A realizar:**
  * **Migración de Base de Conocimiento:** Abandono del Excel y paso a "documentación como código" (Markdown en repositorio) para mejorar la agilidad y trazabilidad, tal como sugirieron.
  * **Pruebas de entorno:** Aprovechar el acceso al aula los miércoles (14:30-15:30) para pedir el mando y probar la proyección (legibilidad y tema de la pantalla baja).
  * **Refinamiento de discurso:** Redactar el Elevator Pitch de una frase y corregir las métricas de la competencia por datos objetivos.
  * **Actualización de entregables:** Incluir la info de Clockify en el Commitment Agreement.

###  2. Feedback General (Conocimiento Transversal)
*Anotaciones objetivas y aprendizajes generales comentados durante las exposiciones del resto de grupos.*

* **Presentación y Puesta en escena:**
  * **Killer Opener:** Hacerlo incluyendo al público, pero con cuidado de no entrar en temas polémicos.
  * **Storytelling:** Mantener un buen hilo argumental y enlazar bien los distintos puntos.
  * **Gestión del tiempo:** Preparar diapositivas extra (que parezcan parte natural de la presentación) para entrar en detalle si se va demasiado rápido.
  * **Legibilidad:** Controlar que los textos se lean bien y tener cuidado con la parte baja de la pantalla.

* **Gestión del Proyecto y Planificación:**
  * **Replanificación:** Contar con el tiempo extra que supondrá procesar el feedback de los usuarios piloto. ¿Cómo se va a lidiar con esa info?
  * **Calendario:** Tener en cuenta las semanas no lectivas para planificar los sprints.
  * **Trazabilidad:** Importancia de medir las acciones que se están tomando.

* **Requisitos y Herramientas:**
  * **Checklist:** Usar una checklist para asegurar que no falte contenido obligatorio (como tener un buen DAFO).
  * **Visuales obligatorios:** Lo que se pide explícitamente para cada semana tiene que tener soporte visual en las diapositivas sí o sí.
  * **Integración Continua (CI):** Ser mucho más explícitos al explicarla.
  * **Sostenibilidad de herramientas:** Probar y asegurar que los créditos/licencias de las herramientas elegidas aguantarán hasta el final del curso sin caducar.

---

##  [Entrega 1: DP] - Fecha: 12/02/2026

###  1. Nuestro Feedback Directo
*Anotaciones sobre lo que los profesores han comentado específicamente sobre nuestra presentación y proyecto.*

* 🟢 **Fortalezas (Lo que hemos logrado y debemos mantener):**
  * **Estrategia y negocio:** Idea clara desde el inicio con una diferenciación temprana. Justificación sólida de precios, competidores y plan de crecimiento. Segmentación correcta de usuarios piloto y feedback almacenado.
  * **Gestión técnica y de proyecto:** Mockups navegables y consideración de riesgos técnicos con CI/CD. Cumplimiento del "commitment agreement".
  * **Comunicación y diseño:** "Killer opener" conectado con utilidad real e inicio visual potente. Buen control del tiempo, ritmo y síntesis. Diseño estratégico (menos texto, marca unificada) y presentación autocontenida.

* 🔴 **Debilidades (Áreas de mejora y puntos de dolor):**
  * **Fallos en el mensaje y estrategia:** La idea no quedó clara al inicio y la diferenciación llegó tarde. Justificación débil de precios y una expansión mal definida.
  * **Gestión y organización:** Procesos y riesgos no explicados, segmentación poco clara y feedback sin estructurar.
  * **Puesta en escena (Formas):** Hablamos demasiado rápido, con redundancias y movimiento excesivo. Error crítico: Tapamos la pantalla y miramos solo al profesor.
  * **Errores de diseño visual:** Demasiado texto, letra pequeña y diapositivas sobrecargadas. DAFO y competidores poco visibles; información importante escondida. La presentación no era autocontenida y el esquema de colores no queda claro.

* 🛠️ **Acciones Tomadas / A realizar (Mejoras de formato y planificación):**
  * **Gestión de la atención:** Traslado de los códigos QR al final de la exposición para evitar distracciones y mantener el foco en el equipo.
  * **Planificación técnica:** Simplificación del diagrama de Gantt, detallado específicamente por sprints.
  * **Diseño visual:** Optimización del diseño reduciendo la carga de texto y aumentando el apoyo gráfico (imágenes) para facilitar la comprensión. Se indica el significado de cada leyenda o elemento visual.
  * **Puesta en escena:** Exposición reubicada; ya no se tapará la pantalla, los ponentes se posicionarán al lado.

###  2. Feedback General (Conocimiento Transversal)
*Anotaciones objetivas y aprendizajes generales comentados durante las exposiciones del resto de grupos.*

* **Integración Narrativa de Mockups:** Aunque tenemos mockups navegables, la recomendación general sugiere integrarlos mejor con historias de usuario en lugar de mostrarlos como pantallas aisladas.
* **Autocontención del Discurso:** Importancia de no dar por hecho que el tribunal recuerda los detalles de presentaciones anteriores; cada entrega debe entenderse por sí sola (refuerza nuestro punto de mejorar la claridad inicial).
* **Cobertura de Requisitos:** Recordatorio de revisar la rúbrica punto por punto para asegurar que no se queda ningún apartado obligatorio sin cubrir.
* **Participación Activa:** Necesidad de aportar feedback constructivo a los demás grupos durante sus exposiciones.
* **Refuerzo de Identidad:** Sugerencia de uso de elementos diferenciadores extra (ej: mascota o iconografía propia) para potenciar la marca visual.

---

##  [Entrega 1: DP] - Fecha: 05/02/2026

###  1. Nuestro Feedback Directo
*Anotaciones sobre lo que los profesores han comentado específicamente sobre nuestra presentación y proyecto.*

* 🟢 **Fortalezas (Qué hemos hecho bien):**
  * **Capacidad de ejecución:** Al pedirnos más casos de uso, reconocen que tenemos un equipo grande y capaz de asumir retos mayores que otros grupos.
  * **Tecnología:** Ya tenemos la base de IA integrada y la estructura SaaS planteada. La infraestructura técnica está encaminada, solo falta mejorar la venta y el enfoque comercial.

* 🔴 **Debilidades (Qué tenemos que mejorar/corregir):**
  * **Fallos en presentación y puesta en escena:** La presentación se ve cortada y sin pie de página en pantalla digital. Falta contacto visual con todo el público (mirar a las 4 esquinas). Apoyo visual insuficiente, especialmente en el análisis de competencia.
  * **Errores de producto y privacidad (Urgente):** Grave error mostrar teléfonos de vecinos en el chat. Votaciones y actas no alineadas con la normativa legal. Casos de uso escasos para el tamaño del equipo. Hay que centrarse solo en características que podamos cumplir.
  * **Estrategia y negocio:** Dependemos demasiado de la IA. ¿Pagarían solo por eso? El modelo SaaS y plan de precios no se entienden bien. No está claro el target ni la edad objetivo. Necesidad de diferenciarse del grupo de mañana y de futuras apps con IA.

* 🛠️ **Acciones Tomadas / A realizar:**
  * **Pivotaje y estrategia:** Redefinición del producto hacia "Gestión de Residencias de Estudiantes" (target: dueños y estudiantes) para diferenciarnos totalmente del grupo de vecinos. Incorporación de funciones de valor añadido no dependientes de IA (reserva de zonas comunes y control de accesos QR).
  * **Privacidad y seguridad:** Eliminación definitiva de los números de teléfono visibles de los usuarios en la app.
  * **Presentación visual:** Comprobación previa de visualización en pantalla digital para evitar cortes. Desglose del contenido en mayor número de diapositivas para mejorar la legibilidad.

###  2. Feedback General (Conocimiento Transversal)
*Anotaciones objetivas y aprendizajes generales comentados durante las exposiciones del resto de grupos.*

* **Sostenibilidad y masa crítica:** Se plantearon dudas a nivel global sobre la viabilidad de las funcionalidades sociales si no se alcanza un volumen de usuarios suficiente rápidamente.
* **Valor Institucional (B2B):** Necesidad de justificar mejor el valor para el cliente "institución" (quien paga) diferenciándolo claramente del valor para el usuario final (quien usa la app). Esto refuerza la necesidad de aclarar nuestro modelo de negocio.
* **Cobertura de requisitos:** Recordatorio general de cubrir todos los apartados exigidos en la hoja de evaluación, evitando omitir secciones obligatorias por falta de tiempo.
* **Control de Calidad (QA) en Proyección:** Importancia de realizar una revisión técnica previa en el proyector del aula para asegurar que la resolución no corta el contenido (esto confirma la causa raíz de nuestro fallo de visualización).

---