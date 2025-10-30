# Cómo realizar búsquedas de información y comparativas técnicas

## 1. Objetivo de la búsqueda de información

La primera fase de cualquier proyecto técnico consiste en **recopilar información fiable y actualizada** que permita:

* Comprender el **problema o necesidad** que se quiere resolver.
* Conocer las **tecnologías existentes** y sus posibilidades.
* Seleccionar la **alternativa más adecuada** en función de los recursos, objetivos y limitaciones del proyecto.

> En el módulo de Proyecto, esta fase es clave antes de diseñar o planificar: sin un buen análisis previo, el proyecto puede basarse en suposiciones erróneas.

---

## 2. Fuentes de información recomendadas

### a) **Fuentes primarias**

Información generada directamente por quienes desarrollan o utilizan la tecnología.

* **Documentación oficial** (manuales, guías de instalación, API docs).
* **Repositorios de código** (GitHub, GitLab, SourceForge).
* **Foros técnicos y comunidades** (Stack Overflow, Reddit r/sysadmin).
* **Whitepapers y artículos técnicos** de fabricantes (Red Hat, VMware, Cisco, Microsoft).

### b) **Fuentes secundarias**

Analizan, interpretan o comparan información de varias fuentes primarias.

* Blogs técnicos y medios especializados (Xataka, MuyLinux, TechRepublic).
* Artículos académicos o publicaciones de IEEE, ACM, etc.
* Cursos y tutoriales en línea (edX, Udemy, Coursera).
* Reseñas o benchmarks comparativos (Phoronix, DistroWatch, ServerWatch).

### c) **Fuentes institucionales**

* Normativa oficial (BOE, BOJA, ENISA, INCIBE).
* Guías de buenas prácticas (ISO, ITIL, NIST).
* Documentos de administraciones o universidades.

---

## 3. Cómo planificar la búsqueda

### Paso 1 – Definir el objetivo de búsqueda

Antes de buscar, **define con claridad qué información necesitas**.
Ejemplo:

> “Comparar diferentes hipervisores para un entorno educativo virtualizado.”

Pregúntate:

* ¿Qué quiero saber exactamente?
* ¿Qué decisión necesito tomar con esta información?
* ¿Qué criterios son relevantes (rendimiento, licencia, compatibilidad, soporte…)?

---

### Paso 2 – Seleccionar palabras clave (keywords)

Piensa como un motor de búsqueda: usa **términos concretos y técnicos**.
Ejemplo:

> `"open source hypervisor comparison 2025 performance"`
> `"Zabbix vs Prometheus monitoring tools linux"`

Puedes combinarr operadores lógicos:

* `AND`: reduce resultados (ej. “Linux AND firewall”)
* `OR`: amplía resultados (ej. “virtualization OR containerization”)
* `-` (guion): excluye (ej. “Debian server -Ubuntu”)
* `"entre comillas"`: busca coincidencia exacta.

---

### Paso 3 – Evaluar la fiabilidad de la fuente

No toda la información técnica en Internet es válida.
Comprueba:

* **Autoría y fecha de publicación.**
* **Reputación del sitio.** (¿es oficial o de una comunidad reconocida?)
* **Evidencias o pruebas.** (¿aporta datos, comparativas o ejemplos reproducibles?)
* **Neutralidad.** (¿es una opinión comercial o un análisis objetivo?)

---

### Paso 4 – Organizar y registrar la información

Usa una **tabla o ficha de investigación** para no perder la trazabilidad.
Ejemplo en Markdown:

| Fuente                       | Tipo         | Resumen                                             | Fiabilidad (1–5) | Enlace                                                    |
| ---------------------------- | ------------ | --------------------------------------------------- | ---------------- | --------------------------------------------------------- |
| Documentation – Proxmox VE 8 | Oficial      | Entorno completo de virtualización con interfaz web | 5                | [https://proxmox.com](https://proxmox.com)                |
| Blog – TechRepublic          | Blog técnico | Comparativa Proxmox vs VMware                       | 4                | [https://techrepublic.com/](https://techrepublic.com/)... |
| Foro – Reddit /r/sysadmin    | Comunidad    | Opiniones de uso real en pymes                      | 3                | [https://reddit.com/](https://reddit.com/)...             |

---

## 4. Investigación de alternativas

Una vez recopilada la información, el siguiente paso es **identificar las posibles soluciones** (alternativas tecnológicas o de diseño).

> Ejemplo:
> “Para desplegar una nube privada se pueden usar Proxmox, OpenStack, o VMware vSphere.”

### Criterios a comparar:
Recuerda que esto son ejemplos, no tienen que ser los mismos.

| Tipo             | Ejemplos de criterios                                     |
| ---------------- | --------------------------------------------------------- |
| **Técnicos**     | Compatibilidad, rendimiento, escalabilidad, seguridad     |
| **Económicos**   | Coste de licencia, mantenimiento, hardware                |
| **Operativos**   | Facilidad de uso, curva de aprendizaje, soporte           |
| **Comunitarios** | Popularidad, frecuencia de actualizaciones, documentación |
| **Sostenibles**  | Consumo energético, mantenimiento a largo plazo           |

---

## 5. Cómo realizar una comparativa técnica

### Paso 1 – Seleccionar las herramientas o alternativas

Elige **entre 2 y 4 opciones** que respondan al mismo problema.

### Paso 2 – Definir los criterios de evaluación

Por ejemplo:

* Requisitos mínimos de hardware
* Escalabilidad
* Licencia
* Soporte multiplataforma
* Nivel de automatización
* Integración con contenedores o CI/CD

### Paso 3 – Asignar puntuaciones

Crea una **matriz comparativa** con valores (1–5) o símbolos (+ / ± / –).

| Criterio               | Proxmox | OpenStack | VMware ESXi   |
| ---------------------- | ------- | --------- | ------------- |
| Licencia               | Libre     | Libre       | Propietaria |
| Facilidad de uso       | Alta      | Baja        | Media          |
| Escalabilidad          | Media-baja| Media-alta  | Media-alta          |
| Soporte y comunidad    | Alto      | Medio       | Alto          |
| Integración con Docker | edia-alta | Media-baja       | Baja  |

### Paso 4️⃣ – Conclusiones

Resume de forma objetiva:

> “Proxmox resulta la opción más equilibrada para un entorno educativo por su simplicidad, soporte activo y coste nulo. VMware ofrece mejor rendimiento, pero su licencia lo hace menos viable.”

---

## 6. Herramientas útiles para gestionar la información

* **Google Scholar** → artículos académicos.
* **DuckDuckGo / StartPage** → búsquedas.
* **ChatGPT o Perplexity.ai** → resumen y filtrado inicial de fuentes.
* **Wikipedia/Grokpedia** → Enciclopedia libre/autogenerada.
* **Zotero o Notion** → gestión de bibliografía y notas.
* **GitHub / GitLab** → documentación y código de herramientas reales.
* **Hoja de cálculo o Markdown** → registro comparativo de opciones.

---

## 7. Buenas prácticas de investigación técnica

- Contrasta **varias fuentes diferentes (mínimo minimísimo 3)**.
- Prioriza **documentación oficial** y fuentes recientes.
- Guarda las **URL y fechas de consulta**.
- No te limites a “qué hace” una herramienta: analiza **cómo lo hace y con qué requisitos**.
- Utiliza **criterios homogéneos** en todas las comparativas.
- Expón las conclusiones de forma **objetiva y razonada** (no por preferencia personal).

---

## 8. Relación con el módulo PI

En el **RA2 (Diseño del proyecto)**:

* Permite justificar las **decisiones técnicas** tomadas.
* Demuestra la **capacidad de análisis e investigación**.
* Favorece la **documentación profesional** del proyecto.
* Prepara la base para la **evaluación de viabilidad técnica y económica**.