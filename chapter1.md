---
title: 'Bienvenido a Python!'
description: 'Todo lo que necesitas saber para empezar.'
---

## La interfaz de Python

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

En el lado derecho se encuentra el script del archivo de Python. Su terminación **(.py)** indica que es un archivo que Python puede correr.

Si se oprime el botón del lado derecho _Run Code_, se compila el código y se ejecuta en el "Shell" de IPython directamente abajo. Compilar significa que Python checa primero los errores de estructura o escritura del código antes de ejecutarlo.

El botón de _Submit Answer_ checa si tu respuesta es correcta o no.

Puedes oprimir el botón de _Run Code_ o _Submit Answer_ las veces que quieras.

También se puede interactuar directamente con el Shell de IPython escribiendo tu código y luego oprimiendo la tecla Enter.

Trabajar en el Shell de IPython directamente es una manera de checar si tu respuesta es correcta o no.

`@instructions`
Comenta la primer línea y corre el código.

Después comenta la segunda operación y descomenta la primera, luego corre el código.

Da _Submit_.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Ejemplo 1
print(5 / 8)

# Imprime la suma de 7 con 10
print (7+10)
```

`@solution`
```{python}
print(5 / 8)
print (7+10)
```

`@sct`
```{python}
Ex().has_printout(0)
```

---

## Python como calculadora

```yaml
type: NormalExercise
key: ab50e7a969
xp: 100
```

Python puede ser usado como calculadora. Puede realizar operaciones básicas y también operaciones más avanzadas como:

	Exponenciación: Este operador eleva al número de la izquierda a la potencia derecha. 
    Por ejemplo, 4*2 dará 16.
 
	Módulo:  Este operador regresa el residuo de la división del número de la izquierda entre el número de la 				derecha.
    Por ejemplo, 18 % 7 es igual a 4.

El código en el script da algunos ejemplos de operaciones aritméticas.

`@instructions`
Supongamos que tienes $100, y los puedes invertir con un 10% de regreso de inversión por año. Después de un año obtienes 100×1.1=110 pesos, después de dos años tendrás 100×1.1×1.1=121 pesos.

1. Escribe código para determinar cuanto dinero tendrás después de 7 años e imprime el resultado.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Suma, resta
print(5 + 5)
print(5 - 5)

# Multiplicación, división, módulo, y potencias
print(3 * 5)
print(10 / 2)
print(18 % 7)
print(4 ** 2)

# ¿Cuánto valen tus $100 después de 7 años si cada año tienes el 10% de retorno de inversión?

```

`@solution`
```{python}
print(100*1.1**7)
```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
```

---

## Asignación de variables

```yaml
type: NormalExercise
key: 8840be502a
xp: 100
```

En Python, una variable permite referirte a un valor con un nombre específico.
Para crear una variable usa el signo de `=` después de una letra o palabra. Por ejemplo,

	x = 5 

Ahora se puede manipular el valor de `x` en vez del valor de `5`.

Recuerda que `=` en Python significa asignación, no es una prueba de igualdad.

`@instructions`
- Crea una variable llamada `ahorros`con un valor de `100`.

- Imprime el valor de esta variable escribiendo `print(ahorros)` en el script.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Crea la variable ahorros
ahorros = 100 
# Imprime ahorros
print(ahorros)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Calculos con variables

```yaml
type: NormalExercise
key: 768b7b8e86
xp: 100
```

En vez de calcular con valores numéricos, puedes usar la variable asignada. Por ahora `ahorros` creada en el ejercicio anterior representa los `$100` con los que empezaste. Depende de ti crear una variable nueva que representa 1.1 y luego rehacer los calculos.

`@instructions`
1. Crea una variable `multiplicador_de_crecimiento`, igual a 1.1.
2. Crea otra variable, `resultado`, igual a la cantidad de dinero que tienes después de 7 años.
3. Imprime el valor de `resultado`.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Se crea la variable llamada "ahorros"


# Se crea una variable llamada "multiplicador_de_crecimiento"


# Calcular resultado


# Imprime el resultado

```

`@solution`
```{python}
# Se crea la variable llamada "ahorros"
ahorros = 100

# Se crea una variable llamada "multiplicador_de_crecimiento"
multiplicador_de_crecimiento = 1.1

# Calcular resultado
resultado = (ahorros*(multiplicador_de_crecimiento**7))

# Imprime el resultado
print(resultado)
```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
```

---

## Tipos de Variables

```yaml
type: NormalExercise
key: fbbf2cbedc
xp: 100
```

En el ejercicio anterior, trabajaste con dos tipos de estructuras de Python:

- `int, "integer" o entero:` un número sin una parte fraccionada.
    	"ahorros" con valor de 100, es un ejemplo de un entero.
        
- `float, o "punto flotante":`número que tiene ambas partes enteras y fracionales, separadas por un punto. 
   		"multiplicador_de_crecimiento", con valor de 1.1, es un ejemplo de un flotante.

Al lado de los tipos de información numéricos, hay otros tipos de información comunes:

 -  `str, string o "cadena de carácter"`: un tipo que representa texto. Puedes usar comillas sencillas o dobles para 			construir un "string".
 - `bool, boolean o "boleana"`: a type to represent logical values. Can only be True or False (the capitalization is 			important!).

`@instructions`
<!-- Guidelines for instructions https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->
- Crea un nuevo string, llamado `desc`, con el valor `"interes compuesto"`
- Crea un boolean, llamado `profitable`, con el valor `True`

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#Crea la variable desc


#Crea la variable profitable

```

`@solution`
```{python}
#Crea la variable desc
desc= "compound interest"

#Crea la variable profitable
profitable= True
```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
```

---

## Adivina el tipo 

```yaml
type: MultipleChoiceExercise
key: 50d0520eda
xp: 50
```

<!-- Guidelines for the question: https://instructor-support.datacamp.com/en/articles/2375523-course-multiple-choice-with-console-exercises. -->
Para encontrar el tipo de la vaibale a la que se está refiriendo podrías utilizar:  `type()`. Está función se ejecuta simplemente escribiendo la variable dentro de los paréntesis. 

	type(a) 
    
Las variables `a`, `b`, y `c ` han sido previamente creadas. 

Puedes utilizar la termianl en la derecha para descubrir cual de las siguientes opciones es correcta. 

`@possible_answers`
- [Correct answer 1] `a` es de tipo `int`, `b` es de tipo `str`, `c` es de tipo `bool`
- Wrong answer 2
- Wrong answer 3
-

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@pre_exercise_code`
```{python}
a= 194.929
b= True 
c= False
```

`@sct`
```{python}
# Check https://instructor-support.datacamp.com/en/articles/2375523-course-multiple-choice-with-console-exercises on how to write feedback messages for this exercise.
```
