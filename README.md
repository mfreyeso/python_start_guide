# Python Start Guide

Este repositorio contiene un conjunto de ejercicios que pueden ser de gran utilidad para aprender Python y desarrollar capacidades alrededor de Ciencia de Datos.

Los ejercicios propuestos son los siguientes:

1. Hello World con Python
2. Calculadora de Decimales y Binarios
3. Usando Archivos
4. Creando un primer modelo de Aprendizaje Automatico en Kaggle.

## Prerequisitos

1. Instalar Python (3.7 version recomendada) en su computador, descargar el instalador de acuerdo a su sistema operativo.
https://www.python.org/downloads/
2. Instalar VSCode en su computador de acuerdo a su sistema operativo.
https://code.visualstudio.com/download
3. Instalar complemento de Python para VSCode. El siguiente video puede ejemplificar el proceso. https://www.youtube.com/watch?v=-IyA_Yvs8IQ

## Hello World con Python

* Crea un archivo Python, con extension .py dentro del directorio `hello_world`. 
* Dentro del arhivo utiliza la funcion print para escribir tu mensaje de saludo al mundo con Python. 🤓
* Ejecuta el programa utilizando la opción `Run` de VSCode.

## Calculadora de Decimales y Binarios

Cree un calculadora de decimales y binarios utilizando Python.

La calculadora debe recibir dos operandos y un operador y entregar el resultado. Los operadores disponibles seran:

* Suma +
* Resta -
* Multiplicación *
* Division /
* Modulo %
* Potencia **

Las siguientes operaciones binarias tambien estaran disponibles. Los operandos recibidos se deberan convertir a decimales antes de la operación y el resultado deberá ser el valor decimal del binario.
* XOR
* XNOR
* OR-FLIP (Cambiar de 0 a 1, o de 1 a 0 y convertir para cada operando y aplicar la funcion OR entre los valores)

La calculadora se detendra si algun operando es el caracter 'Q'

Pistas:
* Leer la entrada (operandos) con la funcion _input_ y validar que sea un numero entero, si el numero es flotante, convierta a entero.
* Validar que el operador sea alguno de los signos definidos o de las funciones binarias definidas.

Siguientes Pasos:
*  Crea una interfaz grafica para tu calculadora con Tkinter
https://docs.python.org/es/3/library/tk.html

## Usando Archivos

Cree un programa Python dentro del directorio `deduplication` para extraer el maximo valor reportado por cada sensor del archivo `sensor_data.txt`.

Cada fila contiene un identificador (sensor) y una medida de temperatura, escriba el valor maximo registrado por cada sensor en un nuevo archivo llamado `unique_records.txt`

_Pista_: Utiliza diccionarios y conjuntos

## Creando un primer modelo de Aprendizaje Automatico en Kaggle.

Unase a Kaggle, una comunidad de cientificos de datos e ingenieros de machine learning, donde puede encontrar diversos recursos para aprender sobre aprendizaje automatico.

Puede comenzar con este curso para familiarizarse en la plataforma:

https://www.kaggle.com/learn/intro-to-machine-learning

