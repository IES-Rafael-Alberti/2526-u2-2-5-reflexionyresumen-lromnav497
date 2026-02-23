# RESPUESTAS — Reflexión y Resumen (Plantilla genérica)

> **Actividad / ID:**  2.a..e - Reflexión y Resumen sobre la Unidad (Individual)
> **Unidad / Tema:**  Análisis de incidentes
> **Alumno/a:** Luis Carlos Romero Navarro
> **Fecha:**  23/02/2026

---

## 1) Reflexión crítica (preguntas)
Responde con **lenguaje técnico** y **argumentos** (no solo opiniones). Si procede, usa ejemplos, riesgos y decisiones justificadas.

### 1.1) ¿Qué te han parecido los temas tratados en la unidad?
- Ha estado distraida porque hace el ciclo real de la gestión de incidentes; desde como se clasifican, hasta como se documentan al final. Tambien por lo ultimo que hemos dado que es la detección con IDS/IPS/SIEM y el uso de OSINT para recopilar información.

- Cada cosa que hemos dado tiene su aplicacion dentro de un SOC. En general, lo que me parece que he visto en esta unidad es el trabajo que haría un analista L1 o L2 en un centro de operaciones de seguridad.

### 1.2) ¿Qué ha sido más útil para tu futuro puesto de trabajo? ¿Por qué?
- El aprender que es y como montar un SIEM, IDS e IPS para la detección y correlación de eventos y documentar los incidentes. Porque si me quiero dedicar a ser un analista pues es un punto a favor saber como funciona y el luego documentar cada incidente para que el cliente lo sepa entender de x manera y el equipo de una manera mas tecnica.

### 1.3) ¿Qué partes ya conocías y cuáles han sido nuevas para ti?
- Un poco de IDS/IPS ya lo sabia, que uno detecta y el otro bloquea, y que
hay organismos como INCIBE-CERT o CCN-CERT pero sin haber entrado
en sus guías nunca.

Lo que ha sido nuevo ha sido la taxonomía formal de incidentes y la profundidad de OSINT, no sabia
que hubiuera tantas herramientas.

### 1.4) ¿Qué concepto/idea te ha llamado más la atención y por qué?
- El SIEM porque es mucho mas practico que las otras cosas y ademas para el dia de mañana si trabajas de analista, se te es mas sencillo el adaptarte al que tenga la empresa en ese momento proque alfina la base es la misma. Ademas de que es mas entrenido que lo demas.

### 1.5) ¿Qué parte recortarías o simplificarías si hubiera menos tiempo? Justifica.
- Las diferencias entre SOC, CSIRT, CERT y CIRT. Está bien saberlo para
situarte pero para un analista junior no es lo que mas va a necesitar saber en mi opinion. Con una
explicación rapida va bien y ese tiempo lo metería en mas usos
con el SIEM porque es donde realmente se entiende como funciona todo.

### 1.6) ¿Qué tema has echado en falta o ampliarías? Justifica.
- Hacer un SIEM cada grupo y luego que los otros grupos lo ataquen y nosotros podamos ver y repsonder antes esos incidentes haciendo una taxonomia y alfinal todo el ciclo de gestionar incidentes.

### 1.7) ¿Qué aplicarías “mañana” en un entorno real con recursos limitados?
- Montaría SIEM open source,
con reglas básicas de fuerza bruta, integridad de ficheros y conexiones
a IPs con mala reputación. Tambien una auditoría OSINT rápida para ver que tiene expuesto la organización. Y una
plantilla para documentar incidentes, porque sin registro no hay
forma de aprender ni de demostrar lo que ha pasado.

### 1.8) ¿Qué duda, riesgo o punto crítico te queda abierto tras la unidad?
- El como gestionar bien los falsos positivos a gran escala, porque como se comento en clase un SIEM en produccion
genera cientos de alertas al día y la mayoría son falsas, si no tienes
un proceso de triage acabas ignorandolas por fatiga y el riesgo real aumenta.


## 2) Resumen esquematizado (obligatorio)
[Aqui, incluye **todos los puntos** vistos en la unidad. Prioriza esquema/tabla/listas con **contenido claro sobre los puntos importantes**, sobre párrafos largos que no aporten. **No olvides el resumen**]

## 2) Resumen esquematizado

| Bloque | Contenido principal | Herramientas / Referencias | Lo más importante |
|--------|--------------------|-----------------------------|-------------------|
| **A – Taxonomía (2a)** | Clasificación de incidentes por categorías: Malicious Code, Intrusion Attempts, Availability, Fraud... | Estándares eCSIRT / ENISA | Tener un lenguaje común para clasificar antes de responder |
| **B – Detección (2b)** | SOC, CSIRT, CERT, CIRT como estructuras organizativas. SIEM para correlacionar eventos, IDS para detectar, IPS para bloquear | ELK, Snort | La correlación de eventos es lo que convierte ruido en un ataque real |
| **C – Seguridad física (2c)** | Control de acceso físico, videovigilancia, detección de intrusiones físicas | — | La seguridad no es solo digital, el acceso físico también es un vector |
| **D – OSINT (2d)** | Recopilación de información en fuentes abiertas para investigar amenazas o auditar tu propia huella digital | theHarvester, Maltego, Google Dorks | Puedes ver lo que ve un atacante antes de que ataque |
| **E – Documentación (2e)** | Clasificar, valorar, documentar y hacer seguimiento de incidentes siguiendo guías nacionales | Guías INCIBE-CERT, CCN-CERT | Sin documentación no hay trazabilidad ni aprendizaje |

[Además, puedes completarlo con:]

### 2.1) Mapa/índice de la unidad (visión global)

- **Bloque A → Taxonomía (CE 2a):** antes de ponerte a detectar nada
  necesitas un lenguaje común para clasificar los incidentes, si no
  cada uno llama a las cosas de una manera diferente.

- **Bloque B → Monitorización y detección (CE 2b):** una vez sabes
  qué buscar, necesitas las herramientas para hacerlo: SOC, CSIRT,
  SIEM, IDS, IPS.

- **Bloque C → Seguridad física (CE 2c):** los incidentes no son
  solo digitales, el acceso físico, las cámaras y las intrusiones
  físicas también cuentan.

- **Bloque D → OSINT (CE 2d):** recopilar información de fuentes
  abiertas, tanto para investigar amenazas externas como para ver
  qué está exponiendo tu propia organización sin saberlo.

- **Bloque E → Documentación (CE 2e):** el cierre del ciclo,
  clasificar, valorar y documentar todo bien siguiendo las guías
  del INCIBE y el CCN-CERT.

### 2.2) Conceptos clave (lista breve)
- Taxonomía de incidentes: Es lo que grupa los incidentes en categorías. Su uso estandarizado facilita la comunicación y el reporte entre organizaciones y CERTs nacionales.
- SOC: Es el equipo dedicado a la monitorización 24/7 a la seguridad de una organización. Puede ser interno, externalizado o híbrido.
- CSIRT/CERT/CIRT son equipos de respuesta a incidentes El CERT tiene connotaciones históricas y a menudo de mandato público o sectorial; el CSIRT es el término más genérico y actual; el CIRT añade el foco en la continuidad de negocio. En la práctica, los tres términos se usan de forma casi intercambiable.
- SIEM es la plataforma que centraliza, normaliza y correlaciona logs y eventos procedentes de múltiples fuentes (firewalls, endpoints, servidores, aplicaciones). Nos permite detectar patrones de ataque que no veriamos examinando cada fuente por separado.
- OSINT es la metodología de recolección y análisis de información procedente de fuentes públicas y abiertas.
- IoC es cualquier artefacto observable que indica con alta probabilidad que un sistema ha sido comprometido.

### 2.3) Procesos / procedimientos (pasos o checklist)

**Proceso de auditoría OSINT:**

1. Definir el objetivo y el alcance que vamos a darle.
2. Recopilar información pasiva sin contactar con el objetivo.
3. Analizar y cruzar la información que saquemos.
4. Identificar posibles vectores de ataque.
5. Redactar el informe con las recomendaciones de mitigación.

---

**Gstión de incidentes:**

1. **Preparación:** Tener protecciones basicas antes de que pase algo como políticas, herramientas y plan de respuesta.

2. **Identificación y detección:** las herramientas generan alertas y el analista tiene que distinguir si es un verdadero positivo o no.

3. **Clasificación y valoración:** aplicar la taxonomía, asignar la categoría y severidad según los criterios de la guia nacional.

4. **Contención:** limitar el daño lo mas rpaido posible, aislar el sistema, bloquear IPs,etc.

5. **Erradicación y recuperación:** limpiar el vector de ataque, restaurar desde backups verificados y volver a la operación normal.

6. **Documentación y lecciones aprendidas:** redactar el informe técnico y actualizar los procedimientos para que no vuelva a pasar.

### 2.4) Herramientas / técnicas (si aplica)
- ELK es una plataforma SIEM de código abierto que integra detección de intrusiones en host, monitorización de integridad de ficheros, análisis de vulnerabilidades y gestión de alertas.
- Snort es IDS/IPS de red de código abierto basado en reglas.
- theHarvester es una herramienta OSINT para recolectar correos electrónicos, subdominios, IPs y nombres de empleados de un dominio objetivo mediante múltiples fuentes públicas (Google, LinkedIn, Shodan, etc.).
- Maltego es una plataforma de análisis de relaciones y visualización de grafos para OSINT. Permite conectar entidades (personas, dominios, IPs, organizaciones).
- Google Dorks son búsquedas avanzadas usando operadores especiales de Google (como site:, filetype:, inurl:, intitle:) para localizar información sensible indexada inadvertidamente: documentos internos, páginas de login expuestas, directorios abiertos, etc.
- MITRE ATT&CK es una base de conocimiento estructurada de tácticas, técnicas y procedimientos usados por actores de amenazas reales. Es el estándar de facto para describir comportamientos adversarios y mapear las detecciones del SIEM a fases del ataque.

### 2.5) Buenas prácticas y errores típicos

- **Normalizar los logs antes de meterlos al SIEM:** si no tienen el
  mismo formato y timestamps sincronizados, correlacionar eventos es
  un caos. El error típico es ingestarlo todo sin filtrar y luego
  ahogarte en ruido.

- **Documentar en tiempo real:** anotar cada acción con su timestamp
  mientras pasa, no al final del turno de memoria. Si lo dejas para
  después te falta detalle y la cronología no cuadra.

- **En OSINT, operar desde una red anónima:** VPN, máquina virtual o
  Tor, para no revelar que estás investigando. El error clásico es
  hacerlo desde la red corporativa y que el objetivo lo vea en sus
  logs.

- **Clasificar la severidad con criterios objetivos:** usar la guía
  nacional con sus criterios reales de impacto, no a ojo. Si lo haces
  a intuición te arriesgas a responder de forma desproporcionada o,
  peor, a quedarte corto ante algo crítico.

### 2.6) Glosario mínimo (términos y definiciones cortas)

- **Alert fatigue:** cuando hay tantas alertas que el analista acaba
  ignorándolas, y ahí es cuando se cuela lo importante.
- **APT:** actor con muchos recursos y paciencia, normalmente detrás
  hay espionaje o sabotaje, y puede estar meses sin que le detectes.
- **C2 / C&C:** la infraestructura desde donde el atacante controla
  el malware que ha metido en tus sistemas.
- **Correlación de eventos:** lo que hace el SIEM para relacionar
  eventos que por separado parecen normales pero juntos son un ataque.
- **CVE:** el ID único que se le asigna a cada vulnerabilidad conocida.
- **HIDS:** IDS que corre en el propio equipo, mirando logs, procesos
  y cambios en ficheros.
- **IoC:** cualquier rastro observable que indica que algo ha sido
  comprometido: un hash, una IP, un dominio sospechoso...
- **NIDS:** IDS que analiza el tráfico de red en busca de patrones
  maliciosos.
- **Severidad:** el nivel de prioridad que le das a un incidente según
  el impacto que puede tener.
- **TTPs:** cómo actúa un atacante: qué quiere conseguir, cómo lo
  hace técnicamente y con qué herramientas concretas.
- **Vulnerabilidad vs. Exploit:** la vulnerabilidad es el fallo que
  existe en el sistema, el exploit es lo que usa el atacante para
  aprovecharse de ese fallo.


## 3) (Opcional) Evidencias y recursos usados
Enlaza aquí evidencias (capturas, logs, configuraciones, salidas de comandos, etc.) si forman parte de tu trabajo.

### Evidencia 1
- Archivo: `evidencias/01_reglasSIEM`
- Qué demuestra: Implklementar reglas
- Qué he aprendido: Implementar reglas en este caso ICMP y SSH usando Snort usando SIEM

### Evidencia 2
- Archivo: `evidencias/02_taxonomia`
- Qué demuestra: La manera de documentar segun los marcos de criticidad
- Qué he aprendido: En base a casos reales ha como catalogarlo segun corresponda

### Evidencia 3
- Archivo: `evidencias/03_retoJirafaOSINT`
- Qué demuestra: Saber almenos lo basico de hacer OSINT
- Qué he aprendido: Hacer una busqueda exahustiva por internet para saber lugares de fotos, nombres, fechas, hora,etc.

## 4) Conclusión

Lo que he sacado de esto es que no sirve de nada tener buenas herramientas si no hay un proceso detrás y que cada incidente bien gestionado y documentado hace que el equipo esté mejor preparado si hay otro araque.
