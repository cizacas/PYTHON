# PYTHON
- [PYTHON](#python)
  - [Introducción](#introducción)
  - [Instalación de Python en el entorno windows](#instalación-de-python-en-el-entorno-windows)
    - [**Ventajas de esta instalación:**](#ventajas-de-esta-instalación)
  - [Configuración del entorno de desarrollo integrado (IDE)](#configuración-del-entorno-de-desarrollo-integrado-ide)
    - [**Ventajas de VS Code para Python:**](#ventajas-de-vs-code-para-python)
    - [Extensiones recomendadas de Python en VS Code:](#extensiones-recomendadas-de-python-en-vs-code)
    - [**¿Qué es Pylint?**](#qué-es-pylint)
      - [1. **Detectar errores antes de ejecutar**](#1-detectar-errores-antes-de-ejecutar)
      - [2. **Mejorar la calidad del código**](#2-mejorar-la-calidad-del-código)
      - [3. **Seguir las convenciones de Python (PEP 8)**](#3-seguir-las-convenciones-de-python-pep-8)
      - [4. **Aprender mientras programas**](#4-aprender-mientras-programas)
      - [Ejemplo práctico:](#ejemplo-práctico)
      - [¿Es necesario para empezar?](#es-necesario-para-empezar)
    - [¿Qué es Jupyter?](#qué-es-jupyter)
      - [1. **Experimentar paso a paso**](#1-experimentar-paso-a-paso)
      - [2. **Combinar código con explicaciones**](#2-combinar-código-con-explicaciones)
      - [3. **Ideal para aprendizaje**](#3-ideal-para-aprendizaje)
      - [4. **Muy usado en ciencia de datos**](#4-muy-usado-en-ciencia-de-datos)
      - [Ejemplo de uso:](#ejemplo-de-uso)
      - [¿Es esencial para empezar?](#es-esencial-para-empezar)
    - [Configurar el VSCode: **Detectar la versión de Python** y **Configurar el intérprete**](#configurar-el-vscode-detectar-la-versión-de-python-y-configurar-el-intérprete)
  - [Modo interactivo](#modo-interactivo)
  - [Utilizar comentarios](#utilizar-comentarios)
  - [Definición de variables](#definición-de-variables)
  - [Tipos de datos](#tipos-de-datos)

## Introducción
`Python` es un lenguaje de programación potente y fácil de aprender. Tiene estructuras de datos de alto nivel eficientes y un simple pero efectivo sistema de programación orientado a objetos. La elegante sintaxis de Python y su tipado dinámico, junto a su naturaleza interpretada lo convierten en un lenguaje ideal para scripting y desarrollo rápido de aplicaciones en muchas áreas, para la mayoría de plataformas.

`El intérprete de Python` y la extensa librería estándar se encuentran disponibles libremente en código fuente y de forma binaria para la mayoría de las plataformas desde [la Web de Python](https://www.python.org/)y se pueden distribuir libremente. El mismo sitio también contiene distribuciones y referencias a muchos módulos libres de Python de terceros, programas, herramientas y documentación adicional.

`El intérprete de Python` es fácilmente extensible con funciones y tipos de datos implementados en C o C++ (u otros lenguajes que permitan ser llamados desde C). Python también es apropiado como un lenguaje para extender aplicaciones modificables.

`Python` es un lenguaje interpretado, lo cual puede ahorrarte mucho tiempo durante el desarrollo ya que no es necesario compilar ni enlazar. El intérprete puede usarse interactivamente, lo que facilita experimentar con características del lenguaje, escribir programas desechables o probar funciones cuando se hace desarrollo de programas de abajo hacia arriba. Es también **una calculadora** de escritorio práctica.

`Python` permite escribir programas compactos y legibles. Los programas en Python son típicamente más cortos que sus programas equivalentes en C, C++ o Java por varios motivos:

* Los tipos de datos de alto nivel permiten expresar operaciones complejas en una sola instrucción.
* La agrupación de instrucciones se hace mediante indentación en vez de llaves de apertura y cierre.
* No es necesario declarar variables ni argumentos.

Por cierto, el lenguaje recibe su nombre del programa de televisión de la BBC «Monty Python’s Flying Circus» y no tiene nada que ver con reptiles. Hacer referencias sobre Monty Python en la documentación no sólo esta permitido, ¡sino que también está bien visto!

## Instalación de Python en el entorno windows

1. **Ir a la página oficial:**
   - Visita: https://python.org
   - Haz clic en "Downloads"
   - Descarga la versión más reciente (Python 3.13.x)

2. **Durante la instalación:**
   - ✅ **MUY IMPORTANTE:** Marca "Add Python to PATH"
   - ✅ Marca "Install launcher for all users"
   - Haz clic en "Install Now

3. **Verificar la instalación:**
   - Abre "Símbolo del sistema" o "PowerShell"
   - Escribe: `python --version`
   - Deberías ver algo como: `Python 3.13.x`

4. **Configurar VS Code:**
   - Abre VS Code en Windows
   - Instala la extensión de Python
   - VS Code detectará automáticamente tu instalación

### **Ventajas de esta instalación:**
- ✅ Más simple y directa
- ✅ Mejor integración con Windows
- ✅ Acceso a todas las librerías
- ✅ Mejor rendimiento

## Configuración del entorno de desarrollo integrado (IDE)

Para comenzar a aprender Python, instalaremos **Visual Studio Code** (VS Code) como IDE. Es una excelente opción por estas razones:

### **Ventajas de VS Code para Python:**

1. **Gratuito y de código abierto**
2. **Excelente soporte para Python** con extensiones oficiales
3. **IntelliSense** (autocompletado inteligente)
4. **Depurador integrado**
5. **Terminal integrado**
6. **Soporte para Jupyter Notebooks**
7. **Control de versiones Git integrado**
8. **Gran cantidad de extensiones útiles**

### Extensiones recomendadas de Python en VS Code:

Instalar las extensiones esenciales: 
* Python
* Pylint , **Pylint** es una herramienta muy útil para principiantes en Python. 
* Jupiter
### **¿Qué es Pylint?**
Pylint es un **analizador de código estático** que te ayuda a:

#### 1. **Detectar errores antes de ejecutar**
- Encuentra errores de sintaxis
- Detecta variables no definidas
- Identifica importaciones incorrectas

#### 2. **Mejorar la calidad del código**
- Te sugiere mejores prácticas de programación
- Detecta código redundante o innecesario
- Identifica funciones o variables no utilizadas

#### 3. **Seguir las convenciones de Python (PEP 8)**
- Te ayuda a escribir código más legible
- Sugiere nombres de variables más claros
- Corrige problemas de formato y espaciado

#### 4. **Aprender mientras programas**
- Te da consejos sobre cómo mejorar tu código
- Explica por qué algo puede ser problemático
- Te enseña buenas prácticas de Python

#### Ejemplo práctico:

Si escribes esto:
```python
def miFuncion():  # Pylint sugiere usar snake_case: mi_funcion
    x=1+2         # Pylint sugiere espacios: x = 1 + 2
    return x
```

Pylint te mostrará:
- ⚠️ "Function name should be in snake_case"
- ⚠️ "Missing whitespace around operator"

#### ¿Es necesario para empezar?
No es **esencial**, pero es **muy recomendado** porque:
- Te ayuda a aprender las mejores prácticas desde el inicio
- Evita que desarrolles malos hábitos
- Hace tu código más profesional y legible

### ¿Qué es Jupyter?

Jupyter te permite crear **notebooks interactivos** donde puedes:

#### 1. **Experimentar paso a paso**
- Ejecutas código en pequeñas celdas
- Ves el resultado inmediatamente
- Puedes modificar y volver a ejecutar fácilmente

#### 2. **Combinar código con explicaciones**
- Mezclas código Python con texto explicativo
- Documentas lo que haces mientras aprendes
- Creas "cuadernos de notas" de programación

#### 3. **Ideal para aprendizaje**
- Perfecto para tutoriales y ejercicios
- Puedes probar conceptos sin crear archivos completos
- Visualizas datos y gráficos directamente

#### 4. **Muy usado en ciencia de datos**
- Análisis de datos
- Machine Learning
- Visualización de gráficos

#### Ejemplo de uso:

**Celda 1:**
```python
# Mi primera variable
nombre = "Ana"
edad = 25
print(f"Hola {nombre}, tienes {edad} años")
```
**Resultado:** `Hola Ana, tienes 25 años`

**Celda 2:**
```python
# Probemos una lista
numeros = [1, 2, 3, 4, 5]
suma = sum(numeros)
print(f"La suma es: {suma}")
```
**Resultado:** `La suma es: 15`

#### ¿Es esencial para empezar?
- **No es obligatorio**, puedes aprender Python con archivos `.py` normales
- **Pero es muy recomendado** porque hace el aprendizaje más interactivo y visual
- Es **estándar** en cursos de Python y ciencia de datos

### Configurar el VSCode: **Detectar la versión de Python** y **Configurar el intérprete**
- Encuentra qué versión de Python tienes instalada
- Se asegura de que VS Code use la correcta
- Le dice a VS Code dónde encontrar Python
- Permite que el autocompletado funcione correctamente
  
  - Cuando instalas Python en Windows usando el instalador oficial, por defecto lo instala en una de estas rutas:
    - Para todos los usuarios:  
  `C:\Program Files\Python3x\`  
  (por ejemplo, `C:\Program Files\Python313\`)
    - Solo para el usuario actual:  
  `C:\Users\<tu_usuario>\AppData\Local\Programs\Python\Python3x\`  
  (por ejemplo, Python313)
El ejecutable principal es `python.exe` dentro de esa carpeta. 
- Si usas una versión específica o un entorno virtual, debes apuntar a esa ruta
Sí, existe una configuración de intérprete de Python a nivel de usuario en VS Code, normalmente en el archivo `settings.json` ubicado en %APPDATA%/Code/User/settings.json en Windows.

En ese archivo puedes encontrar (o agregar) el parámetro:
```json
{
  "python.defaultInterpreterPath": "C:\\ruta\\a\\tu\\python.exe"
}
```
Asegúrate de reemplazar `"C:\\ruta\\a\\tu\\python.exe"` con la ruta correcta a tu instalación de Python.

## Modo interactivo
Cuando se leen los comandos desde un terminal, se dice que el intérprete está en modo interactivo. En este modo, espera el siguiente comando con el prompt primario, generalmente tres signos de mayor que (>>>); para las líneas de continuación, aparece el prompt secundario, por defecto tres puntos (...). El intérprete imprime un mensaje de bienvenida que indica su número de versión y un aviso de copyright antes de imprimir el primer prompt primario:
```python
$py 
Python 3.13.7 (tags/v3.13.7:bcee1c3, Aug 14 2025, 14:15:11) [MSC v.1944 64 bit (AMD64)] on win32
Type  "help", "copyright", "credits" or "license" for more information.

>>> print("Hola, Mundo!")
... 
Hola, Mundo! 
>>>
```

## Utilizar comentarios 
Los comentarios en Python comienzan con el carácter numeral,**#**, y se extienden hasta el final visible de la línea. Un comentario quizás aparezca al comienzo de la línea o seguido de espacios en blanco o código, pero no dentro de una cadena de caracteres.
```python
# este es el primer comentario
spam = 1  # este es el segundo comentario
          # ... este es el tercer comentario!
text = "# este no es un comentario porque está entre comillas dobles."
```
## Definición de variables
Una variable es un nombre que se refiere a un valor. En Python, no es necesario declarar una variable antes de usarla o declarar su tipo. Una variable se crea en el momento en que se le asigna un valor por primera vez.
```python  
counter = 100          # un número entero
miles = 1000.0        # un número decimal
name = "John"       # una cadena de texto
print(counter)
print(miles)
print(name)
```
## Tipos de datos
Python tiene varios tipos de datos integrados, algunos de los más comunes son:

1. **Numéricos**: `int`, `float`, `complex`
Podemos utilizar python como una calculadora. El intérprete funciona como una simple calculadora: puedes introducir una expresión en él y este escribirá los valores. La sintaxis es sencilla: los operadores +, -, * y / se pueden usar para realizar operaciones aritméticas; los paréntesis (()) pueden ser usados para agrupar. Por ejemplo:
```python
>>> 2 + 2
4
>>> 50 - 5*6
20
>>> (50 - 5*6) / 4
5.0
>>> 8 / 5  # división siempre devuelve un flotante
1.6
>>> 5 * 3 + 2  # combina ambos
17
```
El operador // (división entera) trunca el resultado a un número entero:
```python
>>> 17 / 3  # división normal devuelve un flotante
5.666666666666667
>>> 17 // 3  # división entera trunca el resultado
5
```
El operador %  devuelve el resto
```python
>>> 17 % 3  # el operador módulo devuelve el resto de la división
2
```
El operador ** eleva a la potencia
```python
>>> 5 ** 2  # 5 al cuadrado
25
>>> 2 ** 7  # 2 a la séptima potencia
128
```
Crear variables y asignar valor
El signo igual (=) se usa para asignar un valor a una variable. Después, no se muestra ningún resultado antes del siguiente prompt interactivo 
```python
>>> width = 20
>>> height = 5 * 9
>>> width * height
900
```
Si una variable no está «definida» (no se le ha asignado un valor), al intentar usarla dará un error:
```python
>>> n  # intenta usar una variable no definida
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>  
NameError: name 'n' is not defined
```
Operadores de comparación
```python
>>> 3 < 4  # menor que
True
>>> 3 > 4  # mayor que
False
>>> 3 == 4  # igual a
False
>>> 3 != 4  # diferente de
True

>>> n = 17
>>> n % 2  # el resto de la división por 2
1
>>> n % 2 == 0  # ¿es n par?
False
>>> n % 2 == 1  # ¿es n impar?
True
```
En el modo interactivo, la última expresión impresa se asigna a la variable _. Esto significa que cuando se está utilizando Python como calculadora, es más fácil seguir calculando, por ejemplo:
```python
>>> tax = 12.5 / 100
>>> price = 100.50
>>> price * tax
12.5625
>>> price + _  # añade el impuesto al precio
113.0625
>>> round(_, 2)  # redondea a 2 decimales
113.06
```
Esta variable debe ser tratada como de sólo lectura por el usuario. No le asignes explícitamente un valor; crearás una variable local independiente con el mismo nombre enmascarando la variable con el comportamiento mágico.
Además de `int` y `float`, Python admite otros tipos de números, como `Decimal` y `Fraction`. Python también tiene soporte incorporado para `complex` números complejos, y usa el sufijo j o J para indicar la parte imaginaria (por ejemplo, 3+5j).

2. **Texto**
Python puede manipular texto (representado por el tipo `str`, conocido como «cadenas de caracteres») al igual que números. Esto incluye caracteres «!», palabras «conejo», nombres «París», oraciones «¡te cubre las espaldas! », etc. «¡Genial! :)». Se pueden encerrar en comillas simples ('...') o comillas dobles ("...") con el mismo resultado
```python
>>> 'conejo'  # comillas simples
'conejo'
>>> "¡El conejo de París te cubre las espaldas! ¡Genial!"  # Comillas dobles
'¡El conejo de París te cubre las espaldas! ¡Genial!'

'1975'  # Los dígitos y números entre comillas también son cadenas
'1975'
```
Para citar una cita, debemos «escapar» la cita precediéndola con \. Alternativamente, podemos usar el otro tipo de comillas:
```python
>>> 'doesn\'t'  # usa la barra invertida para escapar la comilla simple
"doesn't"
>>> "doesn't"  # o usa comillas dobles en su lugar
"doesn't"
>>> '"Yes," he said.'
'"Yes," he said.'
>>> "\"Yes,\" he said."
'"Yes," he said.'
>>> '"Isn\'t," she said.'
'"Isn\'t," she said.'   
```
En el intérprete de Python, la definición de cadena y la cadena de salida pueden verse diferentes. La función print() produce una salida más legible, omitiendo las comillas de encuadre e imprimiendo caracteres escapados y especiales:
```python
>>> s = 'First line.\nSecond line.'  # \n significa nueva línea
>>> s  # muestra la representación «oficial»
'First line.\nSecond line.'
>>> print(s)  # muestra la cadena en forma legible
First line.
Second line.
```
Las cadenas pueden ser concatenadas (unidas) con el operador +, y repetidas con *:
```python
>>> 'Hola' + 'Mundo'
'HolaMundo'
>>> 'Hola ' + 'Mundo'
'Hola Mundo'
>>> 'Hola ' * 3
'Hola Hola Hola '
>>> 'Hola ' * 3 + '!'
'Hola Hola Hola !'
>>> 'Hola ' * (3 + 1)
'Hola Hola Hola Hola '
>>> 'Hola ' * 3.0
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: can't multiply sequence by non-int of type 'float'
```
Dos o más cadenas literales (es decir, las encerradas entre comillas) una al lado de la otra se concatenan automáticamente.

```python
>>> 'Hola' 'Mundo'
'HolaMundo'
>>> 'Hola'     'Mundo'
'HolaMundo'
>>> ('Hola'
... 'Mundo')
'HolaMundo'
```
Esta característica es particularmente útil cuando quieres dividir cadenas largas
```python
>>> text = ('Este es un texto muy largo y no quiero '
... 'escribirlo todo en una sola línea')
>>> text
'Este es un texto muy largo y no quiero escribirlo todo en una sola línea'
>>> print(text)
Este es un texto muy largo y no quiero escribirlo todo en una sola línea
```
Esto solo funciona con dos literales, no con variables ni expresiones:
```python
>>> prefix = 'Hola'
>>> prefix 'Mundo'
  File "<stdin>", line 1
    prefix 'Mundo'
           ^
SyntaxError: invalid syntax
>>> (prefix + ' ') 'Mundo'
  File "<stdin>", line 1
    (prefix + ' ') 'Mundo'
                   ^ 
SyntaxError: invalid syntax
```
Si quieres concatenar variables o una variable y un literal, usa +:
```python
>>> prefix + ' ' + 'Mundo'
'Hola Mundo'
>>> (prefix + ' ') + 'Mundo'
'Hola Mundo'
```
Las cadenas de texto se pueden indexar (subíndices), el primer carácter de la cadena tiene el índice 0. No hay un tipo de dato diferente para los caracteres; un carácter es simplemente una cadena de longitud uno:
```python
>>> word = 'Python'
>>> word[0]  # primer carácter
'P'
>>> word[5]  # sexto carácter
'n'
```
Los índices también pueden ser números negativos, para empezar a contar desde la derecha:
```python
>>> word[-1]  # último carácter
'n'
>>> word[-2]  # penúltimo carácter
'o'
>>> word[-6]  # primer carácter
'P'
```
Los índices fuera del rango válido generan un error:
```python
>>> word[6]  # error, el índice está fuera del rango
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
IndexError: string index out of range
>>> word[-7]  # error, el índice está fuera del rango
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
IndexError: string index out of range
```
Nótese que -0 es lo mismo que 0, los índice negativos comienzan desde -1.

Además de los índices, las rebanadas (slicing) también están soportadas. Mientras que la indexación se utiliza para obtener caracteres individuales, rebanar te permite obtener una subcadena:
```python
>>> word[0:2]  # caracteres desde el índice 0 hasta (pero sin incluir) el 2
'Py'
>>> word[2:5]  # caracteres desde el índice 2 hasta (pero sin incluir) el 5
'tho'
```
Los índices de las rebanadas tienen valores por defecto útiles; el valor por defecto para el primer índice es cero, el valor por defecto para el segundo índice es la longitud de la cadena a rebanar.
```python
>>> word[:2]   # los dos primeros caracteres
'Py'
>>> word[4:]   # desde el quinto carácter hasta el final
'on'
>>> word[-2:]  # los dos últimos caracteres
'on'
>>> word[:-2]  # todos menos los dos últimos caracteres
'Pyth'
>>> word[:]    # una copia de toda la cadena
'Python'
```
Resumiendo:
El primer índice es inclusivo, el segundo no. Si el primer índice es omitido, se asume que es 0; si el segundo índice es omitido, se asume que es la longitud de la cadena (es decir, hasta el final de la cadena). Si ambos índices son omitidos, se obtiene una copia de toda la cadena.

Ten en cuenta que los índices negativos pueden ser usados en las rebanadas:
```python
>>> word[-4:-2]  # los dos caracteres antes de los dos últimos
'th'
>>> word[-2:]    # los dos últimos caracteres
'on'
'on'
```
Las rebanadas pueden tener un tercer índice, llamado paso (step), que especifica el incremento entre cada índice para la rebanada:
```python
>>> word[::2]  # toma cada segundo carácter
'Pto' 
>>> word[1::2]  # toma cada segundo carácter, empezando desde el segundo
'yhn'
>>> word[::-1]  # toma todos los caracteres, pero en orden inverso
'nohtyP'
```
El paso puede ser negativo, lo que significa que la rebanada se hace de derecha a izquierda:
```python
>>> word[::-2]  # toma cada segundo carácter, pero en orden inverso
'nhy'
>>> word[5:1:-1]  # rebanada desde el índice 5 hasta (pero sin incluir) el 1, en orden inverso
'noht'
>>> word[5:1:-2]  # rebanada desde el índice 5 hasta (pero sin incluir) el 1, tomando cada segundo carácter
'nt'
>>> word[1:5:-1]  # no hay caracteres en esta rebanada
''
>>> word[5:1]  # no hay caracteres en esta rebanada
''
```
Una forma de recordar cómo funcionan las rebanadas es pensar que los índices apuntan entre caracteres, con el borde izquierdo del primer carácter numerado 0. Luego, el punto derecho del último carácter de una cadena de n caracteres tiene un índice n, por ejemplo
```python
 +---+---+---+---+---+---+
 | P | y | t | h | o | n |
 +---+---+---+---+---+---+
 0   1   2   3   4   5   6
   -6  -5  -4  -3  -2  -1
```
La primera fila de números da la posición de los índices 0…6 en la cadena; La segunda fila da los correspondientes indices negativos. La rebanada desde i hasta j consta de todos los caracteres entre los bordes etiquetados i y j, respectivamente.

Para índices no negativos, la longitud de la rebanada es la diferencia de los índices, si ambos están dentro de los límites. Por ejemplo, la longitud de word[1:3] es 2.
```python
>>> len(word[1:3])
2
>>> len(word[1:100])  # el segundo índice está fuera del rango
5
>>> len(word[1:1])  # los índices son iguales
0
>>> len(word[3:1])  # el primer índice es mayor que el segundo
0
```
Si el paso es n, entonces se toman cada n-ésimo carácter. Por ejemplo, la longitud de word[1:5:2] es 2:
```python
>>> len(word[1:5:2])
2
>>> word[1:5:2]
'yt'
>>> len(word[::3])
2
>>> word[::3]
'Ph'
>>> len(word[1::3])
2
>>> word[1::3]
'yo'
>>> len(word[::-1])
6
>>> word[::-1]
'nohtyP'
>>> len(word[::-2])
3
>>> word[::-2]
'nyh'
>>> len(word[5:1:-1])
4
>>> word[5:1:-1]
'noht'
>>> len(word[5:1:-2])
2
>>> word[5:1:-2]
'nt'
>>> len(word[1:5:-1])  # no hay caracteres en esta rebanada
0
>>> word[1:5:-1]
''
>>> len(word[5:1])  # no hay caracteres en esta rebanada
0
>>> word[5:1]
''
```
Las cadenas son inmutables, lo que significa que no pueden ser cambiadas después de ser creadas. Por ejemplo, la asignación de un carácter individual en una cadena produce un error:

```python
>>> word[0] = 'J'
Traceback (most recent call last):
  File "<stdin>", line 1, in <module> 
TypeError: 'str' object does not support item assignment
```


