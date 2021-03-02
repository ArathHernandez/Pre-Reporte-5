# Pre-Reporte-5

Diseña un reloj-alarma digital en VHDL. Tu entidad deberá tener las siguientes entradas y salidas:

Entrada (1 bit)
clk_in (señal de reloj)
Salidas
hrs_dec (decenas de horas, 1 bit)
hrs_uni (unidades de horas, 4 bits)
min_dec (decenas de minutos, 3 bits)
min_uni (unidades de minutos, 4 bits)
seg_dec (decenas de segundos, 3 bits)
seg_uni (unidades de segundos, 4 bits)
Considerar las siguientes restricciones:

Diseñar un flip-flop J-K
Diseñar un contador sincrónico MOD6, instanciando tres flip-flops J-K
Diseñar un contador sincrónico MOD10, instanciando cuatro flip-flops J-K
Diseñar un contador MOD60 BCD, que servirá para contar segundos, instanciando el contador MOD10 y el contador MOD6
Diseñar un contador MOD60 BCD más, que servirá para contar minutos
Diseñar un contador MOD12 BCD, que servirá para contar horas en formato de 12 horas (es decir, 00:00 a 11:59 tanto para AM, como para PM)
Finalmente, asignar las señales de los contadores a las salidas de su entidad
