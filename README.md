# PARCIALMALDONADO
PARCIAL SISTEMAS DIGITALES DANIEL ALEJANDRO MALDONADO SILVA

## ¿Cuál es la diferencia entre un latch y un flip flop?, además ¿cuáles son los diferentes tipos de latch y flip flops?

# Latch vs Flip-Flop

Un latch es un dispositivo de almacenamiento asíncrono que cambia su salida inmediatamente cuando cambian sus entradas (mientras esté habilitado), por lo que es sensible al nivel y más rápido, pero menos controlado. En cambio, un flip-flop es síncrono, ya que solo cambia su estado en un flanco de reloj (subida o bajada), lo que lo hace más estable y ampliamente usado en sistemas digitales. Los tipos de latch incluyen SR y D, mientras que los flip-flops más comunes son SR, D, JK y T, cada uno con funciones específicas de almacenamiento y control.


Tipos de Latch:

- SR Latch (Set-Reset): Usa entradas S y R para establecer o reiniciar el estado.
- Latch (Data): Simplifica el SR evitando estados inválidos.
![Imagen](https://github.com/dmaldonado0/PARCIALMALDONADO/blob/main/latch.png)

Tipos de Flip-Flop:

- SR Flip-Flop: Similar al latch SR pero controlado por reloj.
- D Flip-Flop: El más usado, almacena un bit de información.
- JK Flip-Flop: Mejora el SR eliminando estados inválidos.
- T Flip-Flop: Cambia de estado (toggle) en cada pulso.

![Imagen](https://github.com/dmaldonado0/PARCIALMALDONADO/blob/main/flipflop.jpg)

## ¿Cuál es la diferencia entre un multiplexor y un demultiplexor?. Desarrollar la explicación de un multiplexor 8 entradas y un demultiplexor de 8 salidas.

# Multiplexor vs Demultiplexor

Un multiplexor (MUX) es un circuito que selecciona una de varias entradas y la envía a una sola salida utilizando líneas de selección; por ejemplo, un MUX de 8 entradas usa 3 líneas de selección para elegir cuál entrada pasa a la salida. Por otro lado, un demultiplexor (DEMUX) realiza la operación inversa: toma una única entrada y la dirige hacia una de varias salidas según las líneas de selección. En resumen, el MUX concentra datos y el DEMUX distribuye datos.

| Multiplexor                  | Demultiplexor                |
| ---------------------------- | ---------------------------- |
| Muchas entradas → una salida | Una entrada → muchas salidas |
| Selecciona datos             | Distribuye datos             |

## Explicar de forma sencilla qué es un sumador completo, un sumador medio y circuitos secuenciales.

# Sumador medio, sumador completo y circuitos secuenciales

Un sumador medio (Half Adder) es un circuito combinacional que suma dos bits y genera una salida de suma y un acarreo. El sumador completo (Full Adder) amplía esta función al incluir un tercer bit de entrada (acarreo de entrada), permitiendo sumar números binarios más complejos al encadenarse. Por otro lado, los circuitos secuenciales son aquellos cuya salida depende no solo de las entradas actuales sino también de estados anteriores, ya que incorporan memoria; ejemplos típicos son contadores, registros y máquinas de estado.

## ¿Qué es un mapa de karnaugh? Y ¿para qué sirve?

# Mapa de Karnaugh

Un mapa de Karnaugh es una herramienta gráfica utilizada para simplificar funciones booleanas mediante la agrupación de valores iguales (generalmente unos) en potencias de dos dentro de una tabla organizada según las variables. Su objetivo es reducir expresiones lógicas, minimizar el número de compuertas necesarias y optimizar el diseño de circuitos digitales, facilitando así implementaciones más eficientes y económicas.

![Imagen](https://github.com/dmaldonado0/PARCIALMALDONADO/blob/main/mapaaaaaaaaaaaaaaaaa.png)



2. A

![Imagen](https://github.com/dmaldonado0/PARCIALMALDONADO/blob/main/2A.png)

Ecuación original:
<img width="375" height="52" alt="image" src="https://github.com/user-attachments/assets/c9958ae1-8063-41ee-8e77-4dae1a475b20" />

1: Reordenar:
<img width="368" height="56" alt="image" src="https://github.com/user-attachments/assets/0a23b73d-0a43-4961-bd90-31e0b5d8865a" />

2: Asociar correctamente

<img width="410" height="42" alt="image" src="https://github.com/user-attachments/assets/d82b09e0-1309-4f09-8331-a69b94d44cd1" />
entonces:
<img width="311" height="36" alt="image" src="https://github.com/user-attachments/assets/f499a938-a3db-4152-813f-0481faac480e" />


3: Aplicar propiedad

<img width="204" height="33" alt="image" src="https://github.com/user-attachments/assets/4a78508a-57ce-4a34-83e6-45ece8e3638e" />
entonces:
<img width="161" height="49" alt="image" src="https://github.com/user-attachments/assets/7317ec85-b2ba-4905-a35f-f0e99062e339" />

RESULTADO:

<img width="148" height="51" alt="image" src="https://github.com/user-attachments/assets/1f22f945-047e-44bf-8fb9-882a1a389f11" />

## CIRCUITO:
<img width="1456" height="323" alt="image" src="https://github.com/user-attachments/assets/b49e31c4-cbc9-4b86-979a-2c85e060b0c6" />




2. B

![Imagen](https://github.com/dmaldonado0/PARCIALMALDONADO/blob/main/2B.png)

Ecuacion original:
<img width="334" height="30" alt="image" src="https://github.com/user-attachments/assets/5dda8caa-d6d8-4faf-84b5-ad29df850223" />
1: Expandir
<img width="387" height="42" alt="image" src="https://github.com/user-attachments/assets/c04a0a35-6650-458a-b07d-73f554f8d78a" />

2: Simplificar términos
<img width="127" height="31" alt="image" src="https://github.com/user-attachments/assets/126e96ff-b9ec-4c36-bfbb-40a57c281c84" />
entonces:
<img width="166" height="56" alt="image" src="https://github.com/user-attachments/assets/13943678-68f9-4047-b046-6d4e1e23d780" />

<img width="123" height="32" alt="image" src="https://github.com/user-attachments/assets/34d59850-03dc-42b9-87bf-114c9e16e5aa" />
entonces:
<img width="273" height="47" alt="image" src="https://github.com/user-attachments/assets/b864b5a1-2a1b-42d3-b502-307c123d549a" />


3: Sustituir

4: Factor común
5: Propiedad lógica



## CIRCUITO:
<img width="1403" height="322" alt="image" src="https://github.com/user-attachments/assets/cf27c996-65d4-4d27-ae95-df6b71ed0fc2" />


3.
# Desarrolle un chatbot con las herramientas vistas en clase que haga lo siguiente:

- Analice directamente la temática de los semiconductores en el año 2026.

- las empresas más relevantes del sector y correlacione su impacto en el campo de los sistemas digitales.

## Si al chatbot se le pregunta sobre los sistemas digitales en la educación de las siguientes alternativas:

- Innovación en la Educación con semiconductores y sistemas digitales.

- Novedad e impacto de proyectos de sistemas digitales en la educación.

- Sistemas digitales y semiconductores en el futuro.



