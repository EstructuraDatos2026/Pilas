# Pilas

## Integrantes

- Jonathan Benancio Aguilar Hernández
- Angel Nahum Camarillo Solano
- Luis Fernando Campuzano Hernández
- Pedro García Mata
- Jose Alejandro Olvera Lugo

## Ronda 1: El estacionamiento (10 min)

**Objetivo:** Comprender las operaciones `push`, `pop` y por qué solo se puede acceder al elemento que está en el tope de la pila.

### 1. Entrada de los autos

Los alumnos representan autos que entran al callejón de uno en uno (`push`). El último en entrar queda hasta adelante.

### 2. Salida del auto azul

El docente solicita: **"¡Tiene que salir el auto azul!"**

Si el auto azul está al fondo, todos los autos que están delante deben salir (`pop`) y esperar en una calle lateral, que representa una segunda pila.

Después, el auto azul sale y los demás autos regresan en orden inverso al que salieron.

### 3. Primera imagen de la pila

![Primera imagen de la pila](imagenes/imagen1.png)

### 4. Segunda imagen de la pila

![Segunda imagen de la pila](imagenes/imagen2.png)

### 5. Tercera imagen de la pila

![Tercera imagen de la pila](imagenes/imagen3.png)

---

## Pregunta de cierre

**¿Por qué no pudo salir el auto del fondo directamente?**

Porque la pila funciona con el principio LIFO (*Last In, First Out*), que significa «el último en entrar es el primero en salir». Los demás autos bloqueaban el paso del auto del fondo, por lo que tuvieron que salir primero y colocarse en otra pila. Después de que salió el auto azul, los demás regresaron en orden inverso al que salieron.
