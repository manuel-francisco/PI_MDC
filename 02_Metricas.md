# Elaboración de métricas para medir la consecución de los objetivos

## 1. Qué son las métricas

Las **métricas** son **indicadores cuantitativos o cualitativos** que permiten **evaluar el grado de cumplimiento** de los **objetivos** establecidos en un proyecto.
Sirven para responder a preguntas como:

* ¿Se está alcanzando el objetivo propuesto?
* ¿En qué medida se están cumpliendo los plazos, costes y calidad previstos?
* ¿Qué aspectos deben corregirse o mejorarse?

---

## 2. Relación entre objetivos e indicadores

Cada **objetivo** debe ir acompañado de **una o más métricas** que permitan medir su cumplimiento.
Por ejemplo:

| Tipo de objetivo | Ejemplo                                           | Posible métrica                               |
| ---------------- | ------------------------------------------------- | --------------------------------------------- |
| Técnico          | Configurar una red con alta disponibilidad        | % de tiempo de disponibilidad (>99%)          |
| Económico        | Reducir el coste del servicio                     | Coste mensual respecto al presupuesto inicial |
| Temporal         | Finalizar la fase de pruebas antes del 15 de mayo | Cumplimiento del cronograma (%)               |
| De calidad       | Garantizar un despliegue sin incidencias críticas | Nº de incidencias críticas detectadas         |

---

## 3. Tipos de métricas

### a) **Cuantitativas**

Son las más objetivas. Se expresan en números o porcentajes.

* Ejemplos:

  * Tiempo medio de respuesta del servidor (ms)
  * Número de errores por 1000 líneas de código
  * Tasa de cumplimiento del cronograma (%)
  * Ratio de tareas completadas / tareas planificadas

### b) **Cualitativas**

Evalúan aspectos más subjetivos o de percepción.

* Ejemplos:

  * Satisfacción del cliente (escala 1–5)
  * Grado de comprensión del manual técnico
  * Nivel de documentación entregada

---

## 4. Cómo definir buenas métricas: criterios SMART

Una buena métrica debe cumplir con los criterios **SMART**:

* **S** (Specific): Específica → qué se mide exactamente.
* **M** (Measurable): Medible → que se pueda cuantificar o verificar.
* **A** (Achievable): Alcanzable → realista con los recursos del proyecto.
* **R** (Relevant): Relevante → vinculada directamente con el objetivo.
* **T** (Time-bound): Temporal → asociada a un periodo concreto.

> Ejemplo:
> “Reducir el tiempo de despliegue del servidor en un 25% antes de final del trimestre.”
> Es específico, medible, alcanzable, relevante y limitado en el tiempo.

---

## 5. Etapas para elaborar las métricas

1. **Definir los objetivos concretos del proyecto.**
   → Ejemplo: “Mejorar la disponibilidad de los servicios web.”

2. **Identificar qué variables reflejan el éxito.**
   → Tiempo de disponibilidad, número de caídas, tiempo medio de recuperación.

3. **Seleccionar los indicadores más representativos.**
   → “% de disponibilidad mensual”, “MTTR (Mean Time To Repair)”.

4. **Definir el método de medición y las fuentes de datos.**
   → Logs del sistema, herramientas de monitorización, encuestas.

5. **Establecer un valor objetivo (meta).**
   → “Disponibilidad ≥ 99,5 % mensual.”

6. **Determinar la frecuencia de medición.**
   → Diaria, semanal, al cierre de cada fase, etc.

7. **Registrar y analizar los resultados.**
   → Comparar resultados reales vs. metas → elaborar conclusiones.

---

## 6. Ejemplo aplicado a un proyecto de administración de sistemas

| Objetivo                                 | Métrica                          | Método de medición                   | Meta     | Frecuencia        |
| ---------------------------------------- | -------------------------------- | ------------------------------------ | -------- | ----------------- |
| Mantener disponibilidad del servicio web | % de uptime mensual              | Monitorización (UptimeRobot, Zabbix) | ≥ 99,5 % | Mensual           |
| Reducir incidencias de red               | Nº de incidencias reportadas     | Registro interno                     | ≤ 3/mes  | Mensual           |
| Mejorar la satisfacción del usuario      | Valoración en encuesta (1–5)     | Encuesta online                      | ≥ 4      | Final de proyecto |
| Cumplir el cronograma                    | % de tareas completadas a tiempo | Diagrama Gantt / GitHub issues       | ≥ 90 %   | Semanal           |

---

## 7. Integración en el seguimiento del proyecto (RA4)

En la fase de **seguimiento y control** (RA4 del módulo PI), las métricas se emplean para:

* Detectar **desviaciones** (tiempo, coste, calidad).
* Aplicar **acciones correctivas**.
* Documentar la **evaluación continua** y final del proyecto.
* Elaborar **informes de resultados** y **retroalimentación** para la mejora.

---

## 8. Instrumentos de recogida de datos

* **Registros automáticos:** logs, scripts, herramientas de monitorización.
* **Listas de verificación (checklists):** comprobación de tareas y entregables.
* **Cuadros de mando:** hojas de cálculo o dashboards.
* **Encuestas y formularios:** valoración de usuarios, tutores o clientes.
* **Reuniones de seguimiento:** revisión de objetivos y resultados parciales.

---

## 9. Presentación de resultados

Los resultados deben recogerse en un **informe de métricas**, que incluya:

* Descripción del objetivo medido.
* Valor esperado vs. valor obtenido.
* Interpretación (cumplido / parcialmente cumplido / no cumplido).
* Propuestas de mejora.

Ejemplo:

> **Objetivo:** Mantener la disponibilidad del servidor.
> **Resultado:** 99,2 % (meta 99,5 %).
> **Análisis:** Cumplimiento parcial. Se propone mejorar la redundancia de red.