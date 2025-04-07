## Construcción de una Fuente de Poder Variable en Tinkercad  
**Objetivo:** Integrar conceptos de dispositivos activos en electrónica analógica mediante el diseño de una fuente de alimentación ajustable (1.25V a 12V) utilizando el regulador LM317.  

---

### Introducción a los Dispositivos Activos en Electrónica Analógica  
Los **dispositivos activos** son componentes electrónicos capaces de controlar el flujo de corriente en un circuito mediante una fuente externa de energía. A diferencia de los elementos pasivos (resistencias, capacitores), estos dispositivos introducen **ganancia** o **regulación**, permitiendo funciones como amplificación, conmutación o estabilización de señales.  

En electrónica analógica, componentes como **transistores**, **amplificadores operacionales** y **reguladores de voltaje** (ej. LM317) son fundamentales. El LM317, por ejemplo, es un regulador ajustable que mantiene un voltaje de salida estable independientemente de las fluctuaciones de entrada o carga, gracias a su estructura interna basada en transistores y circuitos de retroalimentación.  

Esta práctica permitirá comprender cómo los dispositivos activos interactúan en sistemas reales, enfocándose en:  
- La relación entre **corriente**, **voltaje** y **resistencia** en circuitos regulados.  
- El papel de la **retroalimentación negativa** en la estabilidad del voltaje.  
- La adaptabilidad de circuitos analógicos para aplicaciones personalizadas.  

---

### Materiales Necesarios (Simulación en Tinkercad)  
1. **Regulador LM317** (dispositivo activo principal).  
2. Transformador de 12V AC (simulado con una fuente de CA).  
3. Puente rectificador de diodos (1N4007 x4)[.  
4. Capacitores electrolíticos: 220µF y 10µF (filtrado de ripple).  
5. Potenciómetro de 5kΩ (ajuste de voltaje).  
6. Resistencia de 240Ω (fijar corriente mínima del LM317).  
7. Cables, multímetro virtual y protoboard.  

---

### Pasos para Construir el Circuito  
#### 1. Rectificación y Filtrado de la Señal AC  
- Conecta la **fuente de CA (12V)** al puente rectificador para convertir la señal alterna en continua pulsante.  
- Agrega el capacitor de 220µF en paralelo con la salida del puente para suavizar el ripple (**filtrado pasivo**).  
```plaintext  
Fuente AC → Puente Rectificador → Capacitor 220µF → Tierra  
```

#### 2. Configuración del LM317  
- Conecta el terminal de entrada (**IN**) del LM317 al voltaje rectificado (+12V).  
- En el terminal de ajuste (**ADJ**), coloca el potenciómetro de 5kΩ en serie con la resistencia de 240Ω:  
```plaintext  
ADJ → Resistencia 240Ω → Potenciómetro → Tierra  
```
- Agrega un capacitor de 10µF entre la salida (**OUT**) y tierra para mejorar la estabilidad.  

#### 3. Fórmula de Voltaje de Salida  
El LM317 sigue la ecuación:  
$$ V_{out} = 1.25 \, \text{V} \times \left(1 + \frac{R_2}{R_1}\right) $$  
Donde $$ R_1 = 240 \, \Omega $$ y $$ R_2 $$ es el valor del potenciómetro (0-5kΩ).  
- **Rango teórico:** 1.25V (cuando $$ R_2 = 0 $$) hasta ~26V, pero limitado por el voltaje de entrada.  

#### 4. Simulación y Pruebas  
- Usa el **multímetro virtual** para medir el voltaje de salida mientras ajustas el potenciómetro.  
- Observa cómo cambios en $$ R_2 $$ afectan $$ V_{out} $$, validando la función del regulador como dispositivo activo.  

---

### Análisis de Componentes Activos  
- **LM317:** Regula el voltaje mediante un circuito interno de transistores y retroalimentación, ajustando la resistencia equivalente para mantener $$ V_{out} $$ estable.  
- **Puente Rectificador:** Aunque usa diodos (pasivos), su interacción con el LM317 demuestra cómo los activos dependen de etapas previas para funcionar.  


