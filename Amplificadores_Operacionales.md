Los amplificadores operacionales (op-amps) son componentes esenciales en la electrónica analógica, diseñados para amplificar la diferencia de voltaje entre dos entradas con alta precisión y versatilidad. Su evolución, desde los primeros modelos con tubos de vacío hasta los circuitos integrados modernos, ha revolucionado aplicaciones que van desde sistemas de audio hasta instrumentación médica.

## **Origen y evolución histórica**  
El concepto de amplificador operacional surgió en 1947 como parte de computadoras analógicas que realizaban operaciones matemáticas, utilizando tubos de vacío. En 1964, Robert Widlar desarrolló el primer op-amp monolítico (μA702) en Fairchild Semiconductor, seguido por el icónico μA741 en 1968, que estableció estándares industriales. La integración de transistores de efecto de campo (JFET) en los años 70, como el LF356, mejoró la impedancia de entrada, mientras que los avances en materiales y diseño permitieron op-amps especializados, como los de alto voltaje y bajo consumo energético (ej. LMR1901YG-M de ROHM, con 160 nA).

## **Estructura interna y funcionamiento**  
Un op-amp típico consta de tres etapas:  
1. **Etapa diferencial de entrada**: Amplifica la diferencia entre las entradas inversora (-) y no inversora (+), con alta impedancia para minimizar la carga en la fuente.  
2. **Etapa de ganancia de voltaje**: Proporciona la amplificación principal, con ganancias en lazo abierto superiores a 100,000.  
3. **Etapa de salida**: Reduce la impedancia de salida para manejar cargas externas eficientemente, a menudo incluyendo protección contra cortocircuitos.  

En condiciones ideales, los op-amps tienen ganancia infinita, impedancia de entrada infinita y cero ruido. Sin embargo, en la práctica, factores como la deriva térmica, el ancho de banda limitado (ej. 1 MHz en el μA741) y las corrientes de polarización (≈10 nA en modelos bipolares) afectan su rendimiento.

## **Configuraciones básicas**  
La flexibilidad de los op-amps se debe a circuitos de retroalimentación que definen su comportamiento:  
- **Amplificador inversor**: Ganancia $$ A_v = -\frac{R_2}{R_1} $$, ideal para ajustar amplitud y polaridad.  
- **Amplificador no inversor**: Ganancia $$ A_v = 1 + \frac{R_2}{R_1} $$, útil para adaptar impedancias sin invertir la señal.  
- **Seguidor de voltaje**: Ganancia unitaria, protege señales sensibles al aislar etapas.  
- **Integrador/Diferenciador**: Realizan operaciones matemáticas usando capacitores, fundamentales en procesamiento de señales.  
- **Comparador**: Detecta umbrales de voltaje sin retroalimentación, clave en sistemas de control.

## **Aplicaciones y relevancia tecnológica**  
Los op-amps son omnipresentes en:  
- **Sistemas de audio**: Amplifican y filtran señales en equipos de sonido.  
- **Instrumentación médica**: Acondicionan señales de biosensores (ej. ECG) con amplificadores de instrumentación.  
- **Control industrial**: Regulan motores y sensores de temperatura/presión mediante PWM y comparadores.  
- **Conversión de datos**: Interfazan sensores con ADCs en sistemas embebidos.  

Innovaciones recientes incluyen op-amps de alto voltaje (hasta ±30 V) para entornos industriales, y modelos de precisión con tecnologías como *zero-drift* (deriva <1 μV) y *e-Trim* para calibración estable[8]. Estos avances permiten aplicaciones en vehículos eléctricos y equipos portátiles con baterías de larga duración.

## **Desafíos y consideraciones de diseño**  
Al implementar op-amps, se deben considerar:  
- **Estabilidad**: La retroalimentación mal diseñada causa oscilaciones, mitigables con compensación de fase.  
- **Rechazo de modo común (CMRR)**: Critico en entornos ruidosos, con valores típicos de 90 dB.  
- **Factor de rechazo a la alimentación (PSRR)**: Asegura inmunidad a fluctuaciones de voltaje, especialmente en sistemas no regulados.  

Resumen, los amplificadores operacionales son la columna vertebral de la electrónica analógica moderna. Su evolución continúa impulsando tecnologías emergentes, combinando precisión, eficiencia y adaptabilidad para resolver desafíos en automatización, telemedicina y energía sostenible.

# Tutorial Práctico: Amplificadores Operacionales en Tinkercad

## Objetivo General

Comprender el funcionamiento y aplicaciones básicas de los **amplificadores operacionales (Op-Amps)** mediante simulaciones prácticas en el entorno de **Tinkercad**.

---

## Instrucciones Generales

1. Accede a [https://www.tinkercad.com](https://www.tinkercad.com).
2. Inicia sesión o crea una cuenta gratuita.
3. Haz clic en **"Circuits"** y luego en **"Create new Circuit"**.
4. Realiza **todas las prácticas** que se indican a continuación.
5. Para cada práctica:
   - Guarda tu simulación en Tinkercad.
   - Realiza capturas de pantalla de tus circuitos y resultados.
   - Contesta las preguntas de análisis al final de cada actividad.

---

##  Actividad 1: Seguidor de Voltaje (Buffer)

###  Materiales Requeridos

- 1 Op-Amp **LM741**
- 1 Potenciómetro (fuente de voltaje variable)
- 1 Fuente de voltaje de **+9V**
- 1 Fuente de voltaje de **-9V** o **GND**
- Multímetro (opcional para medición visual)

###  Pasos para Construir el Circuito

1. Coloca el componente **LM741** en el área de trabajo.
2. Conecta:
   - Pin **7** del LM741 a **+9V**.
   - Pin **4** del LM741 a **-9V** o **GND**.
3. Conecta la **entrada no inversora** (pin 3) a la salida del **potenciómetro**.
4. Conecta la **salida** (pin 6) directamente a la **entrada inversora** (pin 2).
5. Coloca un **multímetro** o usa el punto de medición en la salida para verificar el voltaje.

###  Resultado Esperado

La salida (pin 6) debe ser **igual al voltaje de entrada** (pin 3). El Op-Amp está funcionando como un **seguidor de voltaje**, proporcionando aislamiento sin amplificar.

---

###  Preguntas de Análisis

1. ¿Qué relación observas entre el voltaje de entrada y el voltaje de salida?
2. ¿Qué utilidad tiene este tipo de configuración en un circuito real?
3. ¿Qué sucede si modificas el valor del potenciómetro?

---

##  Recomendaciones Finales

- Asegúrate de revisar los pines del LM741 correctamente.
- Si el circuito no responde como esperas, verifica la conexión de alimentación y tierra.
- Puedes exportar o compartir el enlace del circuito desde Tinkercad para entregas o colaboración.
## 📤 Entrega del Reporte

### 📝 ¿Qué debe incluir tu reporte?

Tu reporte de la práctica debe contener lo siguiente:

1. **Portada** con tu nombre completo, matrícula, grupo y nombre de la práctica.
2. **Capturas de pantalla** de los circuitos simulados en Tinkercad (vista general y conexiones).
3. **Resultados obtenidos**: mediciones de voltajes, comportamiento observado.
4. **Respuestas a las preguntas de análisis** que se indican al final de cada actividad.
5. **Conclusiones personales** sobre lo que aprendiste con la práctica.

### 📂 Formato de entrega

- El reporte debe entregarse en **formato PDF**.
- Nombra tu archivo así:  
  `Practica_OpAmps_NombreApellido.pdf`

  ---

## 📊 Rúbrica de Evaluación: Práctica de Amplificadores Operacionales (Tinkercad)

| Criterio                            | Excelente (10)                                      | Bueno (8)                                              | Regular (6)                                            | Insuficiente (0-5)                                  |
|-------------------------------------|-----------------------------------------------------|--------------------------------------------------------|--------------------------------------------------------|-----------------------------------------------------|
| **Construcción del circuito**       | Circuito completo, funcional, bien conectado y limpio. | Circuito funcional con pocos errores menores.          | Circuito con errores que afectan parcialmente su funcionamiento. | Circuito incompleto o no funcional.                 |
| **Capturas de pantalla**           | Incluye todas las capturas necesarias con buena calidad y claridad. | Faltan pocas capturas o no tienen buena calidad.       | Capturas incompletas o poco claras.                   | No se incluyen capturas o son irrelevantes.         |
| **Mediciones y resultados**        | Todas las mediciones están presentes, bien presentadas y son coherentes. | Algunas mediciones presentes y explicadas.             | Mediciones confusas o poco precisas.                  | No se presentan resultados o son incorrectos.        |
| **Respuestas de análisis**         | Respuestas completas, bien razonadas y con lenguaje técnico adecuado. | Respuestas correctas pero poco desarrolladas.          | Respuestas incompletas o con errores conceptuales.    | No se responden las preguntas o son incorrectas.     |
| **Conclusiones**                   | Conclusiones claras, reflexivas y bien argumentadas. | Conclusiones adecuadas pero generales.                 | Conclusiones muy breves o poco reflexivas.            | No hay conclusiones o son irrelevantes.              |
| **Presentación y ortografía**      | Documento bien organizado, sin faltas ortográficas. | Documento legible con pocos errores ortográficos.      | Documento poco organizado o con varios errores.       | Desordenado y con muchos errores.                    |
| **Entrega en tiempo y forma**      | Entregado a tiempo, en formato PDF correcto.         | Entregado a tiempo con errores menores en el formato. | Entregado con retraso o en formato incorrecto.        | No se entregó la práctica.                           |

---

🔢 **Puntaje total máximo:** 70 puntos  
📈 **Escala de calificación:**  
- 63 - 70: Excelente  
- 56 - 62: Bueno  
- 42 - 55: Regular  
- < 42: Insuficiente

### Bibliografía
Coughlin, R. F., & Driscoll, F. F. (2000). Amplificadores operacionales y circuitos integrados lineales. Academia.edu. Recuperado de https://www.academia.edu/download/56020368/Amplificadores_Operacionales_Coughlin.pdf

Universidad Nacional de La Plata. (2018). Amplificadores operacionales. SEDICI. Recuperado de https://sedici.unlp.edu.ar/handle/10915/69653

Academia.edu. (2021). Amplificadores operacionales (II). Recuperado de https://www.academia.edu/download/68934295/Circuitos_Lab14_recuperado.pdf

Rodríguez, J., & Gómez, M. (2015). Circuitos electrónicos con amplificadores operacionales: problemas, fundamentos teóricos, técnicas de identificación y análisis. Google Books. Recuperado de https://books.google.com/books?hl=en&lr=&id=iWOwTgeLn-QC&oi=fnd&pg=PA11&dq=amplificadores+operacionales&ots=eysORUSbmf&sig=CL0l_AzJ3gqd7eJ6i4i8irHdBrY

Universidad del Azuay. (2019). Dispositivos electrónicos. Biblioteca UAZUAY. Recuperado de https://biblioteca.uazuay.edu.ec/buscar/item/61563

Universidad Nacional de Educación (UNE). (2020). El amplificador operacional. Repositorio UNE. Recuperado de https://repositorio.une.edu.pe/items/be7fa466-9ab6-4368-9bad-da0d8c86e00f

Mayosky, M., & Mayosky, M. A. (2004). Un amplificador operacional equilibrado. ResearchGate. Recuperado de https://www.researchgate.net/profile/Miguel-Mayosky/publication/3455138_A_Fully-Balanced_Operational_Amplifier/links/53d0f2f00cf25dc05cfe750f/A-Fully-Balanced-Operational-Amplifier.pdf

Universidad de Cádiz (UCA). (2012). Amplificación: Amplificadores operacionales. Rodin UCA. Recuperado de https://rodin.uca.es/bitstream/handle/10498/14752/tema6%20ampl%20prot.pdf

Pérez, R., & González, L. (2016). Potencialidades de la aplicación OPEDU para el estudio de los amplificadores operacionales. SciELO Cuba. Recuperado de http://scielo.sld.cu/scielo.php?pid=S1815-5.901202e+16&script=sci_arttext&tlng=en

Mora, J., & Rodríguez, A. (2023). Diseño de un amplificador operacional de transconductancia aplicando técnicas de optimización multiobjetivo. SciELO Costa Rica. Recuperado de https://www.scielo.sa.cr/pdf/tem/v27n1/a01v27n1.pdf

