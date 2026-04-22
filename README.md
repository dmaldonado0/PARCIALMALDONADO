# PARCIALMALDONADO
PARCIAL SISTEMAS DIGITALES DANIEL ALEJANDRO MALDONADO SILVA

## 1.1 ¿Cuál es la diferencia entre un latch y un flip flop?, además ¿cuáles son los diferentes tipos de latch y flip flops?

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

## 1.2 ¿Cuál es la diferencia entre un multiplexor y un demultiplexor?. Desarrollar la explicación de un multiplexor 8 entradas y un demultiplexor de 8 salidas.

# Multiplexor vs Demultiplexor

Un multiplexor (MUX) es un circuito que selecciona una de varias entradas y la envía a una sola salida utilizando líneas de selección; por ejemplo, un MUX de 8 entradas usa 3 líneas de selección para elegir cuál entrada pasa a la salida. Por otro lado, un demultiplexor (DEMUX) realiza la operación inversa: toma una única entrada y la dirige hacia una de varias salidas según las líneas de selección. En resumen, el MUX concentra datos y el DEMUX distribuye datos.

| Multiplexor                  | Demultiplexor                |
| ---------------------------- | ---------------------------- |
| Muchas entradas → una salida | Una entrada → muchas salidas |
| Selecciona datos             | Distribuye datos             |

## 1.3 Explicar de forma sencilla qué es un sumador completo, un sumador medio y circuitos secuenciales.

# Sumador medio, sumador completo y circuitos secuenciales

Un sumador medio (Half Adder) es un circuito combinacional que suma dos bits y genera una salida de suma y un acarreo. El sumador completo (Full Adder) amplía esta función al incluir un tercer bit de entrada (acarreo de entrada), permitiendo sumar números binarios más complejos al encadenarse. Por otro lado, los circuitos secuenciales son aquellos cuya salida depende no solo de las entradas actuales sino también de estados anteriores, ya que incorporan memoria; ejemplos típicos son contadores, registros y máquinas de estado.

## 1.4 ¿Qué es un mapa de karnaugh? Y ¿para qué sirve?

# Mapa de Karnaugh

Un mapa de Karnaugh es una herramienta gráfica utilizada para simplificar funciones booleanas mediante la agrupación de valores iguales (generalmente unos) en potencias de dos dentro de una tabla organizada según las variables. Su objetivo es reducir expresiones lógicas, minimizar el número de compuertas necesarias y optimizar el diseño de circuitos digitales, facilitando así implementaciones más eficientes y económicas.

![Imagen](https://github.com/dmaldonado0/PARCIALMALDONADO/blob/main/mapaaaaaaaaaaaaaaaaa.png)

# 2. A

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


# 2. B

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
<img width="253" height="52" alt="image" src="https://github.com/user-attachments/assets/8efed1e8-e7ca-4004-930a-e9dd432f3346" />

4: Factor común
<img width="246" height="50" alt="image" src="https://github.com/user-attachments/assets/29b92e17-1cfe-4038-80e4-0d7340f85782" />

5: Propiedad lógica
<img width="150" height="44" alt="image" src="https://github.com/user-attachments/assets/014692d7-725d-4106-92fa-9b293c1c3f3b" />
entonces:
<img width="116" height="39" alt="image" src="https://github.com/user-attachments/assets/76cccafa-e074-432c-8909-432f69eb44e3" />
RESULTADO:
<img width="116" height="39" alt="image" src="https://github.com/user-attachments/assets/397d5884-404d-4b95-bb05-f327d21a6f46" />




## CIRCUITO:


# 3. Desarrolle un chatbot con las herramientas vistas en clase que haga lo siguiente:

- Analice directamente la temática de los semiconductores en el año 2026.

- las empresas más relevantes del sector y correlacione su impacto en el campo de los sistemas digitales.

## Si al chatbot se le pregunta sobre los sistemas digitales en la educación de las siguientes alternativas:

- Innovación en la Educación con semiconductores y sistemas digitales.

- Novedad e impacto de proyectos de sistemas digitales en la educación.

- Sistemas digitales y semiconductores en el futuro.


  # >>>>>>>> CODIGO <<<<<<<<<

```cpp

import requests

API_KEY = 'TU_API_KEY_AQUI'
API_URL = 'https://api.deepseek.com/v1/chat/completions'


def enviar_mensaje(mensaje, modelo='deepseek-chat'):
    headers = {
        'Authorization': f'Bearer {API_KEY}',
        'Content-Type': 'application/json'
    }

    mensajes = [
        {
            'role': 'system',
            'content': '''
Eres un experto en sistemas digitales y semiconductores en el año 2026.

Tu estilo es analítico, educativo y explicativo.
Explicas paso a paso como un profesor universitario.

Tu conocimiento incluye:

- Evolución de los semiconductores en 2026
- Empresas líderes del sector:
  NVIDIA, Intel, AMD, TSMC, Samsung
- Impacto de los semiconductores en los sistemas digitales
- Innovaciones tecnológicas (IA, chips avanzados, litografía, etc.)

También debes responder temas educativos como:

- Innovación en la educación con semiconductores y sistemas digitales
- Impacto de proyectos educativos en sistemas digitales
- Futuro de los sistemas digitales y semiconductores

Reglas:

- Explica de forma clara, profunda y bien estructurada
- Relaciona SIEMPRE empresas con sistemas digitales cuando aplique
- Da ejemplos reales y actuales (2026)
- No des respuestas cortas
- Si el tema es educativo, desarrolla ideas completas
- Puedes hacer preguntas al usuario para profundizar
'''
        },
        {
            'role': 'user',
            'content': mensaje
        }
    ]

    data = {
        'model': modelo,
        'messages': mensajes,
        'temperature': 0.8
    }

    try:
        response = requests.post(API_URL, headers=headers, json=data)
        response.raise_for_status()
        return response.json()['choices'][0]['message']['content']

    except Exception as e:
        return f"Error: {e}"


def mostrar_menu():
    print("\n===== CHATBOT SEMICONDUCTORES 2026 =====")
    print("1. Semiconductores en 2026")
    print("2. Empresas del sector y su impacto")
    print("3. Innovación en educación")
    print("4. Proyectos en sistemas digitales")
    print("5. Futuro de semiconductores y sistemas digitales")
    print("6. Pregunta libre")
    print("7. Salir")
    print("========================================")


def manejar_opcion(opcion):
    if opcion == "1":
        return "Analiza la situación de los semiconductores en el año 2026"
    elif opcion == "2":
        return "Explica las empresas más importantes de semiconductores y su impacto en los sistemas digitales"
    elif opcion == "3":
        return "Explica la innovación en la educación con semiconductores y sistemas digitales"
    elif opcion == "4":
        return "Explica la novedad e impacto de proyectos de sistemas digitales en la educación"
    elif opcion == "5":
        return "Explica el futuro de los semiconductores y sistemas digitales"
    elif opcion == "6":
        return input("Escribe tu pregunta: ")
    elif opcion == "7":
        return None
    else:
        print("Opción inválida")
        return ""


def main():
    print("Chatbot de Semiconductores y Sistemas Digitales (2026)")
    print("Escribe '7' para salir")

    while True:
        mostrar_menu()
        opcion = input("Selecciona una opción: ")

        if opcion == "7":
            print("Hasta luego")
            break

        mensaje = manejar_opcion(opcion)

        if mensaje:
            print("\nGenerando respuesta...\n")
            respuesta = enviar_mensaje(mensaje)
            print(respuesta)


if __name__ == "__main__":
    main()

```





