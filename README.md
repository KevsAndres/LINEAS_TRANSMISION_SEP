# Proyecto Modelación y Operación de Líneas de Transmisión en Estado Estacionario

Desarrollar un programa empleando Python, que permita a partir de la selección de la configuración de una torre de línea de transmisión trifásica de tipo: 

- Simple circuito

- Doble circuito con secuencia de fases (abc-c'b'a' o abc-a'b'c').

Calcular los parámetros de la L/T con transposición (por unidad de longitud - km). Conociendo
las coordenadas de cada conductor en metros, el tipo de conductor (ACSR o ACAR), el nombre 
del conductor y sus especificaciones (de la hoja de datos del fabricante de conductor 
proporcionada), número de conductores por fase (hasta 4), distancia de conductores por fase 
(en centímetros).

Adicionalmente el programa podrá analizar las siguientes condiciones operativas:

1. Calcular Voltajes, Corrientes y Potencias de Envío y Recibo, además de las Pérdidas de 
la L/T, eficiencia y porcentaje de Regulación. Conocida la carga en el punto de recibo 
(expresada en potencia MW y Mvar) y el voltaje de operación en recibo (en kV) y la 
longitud de la línea (en km)

3. Calcular Voltajes, Corrientes y Potencias de Envío y Recibo, además de las Pérdidas de 
la L/T, eficiencia y porcentaje de Regulación. Conocida la generación en el punto de 
envío (expresada en potencia MW y Mvar) y el voltaje de operación en envío (en kV) y 
la longitud de la línea (en km).

Se deberá entregar el script desarrollado, así como un informe en formato IEEE, que contenga 
teoría básica acerca del modelamiento eléctrico de L/T, operación en estado estable de L/T, 
ejercicios de aplicación empleando la herramienta desarrollada, análisis de resultados, 
conclusiones, recomendaciones y bibliografía

Nota: Dependiendo de la longitud de la L/T el programa deberá emplear el modelo de L/T 
correspondiente (corta, media, larga).


![image](https://github.com/KevsAndres/LINEAS_TRANSMISION_SEP/assets/144057823/7633b530-41b3-46e3-89d3-9da3fe3e321c)

Disposición de conductores en una línea doble circuito secuencia abc-c'b'a'
