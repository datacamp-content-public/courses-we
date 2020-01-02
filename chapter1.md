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
# Ejemplo 1
print(5 / 8)

# Imprime la suma de 7 con 10
print (7+10)
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
Success!!
Ex().check_function('5/8').check_args('a').has_equal_value()

Ex().check_function('7+10').check_args('a').has_equal_value()
```
