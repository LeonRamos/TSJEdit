# Electrónica Analógica

La electrónica analógica constituye una disciplina esencial dentro de la ingeniería electrónica, dedicada al procesamiento de señales continuas que varían en amplitud, frecuencia o fase. A diferencia de las señales digitales, que se limitan a valores discretos (0 y 1), las señales analógicas representan fenómenos físicos de manera proporcional, como el sonido, la temperatura o la luz, lo que permite una interacción más fiel con el entorno. Esta rama de la electrónica se fundamenta en componentes pasivos (resistencias, capacitores, inductores) y activos (transistores, diodos, amplificadores operacionales), los cuales permiten operaciones críticas como la amplificación, el filtrado y la modulación de señales.

![https://www.freepik.es/search?format=search&img=1&last_filter=img&last_value=1&query=electr%C3%B3nica+anal%C3%B3gica](ceros.jpg)
## Aplicaciones en Contextos Cotidianos

- **Sistemas de audio**: Los equipos de sonido, desde micrófonos hasta altavoces, emplean amplificadores analógicos para procesar señales de audio con alta fidelidad, manteniendo la riqueza de las ondas sonoras originales.

- **Control de temperatura**: Termostatos en hornos y sistemas de climatización utilizan sensores analógicos para medir y ajustar la temperatura de manera continua y precisa.

- **Automoción**: Sensores analógicos monitorizan variables como la presión de los neumáticos, el nivel de combustible o la posición del acelerador, enviando señales proporcionales a las unidades de control.

- **Dispositivos médicos**: Electrocardiógrafos (ECG) y glucómetros capturan señales fisiológicas mediante circuitos analógicos, traduciendo fenómenos biológicos en datos interpretables.

- **Telecomunicaciones tradicionales**: La radiodifusión AM/FM y la televisión analógica basan su funcionamiento en la modulación de ondas electromagnéticas, permitiendo la transmisión de información sin conversión digital.

A pesar del predominio de la electrónica digital en el procesamiento de datos, los sistemas analógicos siguen siendo insustituibles en aplicaciones que requieren una respuesta en tiempo real y una interfaz directa con variables físicas. Su estudio resulta fundamental para comprender el diseño de dispositivos electrónicos integrados en la vida diaria y en entornos industriales.

## Referencias

- Boylestad, R. L., & Nashelsky, L. (2013). *Electronic Devices and Circuit Theory* (11.ª ed.). Pearson.
- Sedra, A. S., & Smith, K. C. (2014). *Microelectronic Circuits* (7.ª ed.). Oxford University Press.
- Floyd, T. L. (2018). *Electronic Devices* (10.ª ed.). Pearson.

# Dispositivos Activos
![https://www.freepik.es/search?format=search&img=1&last_filter=img&last_value=1&query=electr%C3%B3nica+anal%C3%B3gica](unos.jpg)
Los dispositivos activos se definen como componentes electrónicos que requieren una fuente de energía externa para modificar, amplificar o conmutar señales eléctricas. A diferencia de los elementos pasivos, estos dispositivos introducen ganancia (incremento de amplitud) o control direccional al flujo de corriente, siendo fundamentales en circuitos analógicos y digitales. Tres atributos los distinguen:

- **Dependencia energética:** Utilizan alimentación externa (ej.: baterías, fuentes DC) para operar.
- **No linealidad:** Su respuesta voltaje-corriente no sigue una relación proporcional (ej.: diodos en polarización inversa).
- **Funcionalidad dinámica:** Pueden actuar como amplificadores, interruptores o reguladores según su configuración.

## Clasificación y Ejemplos Representativos

La Tabla 1 resume los principales dispositivos activos y sus funciones:

| **Dispositivo**      | **Función Primaria**        | **Ejemplo de Aplicación**                           |
|-----------------------|----------------------------|----------------------------------------------------|
| Transistores (BJT)    | Amplificación/conmutación  | Etapas de potencia en amplificadores de audio      |
| Diodos (Zener)        | Regulación de voltaje      | Fuentes de alimentación estabilizadas              |
| Tiristores (SCR)      | Control de potencia en CA  | Sistemas de iluminación dimmable                  |

## Relación con Materiales Semiconductores

Estos dispositivos se fabrican mediante uniones de materiales semiconductores tipo **N** (portadores mayoritarios: electrones, dopado con fósforo) y tipo **P** (portadores mayoritarios: huecos, dopado con boro). La interacción entre estas regiones explica comportamientos como:

- La rectificación en diodos (unión PN).
- El efecto amplificador en transistores (uniones NPN o PNP).

## Relevancia en el Plan de Estudios

Comprender los dispositivos activos sienta las bases para temas avanzados como:

- **Diodos especializados:** LED (emisores de luz), Zener (regulación).
- **Transistores BJT:** Configuraciones en emisor común, base común.
- **Tiristores:** SCR en control de motores, TRIAC en sistemas domésticos.

## Referencias

- Boylestad, R. L. (2013). *Electronic Devices and Circuit Theory* (11.ª ed.). Pearson.
- Floyd, T. L. (2018). *Electronic Devices* (10.ª ed.). Pearson.
- Avila, F. (2012). *Sintaxis y Estructura en Textos Técnicos*. Editorial ECCI.

# **Materiales Semiconductores Tipo N y Tipo P**

Los materiales semiconductores tipo N y tipo P son esenciales en el diseño de dispositivos electrónicos modernos, como diodos, transistores y tiristores. Estos materiales se desarrollan mediante un proceso conocido como **dopaje**, que consiste en introducir impurezas controladas en un semiconductor intrínseco (como el silicio o el germanio) para modificar sus propiedades eléctricas. Este proceso permite crear regiones con diferentes tipos de portadores de carga, fundamentales para el funcionamiento de los dispositivos electrónicos.

---

## **Semiconductores Intrínsecos y Extrínsecos**
Un semiconductor intrínseco es un material puro que tiene baja conductividad eléctrica a temperatura ambiente. Sin embargo, al ser dopado con elementos específicos, se convierte en un semiconductor extrínseco, aumentando su capacidad conductiva. Este tratamiento genera dos tipos principales de semiconductores:

1. **Tipo N**: Portadores mayoritarios son electrones libres (carga negativa).  
2. **Tipo P**: Portadores mayoritarios son huecos (carga positiva efectiva).

---

## **Materiales Semiconductores Tipo N**

Los semiconductores tipo N se obtienen añadiendo átomos pentavalentes (del grupo V de la tabla periódica), como fósforo (P), arsénico (As) o antimonio (Sb). Estos átomos tienen cinco electrones de valencia, de los cuales cuatro forman enlaces covalentes con el silicio, mientras que el quinto queda libre para moverse dentro del material, incrementando su conductividad.

### **Características Principales**
- **Portadores mayoritarios**: Electrones libres.  
- **Portadores minoritarios**: Huecos.  
- **Conductividad mejorada**: Gracias a la alta densidad de electrones libres.  
- **Aplicaciones comunes**: Capas emisoras en transistores bipolares (BJT) y regiones activas en diodos.

---

## **Materiales Semiconductores Tipo P**
Los semiconductores tipo P se producen mediante la incorporación de átomos trivalentes (del grupo III de la tabla periódica), como boro (B), indio (In) o galio (Ga). Estos átomos tienen tres electrones de valencia, lo que genera huecos al no completar los cuatro enlaces covalentes necesarios con el silicio. Los huecos actúan como portadores positivos dentro del material.

### **Características Principales**
- **Portadores mayoritarios**: Huecos.  
- **Portadores minoritarios**: Electrones libres.  
- **Conductividad mejorada**: Debido al movimiento de huecos en el material.  
- **Aplicaciones comunes**: Bases en transistores bipolares y regiones activas en diodos LED.

---

## **Comparación entre Tipo N y Tipo P**
| **Característica**       | **Tipo N**                          | **Tipo P**                          |
|--------------------------|-------------------------------------|-------------------------------------|
| **Tratamiento utilizado**    | Grupo V (P, As, Sb)                | Grupo III (B, In, Ga)               |
| **Portadores mayoritarios** | Electrones (-)                     | Huecos (+)                          |
| **Conductividad eléctrica** | Dominada por electrones libres     | Dominada por movimiento de huecos   |

---

## **Unión PN**
La combinación de un semiconductor tipo N con uno tipo P forma una unión PN, que es la base para dispositivos como diodos y transistores. En esta unión:  
1. Los electrones del tipo N difunden hacia el tipo P, mientras que los huecos del tipo P migran hacia el tipo N.  
2. Se genera una zona de deplexión donde se establece un campo eléctrico interno que permite la rectificación de corriente eléctrica.

---

## **Aplicaciones Prácticas en Electrónica**
1. **Diodos PN:** Rectificadores y reguladores de voltaje (diodos Zener).  
2. **Transistores BJT:** Amplificadores y conmutadores electrónicos en configuraciones NPN o PNP.  
3. **Tiristores:** Controladores de potencia en sistemas industriales y domésticos (SCR y TRIAC).

---

## **Referencias Bibliográficas**
- Boylestad, R., & Nashelsky, L. (2013). *Electronic Devices and Circuit Theory* (11ª ed.). Pearson Education.  
- Floyd, T.L. (2018). *Electronic Devices* (10ª ed.). Pearson Education.  
- Sze, S.M., & Ng, K.K. (2007). *Physics of Semiconductor Devices* (3ª ed.). Wiley-Interscience.  

# Diodos (LED, Rectificadores, Zener)

## Introducción
Los diodos constituyen dispositivos semiconductores fundamentales en la electrónica, cuya función principal es permitir el flujo de corriente en un solo sentido. Estos componentes desempeñan un papel esencial en diversas aplicaciones, incluyendo la rectificación de corriente, la regulación de voltaje y la emisión de luz. En el presente capítulo se examinan tres tipos de diodos fundamentales: LED, rectificadores y Zener.

Los diodos LED, rectificadores y Zener constituyen componentes esenciales en la electrónica moderna. Cada uno de ellos presenta características y aplicaciones específicas que los hacen indispensables en el desarrollo de circuitos electrónicos, desde la conversión y estabilización de energía hasta la emisión de luz. Su estudio resulta fundamental para el diseño y análisis de sistemas electrónicos avanzados.

---

## 1. Principio de Funcionamiento de los Diodos

Un diodo está compuesto por una unión PN, la cual se caracteriza por la presencia de dos regiones diferenciadas:
- **Región P:** Contiene huecos como portadores de carga mayoritarios.
- **Región N:** Contiene electrones como portadores de carga mayoritarios.

![Unión PN](/unionPN.png)

El funcionamiento del diodo depende de su polarización:
- En **polarización directa**, el ánodo se encuentra a un voltaje positivo con respecto al cátodo, permitiendo el paso de corriente.
- En **polarización inversa**, el ánodo se encuentra a un voltaje negativo respecto al cátodo, impidiendo el flujo de corriente hasta alcanzar el voltaje de ruptura.

---

## 2. Diodo LED (Light Emitting Diode)

El diodo LED es un dispositivo que emite luz cuando se encuentra en polarización directa. Su funcionamiento se basa en la recombinación de electrones y huecos dentro del material semiconductor, lo que genera la emisión de fotones mediante el fenómeno de electroluminiscencia.

### Características
- Presenta una eficiencia energética superior en comparación con las bombillas incandescentes.
- Se fabrica en diferentes colores según el material semiconductor empleado:
  - Arseniuro de galio (GaAs): Emisión en rojo e infrarrojo.
  - Fosfuro de galio (GaP): Emisión en verde y amarillo.
  - Nitruro de galio (GaN): Emisión en azul y blanco.
- Posee una larga vida útil y una baja generación de calor.

  ![Diodo Led](/led.png)
  <p>La imagen anterior es la representación gráfica del diodo LED en polarización directa, mostrando cómo la recombinación electrónica produce la emisión de luz en diferentes colores según el material semiconductor</p>

### Aplicaciones
- Sistemas de iluminación para uso residencial, industrial y automotriz.
- Indicadores en dispositivos electrónicos.
- Pantallas y señalización luminosa.

---

## 3. Diodo Rectificador

El diodo rectificador se utiliza principalmente en fuentes de alimentación para convertir corriente alterna (CA) en corriente continua (CC). Existen dos tipos principales:

- **Diodo de silicio convencional:** Caracterizado por su alta eficiencia en procesos de rectificación.Es un tipo de diodo que sirve para convertir una señal alterna a una señal continua, esto es posible hacerlo debido a su capacidad de dejar circular la corriente en un solo sentido. dependiendo del material en el que fue construido tendrá un voltaje de polarización más bajo, lo que se traduce en una respuesta mas rapida en frecuencia.

- **Diodo Schottky:** Presenta una menor caída de voltaje y una alta velocidad de conmutación. El símbolo del diodo Schottky se basa en el símbolo básico del diodo. El símbolo de Schottky se diferencia de otros tipos de diodos por la adición de dos patas extras en la barra del símbolo.

![Diodo Schottky](/schottky.png)

### Tipos de Rectificación
- **Rectificación de media onda:** Utiliza un solo diodo y permite el paso de una sola mitad del ciclo de la corriente alterna.
- **Rectificación de onda completa:** Emplea un puente de diodos para permitir el flujo de corriente en ambos ciclos de la corriente alterna.

### Aplicaciones
- Fuentes de alimentación en dispositivos electrónicos.
- Convertidores de voltaje.
- Protección contra inversión de polaridad en circuitos eléctricos.

---

## 4. Diodo Zener
![Diodo Zener](/zener.png)

El diodo semiconductor es el dispositivo electrónico semiconductor más simple; actualmente se utiliza en varios circuitos: rectificadores, sensores de temperatura, referencias de tensión, emisión de luz, mezcladores, multiplicadores de voltaje, conformadores de ondas, etcétera. Un tipo en particular, y en el cual se enfoca este tema, es el diodo Zener. Aunque todos los diodos Zener tienen un voltaje de ruptura (más allá de esto, el diodo conduce a pesar de encontrarse polarizado con un potencial negativo), su peculiaridad es que dicho voltaje es relativamente pequeño. Aunque en muchas aplicaciones la conducción de corriente en dirección inversa no es deseable, este efecto puede aprovecharse para hacer reguladores de voltaje, los cuales son circuitos electrónicos cuya función es mantener un voltaje constante a su salida. Además, los reguladores de voltaje se utilizan dentro de las fuentes de voltaje de DC durante el proceso de conversión de la tensión de AC a DC.

![curva tipica](/curva.png)

Como se mencionó en un principio, el diodo Zener es un dispositivo no lineal y, por esta razón, analizar y diseñar los circuitos reguladores considerando ecuaciones no lineales se vuelve complicado e impráctico. Por esta razón, es necesario buscar una forma de aproximar el comportamiento de este dispositivo a través de otros elementos como diodos ideales, resistencias y fuentes de voltaje.

### Características
- Mantiene un voltaje constante independientemente de variaciones en la corriente.
- Está disponible en distintos valores de voltaje de ruptura (3.3V, 5.1V, 12V, etc.).
- Se emplea como regulador de voltaje en circuitos electrónicos.

### Aplicaciones
- Regulación de voltaje en fuentes de alimentación.
- Protección contra sobrevoltajes en circuitos electrónicos.
- Implementación en circuitos de referencia de voltaje.

---

## Bibliografía
- Boylestad, R., & Nashelsky, L. (2015). *Electrónica: Teoría de Circuitos y Dispositivos Electrónicos*. Pearson.
- Malvino, A. P. (2016). *Principios de Electrónica*. McGraw-Hill.
- Millman, J., & Halkias, C. (2010). *Electrónica de Dispositivos*. McGraw-Hill.

# Transistores Bipolares de Unión (BJT)

## Introducción

En el campo de la electrónica analógica, los transistores bipolares de unión (BJT, por sus siglas en inglés) son dispositivos semiconductores fundamentales que desempeñan funciones esenciales en circuitos de amplificación y conmutación. Su invención marcó un hito en la historia de la tecnología, permitiendo el desarrollo de dispositivos electrónicos más pequeños, eficientes y confiables. Este capítulo aborda en profundidad la estructura, el funcionamiento, los modos de operación, los parámetros característicos y las aplicaciones de los transistores BJT.

---

## ¿Qué es un transistor?

Un transistor es un dispositivo semiconductor que permite controlar el flujo de corriente eléctrica entre dos de sus terminales mediante una pequeña corriente o tensión aplicada a una tercera terminal. Los BJT están compuestos por tres regiones de material semiconductor que forman dos uniones PN consecutivas, y se clasifican en dos tipos: NPN y PNP.

![Transistor BTJ](/bjt.png)

### Funciones principales
- **Amplificador:** Un transistor puede aumentar la señal de entrada, es decir, amplificar corrientes o tensiones eléctricas.
- **Interruptor:** También puede actuar como un conmutador, permitiendo o bloqueando el paso de corriente según el estado de polarización.

---

## Estructura del BJT

El BJT posee tres terminales:
- **Emisor (E):** Terminal por el cual se inyectan los portadores de carga (electrones o huecos).
- **Base (B):** Capa muy delgada y ligeramente dopada que controla el paso de portadores.
- **Colector (C):** Terminal que recoge los portadores que han cruzado la base.

### Tipos de BJT
- **NPN:** En este tipo, el emisor y el colector son de material tipo N, y la base es de tipo P. Es el más común en aplicaciones prácticas.
- **PNP:** En este caso, el emisor y el colector son de tipo P, y la base es de tipo N.

![BTJ NPN PNP](/btjNPNPNP.png)
La dirección del flujo de corriente y las condiciones de polarización difieren en ambos tipos, pero el principio de funcionamiento es análogo.

---

## Funcionamiento Básico

El principio de operación de un transistor BJT se basa en el control de la corriente entre el colector y el emisor mediante la corriente que circula por la base. Para que el transistor funcione adecuadamente:

- La **unión emisor-base** debe estar **polarizada directamente**.
- La **unión colector-base** debe estar **polarizada inversamente**.

En un transistor NPN, esto significa que:
- El emisor está a un potencial más bajo que la base (polarización directa).
- El colector está a un potencial más alto que la base (polarización inversa).

![Operación Básica Transistor](/operacion.png)
La corriente que fluye desde la base permite que una corriente mucho mayor circule desde el colector hacia el emisor.

---

## Modos de Operación

El comportamiento del transistor depende de las polarizaciones aplicadas a sus uniones, y esto define tres regiones de operación:

### Región de Corte
- Ambas uniones (emisor-base y colector-base) están polarizadas inversamente.
- No hay flujo de corriente significativa entre el colector y el emisor.
- El transistor actúa como un **interruptor abierto**.

### Región Activa
- La unión emisor-base está polarizada directamente y la colector-base inversamente.
- El transistor funciona como **amplificador**.
- La corriente de colector (IC) es proporcional a la corriente de base (IB):  
  **IC = β * IB**, donde β es la ganancia de corriente del transistor.

### Región de Saturación
- Ambas uniones están polarizadas directamente.
- La corriente fluye libremente del colector al emisor.
- El transistor actúa como un **interruptor cerrado**.

---

## Parámetros y Características

### Ganancia de Corriente (β o hFE)
La ganancia de corriente indica cuántas veces la corriente de base se amplifica para obtener la corriente de colector. Por ejemplo, si β = 100 y la corriente de base es de 20 µA, la corriente de colector será de 2 mA.

### Curvas Características
Las curvas características de un transistor muestran la relación entre las corrientes y voltajes aplicados:
- **Curvas IC vs. VCE:** Para diferentes valores de corriente de base, se observa cómo varía la corriente de colector respecto a la tensión colector-emisor.
- Estas curvas permiten identificar en qué región opera el transistor y son esenciales para el diseño de circuitos amplificadores.

### Voltajes y Corrientes Máximas
Cada transistor tiene especificaciones límites dadas por el fabricante:
- **VCE(max):** Máxima tensión que puede soportar entre colector y emisor.
- **IC(max):** Máxima corriente de colector permitida.
- **Ptot:** Potencia total máxima que el transistor puede disipar.

Superar estos límites puede dañar el dispositivo permanentemente.

---

## Aplicaciones de los Transistores BJT

Los transistores BJT tienen una amplia variedad de aplicaciones en circuitos electrónicos:

### **Amplificadores**
- En configuraciones como emisor común, colector común y base común.
- Se utilizan en radios, equipos de audio, instrumentación y telecomunicaciones.

### **Interruptores Electrónicos**
- Usados en lógica digital, controladores de motores, fuentes conmutadas.
- Permiten la automatización de procesos electrónicos con eficiencia y fiabilidad.

### **Osciladores y Generadores de Señal**
- Generan formas de onda periódicas para relojes digitales, sintetizadores de audio y moduladores.

### **Reguladores de Tensión**
- En combinación con diodos Zener, se utilizan para mantener una tensión constante de salida.

---

# **Tiristores: Dispositivos de Control de Potencia**  
### (SCR, DIAC y TRIAC)

## **Introducción**

En la electrónica de potencia, los tiristores ocupan un lugar crucial al permitir el control eficiente de la energía eléctrica en aplicaciones industriales, comerciales y domésticas. Estos dispositivos semiconductores están diseñados para manejar altos voltajes y corrientes, facilitando la conmutación y regulación de potencia en sistemas de corriente alterna (CA) y corriente continua (CC).

El término *tiristor* hace referencia a una familia de componentes semiconductores que actúan como interruptores controlados, es decir, pueden cambiar entre estados de conducción y no conducción bajo ciertas condiciones. Entre los tiristores más importantes y utilizados se encuentran el **SCR (Rectificador Controlado de Silicio)**, el **DIAC** y el **TRIAC**, cada uno con características y aplicaciones particulares.

Este material tiene como objetivo que el estudiante comprenda la estructura, el funcionamiento, las características eléctricas y las aplicaciones típicas de estos tres tipos de tiristores.

---

## **El Rectificador Controlado de Silicio (SCR)**

### **Estructura y Principio de Funcionamiento**

El SCR (Silicon Controlled Rectifier) es un dispositivo semiconductor de cuatro capas (PNPN) con tres terminales: ánodo (A), cátodo (K) y compuerta (G). Su funcionamiento se basa en el control del paso de corriente desde el ánodo hacia el cátodo a través de una señal aplicada a la compuerta.

Cuando el ánodo se encuentra a un voltaje positivo respecto al cátodo y se aplica una corriente de disparo en la compuerta, el SCR entra en conducción, permitiendo el paso de corriente. Esta conducción se mantiene incluso si se retira la señal de la compuerta, siempre que la corriente entre ánodo y cátodo sea mayor a una corriente mínima denominada *corriente de mantenimiento*. Para que el dispositivo deje de conducir, es necesario reducir esta corriente por debajo de dicho valor, lo que se puede lograr mediante el cruce por cero en una señal de CA o conmutación forzada en CC.

### **Características y Parámetros Eléctricos**

- **Voltaje de encendido (V<sub>BO</sub>):** es el voltaje mínimo necesario entre ánodo y cátodo para activar el dispositivo sin señal de compuerta.
- **Corriente de disparo (I<sub>GT</sub>):** mínima corriente que debe aplicarse a la compuerta para encender el SCR.
- **Corriente de mantenimiento (I<sub>H</sub>):** corriente mínima entre ánodo y cátodo para mantener el SCR en conducción.
- **Tiempo de encendido y apagado:** valores importantes en aplicaciones de conmutación rápida.

### **Aplicaciones Comunes**

El SCR se emplea en sistemas de control de potencia como reguladores de velocidad de motores, sistemas de calefacción eléctrica, rectificadores controlados, fuentes conmutadas y protecciones contra sobrecargas.

---

## **DIAC (Diodo para Corriente Alterna)**

### **Estructura y Funcionamiento**

El DIAC es un dispositivo semiconductor bidireccional compuesto por tres capas alternadas, que actúa como un interruptor que conduce en ambas direcciones cuando se alcanza una tensión de ruptura determinada. Posee dos terminales, y su comportamiento es simétrico con respecto a la polarización.

El DIAC no dispone de terminal de control como el SCR, por lo que no puede activarse mediante una señal externa. Su activación se produce automáticamente al superar el voltaje de ruptura en cualquiera de los dos sentidos.

### **Características**

- **Voltaje de ruptura (V<sub>BO</sub>):** alrededor de 30 a 40 V en la mayoría de los modelos comerciales.
- **Simetría:** el DIAC conduce en ambas direcciones de forma prácticamente idéntica.
- **Sin compuerta:** no puede ser activado por una señal externa, lo que lo hace ideal para disparar TRIACs.

### **Aplicaciones Típicas**

El DIAC es ampliamente utilizado como disparador para TRIACs en circuitos de regulación de luz (dimmers), control de ventiladores, pequeños motores de CA y control de calentadores eléctricos. Su comportamiento bidireccional y su activación automática lo convierten en un elemento ideal para circuitos osciladores y de arranque suave.

---

## **TRIAC (Triodo para Corriente Alterna)**

### Estructura y Principio de Funcionamiento**

El TRIAC (Triode for Alternating Current) es un componente de cinco capas capaz de conducir corriente en ambas direcciones, a diferencia del SCR que solo lo hace en un sentido. Este dispositivo también tiene tres terminales: MT1, MT2 (terminales principales) y G (compuerta). Puede ser disparado tanto por corriente positiva como negativa en la compuerta, lo que permite una gran flexibilidad en el diseño de circuitos de control.

El TRIAC puede considerarse como dos SCRs conectados en antiparalelo, con compuerta común. Esta arquitectura le permite funcionar en ambos semicíclos de una señal de CA.

### **Características Principales**

- **Bidireccionalidad:** puede controlar el paso de corriente en ambos sentidos.
- **Control por compuerta:** puede dispararse con señales positivas o negativas.
- **Sensibilidad:** requiere una corriente de disparo ligeramente superior a la del SCR.

### **Aplicaciones Prácticas**

El TRIAC se utiliza en una gran variedad de aplicaciones de control de potencia en CA, como reguladores de intensidad para lámparas incandescentes, controles de temperatura, controladores de velocidad para motores de inducción monofásicos, lavadoras, hornos eléctricos y soldadoras. Su capacidad para ser controlado electrónicamente lo hace indispensable en aplicaciones de automatización y domótica.

---

## **Comparación entre SCR, DIAC y TRIAC**

| Característica | SCR | DIAC | TRIAC |
|----------------|-----|------|-------|
| Direccionalidad | Unidireccional | Bidireccional | Bidireccional |
| Terminal de control | Sí | No | Sí |
| Uso común | Rectificadores, inversores | Disparo de TRIACs | Controladores de potencia en CA |
| Complejidad de control | Media | Baja | Alta (por disparo en ambos ciclos) |

![omparación visual entre SCR, DIAC y TRIAC](/triacscrdiac.png)

## **Referencias Bibliográficas (formato APA)**

Floyd, T. L. (2019). *Dispositivos semiconductores y teoría de circuitos electrónicos* (11.ª ed.). Pearson Educación.

Boylestad, R. L., & Nashelsky, L. (2017). *Electrónica: teoría de circuitos y dispositivos electrónicos* (11.ª ed.). Pearson.

Mohan, N., Undeland, T. M., & Robbins, W. P. (2003). *Power Electronics: Converters, Applications, and Design* (3rd ed.). John Wiley & Sons.

Sedra, A. S., & Smith, K. C. (2020). *Microelectrónica* (8.ª ed.). Oxford University Press.



