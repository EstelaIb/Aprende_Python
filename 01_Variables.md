# Variables

El espacio en memoria que nos permite guardar datos, se podría decir que es como una caja.

Cuando declaramos variables debes tener cierto aspectos en cuenta al `nombrarlas`:

**- No debe iniciar con números**

**- Debe empezar con una letra o guión bajo**

**- Solo puede contener caracteres alfanuméricos, números y guiones bajos**

### Ejemplo de nombres validos ✅

```
  _contador
  numero_21
  Primer_nombre
  primer_apellido
```

### Ejemplo de nombres **NO** validos ❌

```
  21__
  P@_nombre
  apellido-3
```

<hr>

<h2>Notas que recordar👀</h2>

<div>
    <strong>- Recuerda usar variables mnemotécnicas, es decir que sean cortas, faciles de asociar y recordar.</strong>
</div>
<br>
<div>
    <strong>- Por convención en Python se usa <mark>Snake_Case</mark>, se usa el guión bajo después de cada palabra para el nombre de la variable que contenga más de una palabra</strong>
</div>
<hr>

## Declaración de variables

Es cuando se le asigna o un valor a una variable con ayuda del operador de asignación  (`=`). Hagamos de cuenta que tenemos una cajita vacía (variable) y ponemos algo dentro (dato) con ayuda de nuestras manos (=).

```
  Primer_nombre = "Perez"
  contador = 0
  verdadero = False
```

<hr>

## Declaracion de variables en una sola línea
Se asignarán los valores en el orden correspondiente. 
```
nombre, apellido, edad, genero = "Amelia", "Perez", 21, "Femenino"
```

<h2>Visualizar variables</h2>
Para visualizar el valor de las variables haremos uso de una de las tantas funciones incorporadas, `print()`.

```
print("Nombre: ", nombre)
print("Apellido: ", apellido)
print("Edad: ", edad)
print("Genero: ", genero)
```

<hr>

### En la siguiente lección veremos las funciones incorporadas de Python. 
<hr>
