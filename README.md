# Simulacion-y-analisis-de-senales-con-la-transformada-de-Fourier
#El objetivo de esta actividad es analizar señales en el dominio del tiempo y frecuencia utilizando MATLAB o Python. Aplicarás la Transformada de Fourier #para visualizar cómo las señales se representan en ambos dominios y compararás los resultados obtenidos. 
##Señales en el Dominio del Tiempo

Se generan tres tipos de señales básicas:

1. **Señal Senoidal**
   - Frecuencia: 5 Hz
   - Fórmula: `sin(2πft)`
   - Representa una onda continua y periódica.

2. **Señal Escalón (Heaviside)**
   - Comienza en `t = 0.5` segundos.
   - Representa una transición repentina de 0 a 1.

3. **Pulso Rectangular**
   - Activa entre `t = 0.4` y `t = 0.6` segundos.
   - Representa una señal binaria de duración limitada.
   
##Análisis en el Dominio de Frecuencia

Se aplica la **Transformada de Fourier (FFT)** a cada señal para observar su comportamiento en el espectro de frecuencia:

- **Espectro de Señal Senoidal**: Pico claro en la frecuencia de 5 Hz.
- 
- **Espectro de Señal Escalón**: Contenido de baja frecuencia dominante.
- 
- **Espectro de Pulso Rectangular**: Distribución amplia de frecuencias debido a la discontinuidad.
