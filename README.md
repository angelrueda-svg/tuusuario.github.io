# Conceptos básicos de programación

## **¿Qué es un programa?**
Es un medio que utilizan las personas (programadores) para darle órdenes a una máquina.  
Así como los humanos usamos idiomas como inglés o español para comunicarnos, los programadores utilizan **lenguajes de programación** como **Java**, **Python** o **C++** para comunicarse con las computadoras.

## **Tipos de lenguaje de programación**
## **Interpretados** 
las ordenes son traducidas una a una por una aplicación, por ejmeplo Python, Pearl y Bash.
## **Compilados** 
son las instrucciones traducidas por grupo por una aplicación, como por ejemplo Fortran, C/C++.
## **Intermedios** 
son como una fución entre compilados y interprados, osea mitad y mitad, ejemplo Java y scala.

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

## **Algoritmo**
es un conjunto de pasos o instrucciones dadas en orden que permiten ejecutar y resolver un problema o una tarea.

---

## **Partes de un algoritmo**
Son los **componentes básicos** que permiten estructurar y organizar un conjunto de pasos lógicos para resolver un problema.  
Se dividen en tres partes fundamentales:
1. **Entrada:** datos que ingresan al sistema.  
2. **Proceso:** operaciones o pasos lógicos que transforman los datos.  
3. **Salida:** resultados generados después del procesamiento.

---

## **Tipos de datos en programación**
- Entero (INT) son aquellos que no tienen decimales
- Decimal (FLOAD) guarda los numeros con parte decimal como medidas o valores con precisión
- Boleano (BOOL) solo representa dos valores los cuales son: true o false osea verdadero o falso
- Cadena de texto (STR) almacena textos o caracteres, como palabras y simbolos
- Binario: es la forma basica en la que el computador representa la información y se guarda internamente usando 0 y 1
- Fecha: se usa para representar valores de tiempo, meses, años, horas, minutos e incluso segundos
  
 --- 

## **IDE Google Colaboratory**
**Google Colab** es un **entorno de desarrollo basado en la nube** que permite escribir y ejecutar código Python directamente desde el navegador, sin instalar nada en el computador.  
Fue creado por **Google** y tiene las siguientes ventajas:
- Integración con **Google Drive**.  
- Ejecución en **servidores en la nube**.  
- Bibliotecas de Python **preinstaladas**.  
- Entorno **colaborativo**, como en Google Docs.  

---

## **Reflexion personal**

En el transcurso de estas clases y durante el desarrollo de esta primera actividad comprendí que programar no es solo escribir código, sino pensar de forma lógica y ser cuidadoso con cada detalle.
Incluso un pequeño error —como colocar un punto o una letra mal— puede afectar todo el programa.
He aprendido a valorar el trabajo de los programadores y me he dado cuenta de que realmente disfruto este proceso y quiero seguir aprendiendo sobre el mundo de la programación.

---
##**Referencias**
-https://chatgpt.com/share/690ac7e9-7e2c-800e-ab1c-34bea4d3f0c5
-https://chatgpt.com/share/690b4760-4cdc-800e-bc7d-01b4ad2a9b40
-https://chatgpt.com/share/690df993-5360-800e-a648-56bd998acded
---

## **Ejemplo de código en Python**

```python
ciudad = input("¿En qué ciudad vives? ")
pais = input("¿En qué país naciste? ")
edad = int(input("¿Cuántos años tienes? "))
peso = float(input("¿Cuál es tu peso en kilogramos? "))
estudiante = bool(input("¿Eres estudiante? (Escribe True o False): "))

print(f"Vives en {ciudad}, {pais}. En 10 años tendrás {edad + 10} años.")
