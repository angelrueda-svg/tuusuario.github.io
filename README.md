# Conceptos básicos de programación

## **¿Qué es un programa?**
Es un medio que utilizan las personas (programadores) para darle órdenes a una máquina.  
Así como los humanos usamos idiomas como inglés o español para comunicarnos, los programadores utilizan **lenguajes de programación** como **Java**, **Python** o **C++** para comunicarse con las computadoras.

---

## **Variables**
Son **espacios en la memoria** de un computador que se utilizan para **guardar temporalmente datos** mientras se ejecuta un algoritmo o programa.  
Ejemplo: almacenar el nombre, edad o resultado de una operación.

---

## **Constantes**
Las constantes son **valores que nunca cambian**, ni durante la ejecución de un algoritmo ni fuera de él.  
Permanecen fijos sin importar cuántas veces se usen o en qué parte del programa se apliquen.  
Ejemplo: el número π (3.1416) o el número e (2.718) son datos universales que no pueden modificarse.

---

## **Partes de un algoritmo**
Son los **componentes básicos** que permiten estructurar y organizar un conjunto de pasos lógicos para resolver un problema.  
Se dividen en tres partes fundamentales:
1. **Entrada:** datos que ingresan al sistema.  
2. **Proceso:** operaciones o pasos lógicos que transforman los datos.  
3. **Salida:** resultados generados después del procesamiento.

---

## **IDE Google Colaboratory**
**Google Colab** es un **entorno de desarrollo basado en la nube** que permite escribir y ejecutar código Python directamente desde el navegador, sin instalar nada en el computador.  
Fue creado por **Google** y tiene las siguientes ventajas:
- Integración con **Google Drive**.  
- Ejecución en **servidores en la nube**.  
- Bibliotecas de Python **preinstaladas**.  
- Entorno **colaborativo**, como en Google Docs.  

---

## **Ejemplo de código en Python**

```python
ciudad = input("¿En qué ciudad vives? ")
pais = input("¿En qué país naciste? ")
edad = int(input("¿Cuántos años tienes? "))
peso = float(input("¿Cuál es tu peso en kilogramos? "))
estudiante = bool(input("¿Eres estudiante? (Escribe True o False): "))

print(f"Vives en {ciudad}, {pais}. En 10 años tendrás {edad + 10} años.")
