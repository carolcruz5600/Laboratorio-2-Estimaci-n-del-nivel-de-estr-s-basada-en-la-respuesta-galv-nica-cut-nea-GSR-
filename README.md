# Laboratorio 2: Estimación del nivel de estrés basada en la respuesta galvánica cutánea (GSR)

# Objetivos

## Objetivo general

Proporcionar un sistema de medición continua de estrés basado en la respuesta galvánica cutánea (GSR).

## Objetivos específicos
- Identificar las componentes estacionaria y transitoria de la respuesta galvánica cutánea (GSR).
- Elaborar un dispositivo vestible que permita capturar de forma continua las variaciones de la GSR.
- Plantear hipótesis desde la fisiología humana sobre el rol de la GSR como indicador de estrés.

# PARTE A:  Actividad Electrodérmica (EDA) y Respuesta Galvánica Cutánea (GSR)

## Actividad electrodérmica

La actividad electrodérmica (EDA, Electrodermal Activity) comprende los fenómenos eléctricos que ocurren en la piel y que producen variaciones en su capacidad para conducir corriente eléctrica. Esta propiedad se conoce como conductancia cutánea y puede cambiar como consecuencia de diferentes procesos fisiológicos y estímulos externos. Entre los factores que pueden modificar la actividad electrodérmica se encuentran los cambios en la respiración, estímulos térmicos y mecánicos, dolor, actividad física, emociones y situaciones que generan activación del sistema nervioso autónomo. Una de las principales razones por las que la piel presenta cambios en sus propiedades eléctricas es la actividad de las glándulas sudoríparas. Estas glándulas producen secreciones que contienen agua y electrolitos, aumentando la humedad de la superficie de la piel y facilitando el movimiento de cargas eléctricas. Por esta razón, una mayor actividad sudorípara puede generar una disminución de la resistencia eléctrica y, en consecuencia, un aumento de la conductancia.

La EDA constituye una señal fisiológica de interés en el área de la ingeniería biomédica porque permite convertir una respuesta fisiológica en una señal eléctrica que puede ser registrada y analizada. Mediante electrodos colocados sobre la piel es posible detectar las variaciones de conductancia y estudiar su comportamiento a lo largo del tiempo. Es importante tener en cuenta que la actividad electrodérmica no representa exclusivamente una respuesta de estrés. Una variación de la señal puede producirse por diferentes estímulos, por lo que su interpretación debe realizarse considerando las condiciones experimentales y el contexto fisiológico de la persona.

### Relación con el sistema nervioso autónomo

La actividad electrodérmica está relacionada principalmente con la actividad del sistema nervioso autónomo, especialmente con la activación del sistema nervioso simpático. Este sistema participa en la regulación de diferentes funciones involuntarias del organismo y tiene influencia sobre la actividad de las glándulas sudoríparas. Cuando una persona experimenta una situación que genera activación fisiológica, puede aumentar la actividad de las glándulas sudoríparas. Aunque la cantidad de sudor producida puede ser muy pequeña y no necesariamente visible, puede ser suficiente para modificar las propiedades eléctricas de la superficie de la piel. Al aumentar la actividad de las glándulas sudoríparas, aumenta la humedad y la concentración de electrolitos presentes sobre la piel. Como consecuencia, se facilita el paso de la corriente eléctrica y aumenta la conductancia cutánea. Por lo tanto, existe una relación inversa entre la resistencia y la conductancia:

$$
G = \frac{1}{R}
$$

donde:

$G$ = conductancia eléctrica, medida en siemens (S).
$R$ = resistencia eléctrica, medida en ohmios ($\Omega$).

Así, cuando disminuye la resistencia de la piel, aumenta su conductancia:

$$
R\downarrow \Rightarrow G\uparrow
$$

Por el contrario, cuando aumenta la resistencia, la conductancia disminuye:

$$
R\uparrow \Rightarrow G\downarrow
$$

Esta relación constituye el principio eléctrico fundamental que permite utilizar los cambios de la piel como una señal fisiológica medible.

### Conductancia cutánea

La conductancia cutánea es una medida de qué tan fácilmente puede circular una corriente eléctrica a través de la piel. Su valor está determinado por las propiedades eléctricas de los tejidos y, particularmente, por las condiciones de humedad y actividad de las glándulas sudoríparas presentes en la zona donde se realiza la medición. La conductancia puede variar continuamente incluso cuando una persona permanece en reposo. Esto se debe a que la actividad fisiológica del organismo no permanece completamente constante y puede verse afectada por factores internos y externos, como la temperatura, la hidratación, la actividad autonómica, el estado emocional y las condiciones ambientales.

La GSR puede utilizarse para estudiar respuestas relacionadas con:

- Estrés.
- Activación emocional.
- Atención.
- Esfuerzo cognitivo.
- Estímulos físicos.
- Cambios respiratorios.

Sin embargo, la GSR no representa exclusivamente el estrés, ya que diferentes estímulos pueden producir cambios en la conductancia. Por esta razón, un incremento de la señal no debe interpretarse automáticamente como una situación de estrés, sino como una posible manifestación de activación fisiológica.

### Componentes de la GSR

La señal GSR puede analizarse mediante dos componentes principales: la componente tónica, asociada al nivel basal de conductancia, y la componente fásica, relacionada con los cambios rápidos y transitorios que aparecen sobre ese nivel basal. La identificación de ambas componentes permite analizar la señal de una manera más completa, ya que no todas las variaciones de conductancia tienen la misma velocidad ni necesariamente representan el mismo tipo de respuesta fisiológica.

Componente tónica — SCL

El SCL (Skin Conductance Level) corresponde al nivel basal o estacionario de la conductancia de la piel. Esta componente presenta variaciones relativamente lentas y permite establecer un nivel de referencia sobre el cual pueden analizarse posteriormente las respuestas rápidas.

El SCL puede cambiar debido a diferentes factores fisiológicos y ambientales. Por esta razón, antes de analizar una respuesta ante un estímulo resulta conveniente disponer de un periodo inicial de registro en condiciones de reposo que permita establecer el comportamiento basal de la persona.

Componente fásica — SCR

La SCR (Skin Conductance Response) corresponde a los cambios rápidos y transitorios de la conductancia cutánea. Una respuesta típica puede presentarse como un incremento rápido de la conductancia seguido de una recuperación progresiva hacia el valor inicial.La respuesta fásica puede analizarse considerando características como la amplitud del cambio, el tiempo necesario para alcanzar el máximo y el tiempo requerido para recuperar el nivel basal.

### Importancia de la GSR

La respuesta galvánica cutánea es uno de los indicadores fisiológicos utilizados en ingeniería biomédica para estudiar cambios relacionados con la actividad del sistema nervioso autónomo. Su principal ventaja es que permite obtener una señal de manera relativamente sencilla mediante electrodos en contacto con la piel y analizar sus variaciones a lo largo del tiempo. En esta práctica, la GSR se utiliza para desarrollar un sistema capaz de realizar un monitoreo continuo de cambios asociados con el nivel de estrés durante la realización de tareas cognitivas. El objetivo no consiste únicamente en obtener una señal eléctrica, sino en comprender cómo esta señal puede relacionarse con determinadas respuestas fisiológicas. Por lo tanto, la GSR representa una aplicación en la que se integran conocimientos de fisiología humana, electrónica, instrumentación biomédica y procesamiento de señales.

### Ubicación de los electrodos

Para realizar una medición de GSR se utilizan electrodos en contacto directo con la piel. La selección de la zona donde se colocan es importante porque las diferentes regiones del cuerpo presentan distintas cantidades de glándulas sudoríparas y diferentes características eléctricas. Las regiones de la mano, particularmente los dedos y la palma, son utilizadas frecuentemente debido a la presencia de una alta densidad de glándulas sudoríparas. Estas zonas permiten obtener variaciones de conductancia que pueden ser detectadas mediante el sistema de medición. La ubicación de los electrodos debe seleccionarse cuidadosamente para reducir interferencias producidas por movimiento, contacto deficiente o cambios en la presión. Si el electrodo se desplaza o cambia la superficie efectiva de contacto con la piel, pueden producirse variaciones en la señal que no necesariamente corresponden a una respuesta fisiológica.

### Interpretación de la señal GSR

La interpretación de una señal GSR debe realizarse teniendo en cuenta que la conductancia cutánea representa una respuesta fisiológica indirecta. Un incremento de la señal puede indicar una mayor activación del sistema nervioso autónomo, pero no permite determinar por sí solo cuál fue la causa de dicha activación. Por ejemplo, una persona puede presentar un aumento de la conductancia debido a estrés, pero también puede producirse una respuesta similar ante una emoción, una situación de sorpresa, dolor, esfuerzo cognitivo o determinados estímulos físicos. Por esta razón, es necesario considerar el contexto en el que se realiza la medición. Una estrategia adecuada consiste en registrar inicialmente un periodo de reposo para establecer el nivel basal o SCL y posteriormente comparar los cambios producidos durante la actividad experimental. De esta manera, las variaciones de la señal pueden analizarse respecto al comportamiento individual de cada persona.

En términos generales, un aumento transitorio de la conductancia respecto al nivel basal puede interpretarse como una respuesta de activación fisiológica, mientras que la recuperación posterior permite observar cómo la señal retorna progresivamente hacia sus condiciones iniciales.

## Efectos de la corriente directa y alterna en seres humanos

La IEC 60479-1 estudia los efectos de la corriente eléctrica sobre el cuerpo humano y considera diferentes factores que influyen en la respuesta fisiológica. Esta información es especialmente importante en el diseño de sistemas biomédicos que tienen contacto eléctrico con una persona, debido a que una corriente que puede parecer pequeña desde el punto de vista electrónico puede generar respuestas fisiológicas.

Entre los principales factores que determinan los efectos de la corriente se encuentran:

- Magnitud de la corriente.
- Duración del contacto.
- Recorrido de la corriente por el cuerpo.
- Frecuencia de la corriente.
- Condiciones de contacto.
- Impedancia del cuerpo.
- Características individuales de la persona.

Por esta razón, el efecto de una corriente eléctrica no depende únicamente del voltaje aplicado. La corriente que realmente circula depende de la tensión y de la impedancia presente en el circuito.

La relación básica está determinada por la Ley de Ohm:

$$
I=\frac{V}{R}
$$

Por lo tanto, para una misma tensión, una resistencia mayor produce una corriente menor, mientras que una resistencia menor produce una corriente mayor. En un sistema biomédico, esta característica debe tenerse en cuenta desde el diseño para evitar que una condición inesperada pueda producir una corriente superior a la establecida.

### Umbral de percepción

El umbral de percepción corresponde al nivel mínimo de corriente que puede ser detectado por una persona. Cuando la corriente es suficientemente pequeña puede no producir una sensación perceptible; sin embargo, al aumentar su magnitud puede comenzar a aparecer una sensación eléctrica.

Este valor no es idéntico para todas las personas, ya que puede variar dependiendo de las condiciones de contacto, la zona del cuerpo, la humedad de la piel y otras características individuales. Por esta razón, los valores utilizados como referencia deben entenderse dentro de las condiciones para las cuales fueron establecidos y no como valores absolutos aplicables a cualquier situación.

### Umbral de reacción

El umbral de reacción corresponde a un nivel de corriente capaz de producir una respuesta fisiológica perceptible, como una contracción muscular involuntaria.

Para determinadas condiciones de corriente alterna, se utiliza como referencia un valor aproximado de:

$$
I\approx0.5mA
$$

Esto demuestra que las corrientes necesarias para generar una respuesta fisiológica pueden ser relativamente pequeñas. Por lo tanto, el diseño de un dispositivo que tenga contacto eléctrico con una persona debe considerar cuidadosamente la magnitud de la corriente que puede circular.

### Inmovilización

Al aumentar la corriente pueden producirse contracciones musculares involuntarias de mayor intensidad. La inmovilización ocurre cuando la estimulación eléctrica dificulta el control voluntario de los músculos mientras la corriente continúa circulando. Este fenómeno representa un riesgo importante porque una persona podría tener dificultades para reaccionar ante la fuente eléctrica o retirarse voluntariamente de ella. La gravedad de este efecto depende de factores como la magnitud de la corriente, el tiempo de exposición, el recorrido de la corriente y las características individuales.

### Umbral de liberación

El umbral de liberación o let-go representa aproximadamente el nivel de corriente a partir del cual una persona puede presentar dificultades para liberar voluntariamente un conductor que está tocando. Para determinadas condiciones de corriente alterna, la IEC considera valores de referencia aproximadamente del orden de:

- 10 mA para hombres adultos.
- 5 mA como referencia para una población adulta más amplia.

Estos valores dependen de las condiciones de exposición y de las características individuales. El concepto es importante porque una persona que no puede liberar voluntariamente una fuente eléctrica puede permanecer expuesta durante un tiempo mayor.

### Fibrilación ventricular

La fibrilación ventricular es uno de los efectos fisiológicos más graves que puede producir una corriente eléctrica. Se caracteriza por una alteración de la actividad eléctrica normal del corazón que puede comprometer su capacidad para realizar una contracción efectiva. El riesgo de que se produzcan efectos graves depende de diferentes factores:

- Magnitud de la corriente.
- Duración del contacto.
- Recorrido de la corriente.
- Frecuencia.
- Características fisiológicas de la persona.

Por esta razón, no existe un único valor de corriente que pueda considerarse completamente independiente de las condiciones de exposición. El recorrido de la corriente es especialmente importante, debido a que una corriente que atraviesa determinadas regiones del cuerpo puede presentar un riesgo diferente a una corriente localizada.

## Cálculo para limitar la corriente a 1 mA
## Condición establecida

La guía establece que el dispositivo debe utilizar una alimentación entre:

$$
3.3V\leq V_{DC}\leq5V
$$

y garantizar que la corriente que circule a través de la piel sea:

$$
I\leq1mA
$$

Además, se debe considerar el peor caso:

$$
R_{skin}=0\Omega
$$

Esta condición representa un escenario de diseño conservador, ya que implica que no se debe depender de la resistencia natural de la piel para limitar la corriente. En otras palabras, aunque la piel normalmente presenta una resistencia eléctrica, el diseño debe ser capaz de cumplir la condición de seguridad incluso si esta resistencia se considera igual a cero. Por lo tanto, es necesario incorporar una resistencia externa de limitación de corriente que controle la corriente máxima del circuito.

La relación entre tensión, corriente y resistencia está dada por la Ley de Ohm:

$$
I=\frac{V}{R}
$$

Despejando la resistencia:

$$
R=\frac{V}{I}
$$

La corriente máxima permitida es:

$$
I_{max}=1mA
$$

Convirtiendo a amperios:

$$
I_{max}=0.001A
$$

Para garantizar que la corriente permanezca por debajo de este límite, la resistencia utilizada debe ser igual o superior al valor mínimo calculado.

### Cálculo para una alimentación de 3.3 V

Para una alimentación de:

$$
V=3.3V
$$

se obtiene:

$$
R_{min}=\frac{3.3V}{0.001A}
$$

$$
R_{min}=3300\Omega
$$

Por lo tanto:

$$
\boxed{R_{min}=3.3k\Omega}
$$

Esto significa que, considerando una resistencia de piel de $0\Omega$, una resistencia externa de al menos 3.3 kΩ limitaría teóricamente la corriente a un máximo de 1 mA cuando la alimentación sea de 3.3 V.

### Cálculo para una alimentación de 5 V

El peor caso corresponde a la máxima tensión de alimentación:

$$
V=5V
$$

Entonces:

$$
R_{min}=\frac{5V}{0.001A}
$$

$$
R_{min}=5000\Omega
$$

Por lo tanto:

$$
\boxed{R_{min}=5k\Omega}
$$

Este es el valor mínimo que debe considerarse cuando el sistema puede funcionar hasta 5 V y se desea limitar la corriente a 1 mA bajo la condición de:

$$
R_{skin}=0\Omega
$$

Por lo tanto, para cubrir todo el rango de alimentación establecido entre 3.3 V y 5 V, el diseño debe basarse en el peor caso correspondiente a 5 V.

## Verificación utilizando una resistencia de 68 kΩ

La guía de laboratorio especifica una resistencia de:

$$
\boxed{R=68k\Omega}
$$

como uno de los componentes disponibles para la práctica.

Se debe verificar si este valor permite cumplir la condición:

$$
I\leq1mA
$$

considerando nuevamente el peor caso:

$$
R_{skin}=0\Omega
$$

En este escenario, la resistencia total utilizada para limitar la corriente corresponde a:

$$
R_{total}=68k\Omega
$$

Debido a que 68 kΩ es significativamente mayor que el valor mínimo calculado de 5 kΩ para una alimentación de 5 V, se espera que la corriente resultante sea considerablemente inferior al límite de 1 mA.

### Corriente máxima con 5 V

Aplicando la Ley de Ohm:

$$
I=\frac{V}{R}
$$

Sustituyendo los valores:

$$
I=\frac{5V}{68000\Omega}
$$

se obtiene:

$$
I=7.35\times10^{-5}A
$$

Convirtiendo a miliamperios:

$$
I=0.0735mA
$$

Por lo tanto:

$$
\boxed{I_{max}=0.0735mA=73.5\mu A}
$$

Al comparar este resultado con el límite establecido:

$$
0.0735mA<1mA
$$

se verifica que la corriente máxima calculada se encuentra por debajo del valor permitido para la práctica.Por lo tanto, la resistencia de 68 kΩ cumple matemáticamente con el requisito de corriente máxima establecido, bajo las condiciones de cálculo indicadas.

## Corriente máxima con 3.3 V

Para una alimentación de 3.3 V:

$$
I=\frac{3.3V}{68000\Omega}
$$

$$
I=4.85\times10^{-5}A
$$

Por lo tanto:

$$
\boxed{I_{max}=0.0485mA=48.5\mu A}
$$

Comparando nuevamente con el límite:

$$
0.0485mA<1mA
$$

se verifica que la resistencia de 68 kΩ también cumple la condición cuando la alimentación es de 3.3 V.

## Consideraciones de seguridad para el sistema GSR

La seguridad constituye un aspecto fundamental en el diseño de un sistema de medición que establece contacto eléctrico con el cuerpo humano. En este caso, los electrodos estarán directamente en contacto con la piel, por lo que el circuito debe diseñarse de manera que la corriente permanezca limitada bajo las condiciones consideradas en la práctica. La guía establece como condición de diseño una corriente máxima de 1 mA y plantea el caso extremo de una resistencia de piel igual a cero. Esto permite realizar un diseño conservador en el que la protección no dependa de las propiedades variables de la piel. La resistencia de 68 kΩ permite obtener una corriente máxima teórica de 0.0735 mA con una alimentación de 5 V, valor que se encuentra considerablemente por debajo del límite establecido. Sin embargo, este cálculo corresponde al comportamiento teórico del circuito y no sustituye la verificación práctica del sistema.

Antes de realizar una medición sobre una persona se deben revisar cuidadosamente las conexiones, verificar la tensión de alimentación, comprobar el valor de la resistencia utilizada y confirmar que no existan conexiones que puedan generar una corriente inesperada. Además, los electrodos deben colocarse correctamente sobre la piel y mantenerse estables durante la medición. Una mala conexión, un movimiento excesivo o una modificación del contacto pueden afectar la señal obtenida y generar resultados que no correspondan directamente con una respuesta fisiológica. Por lo tanto, el desarrollo del sistema GSR debe considerar simultáneamente la seguridad eléctrica, la calidad de la adquisición y la correcta interpretación fisiológica de la señal.

Nota de seguridad: los valores de la IEC 60479 no deben interpretarse como una autorización para experimentar directamente con corrientes sobre personas. El circuito debe diseñarse de forma que la corriente quede limitada mediante componentes eléctricos y debe verificarse antes de conectar los electrodos al sujeto.

## Diseño del dispositivo vestible para captura de GSR

Se propone el diseño de un dispositivo vestible en forma de muñequera, cuyo objetivo es permitir la captura continua de las variaciones de la respuesta galvánica cutánea (GSR) y su posterior transmisión de forma alámbrica hacia un computador personal. Esta propuesta responde al objetivo de la práctica de desarrollar un sistema capaz de capturar las variaciones de la GSR de manera continua. La muñequera contará con dos electrodos metálicos de aluminio, que estarán en contacto directo con la piel y funcionarán como los electrodos encargados de realizar la medición de la conductancia cutánea. Para su fabricación se contempla el uso de aluminio 1500, aluminio 1100 o aluminio 6061-T6, seleccionando finalmente el material que proporcione mejores condiciones de contacto con la piel, facilidad de fabricación y estabilidad durante la adquisición de la señal. La guía de laboratorio contempla el uso de placas metálicas de acero inoxidable, aluminio u otros metales que no reaccionen con el sudor corporal como alternativa a los electrodos Ag-AgCl.

### Selección de la región anatómica

Se selecciona la muñeca como región anatómica para sujetar los electrodos debido a que permite implementar el sistema de manera sencilla y cómoda como un dispositivo vestible. La utilización de una muñequera facilita mantener los electrodos en una posición relativamente constante durante la medición, evitando que el usuario tenga que sostenerlos manualmente. Los dos electrodos estarán ubicados sobre la superficie de la piel de la muñeca, separados entre sí una distancia suficiente para establecer el contacto eléctrico necesario para la medición. La muñequera permitirá mantener una presión moderada y constante sobre los electrodos, buscando evitar movimientos excesivos que puedan generar cambios artificiales en la señal o interferencias asociadas al movimiento. La selección de esta región también busca facilitar las pruebas dinámicas planteadas en la práctica, ya que el dispositivo debe evaluarse mientras el sujeto permanece en reposo y también cuando realiza actividades como caminar, moverse o escribir.

### Sujeción y reducción de interferencias

Para mantener los electrodos en contacto con la piel se utilizará una muñequera ajustable, preferiblemente mediante cinta de velcro. De esta manera, el dispositivo podrá adaptarse al tamaño de la muñeca del usuario sin ejercer una presión excesiva. La guía contempla específicamente el uso de cintas de velcro entre los materiales disponibles para el desarrollo del dispositivo. La sujeción firme de los electrodos es importante para disminuir las variaciones producidas por el movimiento relativo entre el metal y la piel. Además, se procurará que ambas superficies metálicas tengan un contacto uniforme con la piel y que los cables de conexión queden asegurados a la muñequera para evitar que su movimiento genere perturbaciones adicionales en la señal. El diseño deberá buscar un equilibrio entre comodidad, estabilidad mecánica y calidad de la señal, debido a que una presión excesiva podría resultar incómoda para el usuario, mientras que una presión insuficiente podría producir un contacto inestable y aumentar el ruido de la medición.

### Transmisión de la señal

Los electrodos estarán conectados al circuito de acondicionamiento y adquisición de la GSR, el cual permitirá obtener las variaciones de la conductancia de la piel. Posteriormente, la señal será enviada mediante una conexión alámbrica hacia un Arduino UNO o Nano y desde este sistema hacia el computador personal para visualizar y analizar la señal obtenida. La guía establece el uso de un Arduino UNO o Nano y un computador con MATLAB como parte de los recursos disponibles para el estudiante. El sistema deberá garantizar que la corriente que circula a través del sujeto sea segura. De acuerdo con las condiciones planteadas en la práctica, se deben realizar los cálculos correspondientes para una alimentación entre 3,3 y 5 VDC, considerando incluso el caso extremo de una resistencia de piel igual a cero, con el propósito de garantizar que la corriente a través del sujeto no supere 1 mA. En conjunto, la propuesta consiste en una muñequera con dos electrodos de aluminio, conectados al circuito de medición y posteriormente al Arduino y al computador. El diseño busca proporcionar un sistema sencillo, cómodo y estable que permita adquirir la GSR en tiempo real y evaluar sus variaciones tanto en reposo como durante la realización de diferentes actividades.

# Referencias

1. Boucsein, W. (2012). *Electrodermal Activity*. Springer Science & Business Media.

2. Loggia, M. L., Juneau, M., & Bushnell, M. C. (2011). Autonomic responses to heat pain: Heart rate, skin conductance, and their relation to verbal ratings and stimulus intensity. *Pain, 152*(3), 592–598. https://doi.org/10.1016/j.pain.2010.11.032

3. Breimhorst, M., Sandrock, S., Fechir, M., Hausenblas, N., Geber, C., & Birklein, F. (2011). Do intensity ratings and skin conductance responses reliably discriminate between different stimulus intensities in experimentally induced pain? *The Journal of Pain, 12*(1), 61–70. https://doi.org/10.1016/j.jpain.2010.04.012

4. Figner, B., & Murphy, R. O. (2011). Using skin conductance in judgment and decision making research. En *A Handbook of Process Tracing Methods for Decision Research* (pp. 163–184). Psychology Press.

5. International Electrotechnical Commission (IEC). (2018). *IEC 60479-1:2018 — Effects of current on human beings and livestock — Part 1: General aspects*.

6. Universidad Militar Nueva Granada. *Guía de Preparación — Práctica de Laboratorio: Estimación del nivel de estrés basada en la respuesta galvánica cutánea (GSR)*. Laboratorio de Instrumentación Biomédica y Biosensores.
