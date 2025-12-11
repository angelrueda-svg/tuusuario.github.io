---
jupyter:
  colab:
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
  language_info:
    codemirror_mode:
      name: ipython
      version: 3
    file_extension: .py
    mimetype: text/x-python
    name: python
    nbconvert_exporter: python
    pygments_lexer: ipython3
    version: 3.13.9
  nbformat: 4
  nbformat_minor: 5
---


``` python
import turtle

t = turtle.Turtle()   # Crea una tortuga
t.forward(100)        # Avanza 100 unidades
turtle.done()         # Mantiene la ventana abierta
```



``` python
#Reto1. Simula el comportamiento de la tortuga usando solo print y input

print("Simulación de tortuga:")
# Se POSICIONO LA TORTUGA EN LA POSICION INICIAL 0 Y AVANZA 50 UNIDADES DIBUJANDO SU RASTRO
# Posición inicial
posicion = 0
print("La tortuga está en la posición:", posicion)

# Avanzar
input("Presiona ENTER para avanzar 50 unidades...")

# Dibujar rastro con '-' + flecha al final
pasos = 50
print("-" * (pasos - 1) + "→")   # 49 guiones + flecha

# Actualizar posición
posicion += pasos

# Mostrar nueva posición
print("La tortuga avanzó", pasos, "unidades.")
print("La nueva posición es:", posicion)
```


    Simulación de tortuga:
    La tortuga está en la posición: 0
    -------------------------------------------------→
    La tortuga avanzó 50 unidades.
    La nueva posición es: 50


![WhatsApp Image 2025-12-10 at 11 05 50 PM](https://github.com/user-attachments/assets/18ce6655-3746-4a5e-add4-97211d184501)




``` python
#Reto2. Simula la tortuga bajando usando solo print y input
#crea el rastro de una tortuga moviendose hacia abajo usando unicamente print e input.

print("Simulación de tortuga bajando:")
#la tortuga avanza hacia abajo dejando el rastro de su movimiento
pasos = 10  # cantidad de pasos hacia abajo

input("Presiona ENTER para que la tortuga comience a bajar...")

for i in range(pasos):
    print("|")

print("↓")  # flechita SOLO al final
```


    Simulación de tortuga bajando:
    |
    |
    |
    |
    |
    |
    |
    |
    |
    |
    ↓

![WhatsApp Image 2025-12-10 at 11 05 50 PM](https://github.com/user-attachments/assets/e7fb18b4-5807-4e14-852c-f9146876fa5a)




``` python
#Reto3. Tortuga avanzando hacia adelante y luego hacia abajo
# Crea el rastro de una tortuga moviendose hacia adelante y luego hacai abajo usando unicamente print e input.

print("Simulación de tortuga:\n")
# LA TORTUGA REALIZA UN RECORRIDO EN FORMA DE L
# Tramo horizontal
input("Presiona ENTER para avanzar 50 unidades hacia la derecha...")
print("-" * 49 + "→")   # Flecha al final del tramo horizontal

# Tramo vertical hacia abajo
input("Presiona ENTER para avanzar 10 líneas hacia abajo...")
for _ in range(9):
    print(" " * 49 + "|")
print(" " * 49 + "↓")   # Flecha al final del tramo vertical

print("\nLa tortuga ha terminado su recorrido.")
```

    Simulación de tortuga:

    -------------------------------------------------→
                                                     |
                                                     |
                                                     |
                                                     |
                                                     |
                                                     |
                                                     |
                                                     |
                                                     |
                                                     ↓

    La tortuga ha terminado su recorrido. 


<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/62620c69-f7f9-4720-b05d-5dc3b2376b11" />

    

``` python
#Reto4. Girar y dibujar usando solo print e input.
# ahora la tortuga no solo avanza: tambien gira, observa como lo hace la version grafica.

print("Simulación de tortuga dibujando escalones\n")
#LA TORTUGA DIBUJA 3 ESCALONES  SIGUIENDO INSTRUCCIONES Y DIBUJANDO SU RASTRO
# --- ESCALÓN 1 ---
print("Escalón 1:")
input("ENTER para avanzar 5...")
print("----" + "→")     # adelante(5) con flecha final

input("ENTER para bajar 2...")
print("    |")
print("    ↓")          # flecha hacia abajo

# --- ESCALÓN 2 ---
print("\nEscalón 2:")
input("ENTER para avanzar 5...")
print("---------" + "→")   # 10 guiones acumulados + flecha

input("ENTER para bajar 2...")
print("         |")
print("         ↓")        # flecha hacia abajo

# --- ESCALÓN 3 ---
print("\nEscalón 3:")
input("ENTER para avanzar 5...")
print("--------------" + "→")   # 15 guiones acumulados + flecha

input("ENTER para bajar 2...")
print("              |")
print("              ↓")        # flecha hacia abajo

print("\nDibujo terminado.")
```


    Simulación de tortuga dibujando escalones

    Escalón 1:
    ----→
        |
        ↓

    Escalón 2:
    ---------→
             |
             ↓

    Escalón 3:
    --------------→
                  |
                  ↓

    Dibujo terminado.
    
