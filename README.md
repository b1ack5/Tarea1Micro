En esta programación la función ADC_Init() configura el módulo ADC (Conversor Analógico-Digital). 

Después, la función ADC_Read() convierte la señal analógica en un valor digital de 10 bits, es decir, del 0 al 1023.

Para inicializar el PWM utilizamos la función PWM_Init(), la cuál configura el módulo PWM en el pin RC2.

Por último, para ajustar el ciclo de trabajo utilizamos la función PWM_SetDuty(), la cual ajusta el ciclo de trabajo del PWM según la lectura del ADC.
