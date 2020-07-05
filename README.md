# Tarea-4
Conclusión de la Tarea 4
1. Crear un esquema de modulación BPSK para los bits presentados. Esto implica asignar una forma de onda sinusoidal normalizada (amplitud unitaria) para cada bit y luego una concatenación de todas estas formas de onda.
La forma de onda de la portadora se observa a continuación:
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/ondaportadora.png">
Una gráfica de los primeros 5 bits modelados se observa a continuación:
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/Tx.png">
2. Calcular la potencia promedio de la señal modulada generada.
En esta sección se encontró la potencia promedio de la señal modulada, cuyo valor fue de: 0.49999999999999983
3. Simular un canal ruidoso del tipo AWGN (ruido aditivo blanco gaussiano) con una relación señal a ruido (SNR) desde -2 hasta 3 dB.
La simulación de un canal ruidoso del tipo AWGN con una relación señal ruido de -2 se observa en la siguiente imagen.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/SNR%3D-2.png">
La simulación de un canal ruidoso del tipo AWGN con una relación señal ruido de -1 se observa en la siguiente imagen.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/SNR%3D-1.png">
La simulación de un canal ruidoso del tipo AWGN con una relación señal ruido de 0 se observa en la siguiente imagen.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/SNR%3D0.png">
La simulación de un canal ruidoso del tipo AWGN con una relación señal ruido de -1 se observa en la siguiente imagen.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/SNR%3D-1.png">
La simulación de un canal ruidoso del tipo AWGN con una relación señal ruido de -2 se observa en la siguiente imagen.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/SNR%3D-2.png">
La simulación de un canal ruidoso del tipo AWGN con una relación señal ruido de -3 se observa en la siguiente imagen.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/SNR%3D-3.png">
A partir de las imágenes anteriores de observa que al aumentar el valor de SNR, se observa menos ruido en la señal.
4. Graficar la densidad espectral de potencia de la señal con el método de Welch (SciPy), antes y después del canal ruidoso.
La gráfica de la densidad espectral de potencia de la señal antes del canal ruidoso se observa a continuación.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/Antes.png">
La gráfica de la densidad espectral de potencia de la señal después del canal ruidoso se observa a continuación.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/Despu%C3%A9s.png">
5. Demodular y decodificar la señal y hacer un conteo de la tasa de error de bits (BER, bit error rate) para cada nivel SNR.
La tasa de error de bits para SNR= -2 es:    0.4974
El error total es:  4974.0
La tasa de error de bits para SNR= -1 es:    0.4974
El error total es:  4974.0
La tasa de error de bits para SNR= 0 es:   0.4974
El error total es:  4974.0
La tasa de error de bits para SNR= 1 es:   0.4974
El error total es: 4974.0
La tasa de error de bits para SNR= 2 es:    0.4974
El error total es:  4974.0
La tasa de error de bits para SNR= 3 es:  0.4974
6. Graficar BER versus SNR
La gráfica se observa a continuación.
<img src="https://github.com/Pamela2345/Tarea-4/blob/master/BER-SNR.png">
