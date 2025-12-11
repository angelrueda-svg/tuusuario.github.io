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

::: {#748aa2ed .cell .code id="748aa2ed"}
``` python
import turtle

t = turtle.Turtle()   # Crea una tortuga
t.forward(100)        # Avanza 100 unidades
turtle.done()         # Mantiene la ventana abierta
```
:::

::: {#e1d530be .cell .code id="e1d530be" outputId="a3eb7088-6206-4ec3-c2c3-3a402c45043e"}
``` python
#Reto1. Simula el comportamiento de la tortuga usando solo print y input

print("Simulación de tortuga:")
# Se POCISIONO LA TORTUGA EN LA POSICION INICIAL 0 Y AVANZA 50 UNIDADES DIBUJANDO SU RASTRO
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

::: {.output .stream .stdout}
    Simulación de tortuga:
    La tortuga está en la posición: 0
    -------------------------------------------------→
    La tortuga avanzó 50 unidades.
    La nueva posición es: 50
:::
:::

::: {#0947eaf5 .cell .code id="0947eaf5" outputId="4e487a4a-b901-489f-8c72-67ca9f166720"}
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

::: {.output .stream .stdout}
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
:::
:::

::: {#2b0f7e99 .cell .code id="2b0f7e99" outputId="7f9fadec-0e44-4150-fd01-da41f3e581bf"}
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

::: {.output .stream .stdout}
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
:::
:::

::: {#353c14bd .cell .code id="353c14bd" outputId="7557285e-f9a2-4f4a-c796-b367f513d6a8"}
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

::: {.output .stream .stdout}
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
:::
:::

::: {#e5e0f4f1 .cell .code execution_count="5"}
``` python

## Reto 4 -- Dibujar escalones
python
print("Simulación de tortuga dibujando escalones\n")

print("Escalón 1:")
input("ENTER para avanzar 5...")
print("----→")
input("ENTER para bajar 2...")
print("    |")
print("    ↓")

print("\nEscalón 2:")
input("ENTER para avanzar 5...")
print("---------→")
input("ENTER para bajar 2...")
print("         |")
print("         ↓")

print("\nEscalón 3:")
input("ENTER para avanzar 5...")
print("--------------→")
input("ENTER para bajar 2...")
print("              |")
print("              ↓")

print("\nDibujo terminado.")

```

::: {.output .error ename="NameError" evalue="name 'python' is not defined"}
    ---------------------------------------------------------------------------
    NameError                                 Traceback (most recent call last)
    Cell In[5], line 2
          1 ## Reto 4 -- Dibujar escalones
    ----> 2 python
          3 print("Simulación de tortuga dibujando escalones\n")
          5 print("Escalón 1:")

    NameError: name 'python' is not defined
:::
:::
