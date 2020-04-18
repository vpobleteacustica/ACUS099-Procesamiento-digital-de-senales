# Universidad Austral de Chile.
# Instituto de Acústica.
## ACUS099: Procesamiento digital de señales.
### Descripción.
La asignatura Digital signal processing tiene como principal propósito que los estudiantes apliquen conocimientos en el área de procesamiento y análisis de señales, y fundamentando conceptualmente el procesamiento en el dominio digital en contextos de trabajo multidisciplinario.
* **Semestre:** 
  + Otoño 2020. 
* **Requisitos:** 
  + Física: ondas y electromagnetismo (BAIN085-14).
* **Docente responsable:** 
  + Dr. Víctor Poblete Ramírez, vpoblete@uach.cl 
* **Ayudante:**
  + Diego Espejo Alquinta, diego.espejo@alumnos.uach.cl 
### Contenidos
* **Unidad 1:** Secuencias y sistemas en el dominio del tiempo discreto.
  + 1.1 Secuencias (señales) básicas en tiempo discreto: Impulso unitario, escalón unitario, exponencial real, exponencial compleja, senoidal, cosenoial, periódicas y aperiódicas, combinación de secuencias.
  + 1.2 Sistemas discretos en el tiempo. Sistemas lineales y no lineales. Sistemas invariantes en el tiempo. Sistemas lineales e invariantes en el tiempo.
  + 1.3 Respuesta al impulso. Suma de convolución. 
  + 1.4 Respuesta en frecuencia de sistemas lineales e invariantes en el tiempo.

* **Unidad 2:** Secuencias y sistemas en dominio de la frecuencia.  
  + 2.1 Transformada de Fourier aplicada a secuencias. Respuesta impulso expresada como la transformada inversa de Fourier de la función de respuesta en frecuencia. Uso de ventanas.
  + 2.2 Propiedades, teoremas, y parejas de transformadas de Fourier.
  + 2.3 Teorema de modulación y teorema del muestreo (Nyquist).
  + 2.4 Transformada discreta de Fourier (DFT). Transformada inversa discreta de Fourier (IDFT). Transformada rápida de Fourier (FFT).

* **Unidad 3:** Transormada z. Transformada z inversa. Filtros en tiempo discreto. 
  + 3.1 Ecuaciones en diferencias lineales con coeficientes constantes.
  + 3.2 Plano complejo z, región de convergencia.
  + 3.3 Función del sistema o función de transferencia. Análisis de polos y ceros de la función de transferencia.
  + 3.4 Diseño de filtros en tiempo discreto: pasa bajo, pasa banda, pasa altos.
     
* **Unidad 4:** Nociones básicas de procesamiento de señales aleatorias.  
  + 4.1 Señales discretas randómicas en el tiempo.
  + 4.2 Señales degradas con ruido aleatorio por procesos de ruido o vibraciones.
  + 4.3 Densidad espectral de potencia usando FFT.
  + 4.4 Función de autocorrelación. Transformada de Fourier de la autocorrelación y  espectro de potencia.

### Proyectos: 
  + **Pueden ser resueltos en grupos de máximo dos estudiantes.**
  + **(P1) Suma de Convolución (20%).** Construir un código en Python que muestre una animación, paso paso, del proceso de suma de convolución entre dos secuencias. Debe mostrar gráficamente tres secuencias: las dos secuencias a convolucionar y la tercera es la secuencia resultante convolucionada. Se aplica lenguaje matemático y lenguaje de programación. El código tiene que estar bien organizado y con comentarios. Debe funcionar para cualquier señal acústica que se ingrese.
    + Entrega: A más tardar, el lunes 18 de Mayo, 16 horas. Cumplida la fecha de entreha, se descontará un punto por día de atraso. 
  + **(P2) Segmentar una señal acústica en tiempos cortos y construir espectrograma (20%).** Construir un código en Python que genere una matriz la cual contenga una señal segmentada en tiempo corto. A cada segmento, aplicar una ventana, por ejemplo, Hamming, y calcular la Transformada de Fourier. Debe representar además, la magnitud cuadrática de cada segmento a lo largo del tiempo (espectrograma). Se aplica lenguaje matemático y lenguaje de programación. 
    + Entrega: A más tardar, el lunes 8 de Junio, 16 horas. Cumplida la fecha de entreha, se descontará un punto por día de atraso.
  + **(P3) Representaciones para una señal acústica sin distorsión y degradada por ruido o vibración (20%).** Construir un código en Python que permita hacer representaciones de una señal acústica sin distorsión y degradada por ruido o vibración. Analizar las representaciones en tiempo y frecuencia, y usar Transformada de Fourier, filtros, espectrogramas, e histogramas. Se aplica lenguaje matemático y lenguaje de programación.
    + Entrega: A más tardar, el lunes 29 de Junio, 16 horas. Cumplida la fecha de entreha, se descontará un punto por día de atraso.

