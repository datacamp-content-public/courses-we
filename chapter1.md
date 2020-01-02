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

## Insert exercise title here

```yaml
type: NormalExercise
key: ab50e7a969
xp: 100
```

Python puede ser usado como calculadora. APuede realizar operaciones básicas y también operaciones más avanzadas como

 Exponenciación: **. Este operador eleva al número de la izquierda a la potencia derecha. Por ejemplo, 4**2 dará 16.
 
 Módulo: %. Este operador regresa el residuo de la división del número de la izquierda entre el número de la derecha. Por ejemplo, 18 % 7 es igual a 4.

El código en el script da algunos ejemplos de operaciones aritméticas.

`@instructions`
Supongamos que tienes $100, y los puedes invertir con un 10% de regreso de inversión por año. Después de un año obtienes 100×1.1=110 pesos, después de dos años tendrás 100×1.1×1.1=121 pesos. Escribe código para determinar cuanto dinero tendrás después de 7 años e imprime el resultado.

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
