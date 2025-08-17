---
**3. Archivo: `content/posts/funciones-python.md`**
```markdown
---
title: "Ejemplos de Funciones en Python"
date: 2025-08-17T22:01:00Z
draft: false
description: "Ejemplos básicos de cómo definir y usar funciones en Python."
---

Una función en Python es un bloque de código reutilizable que realiza una tarea específica. Se definen con la palabra clave `def`.

## Función Simple sin Parámetros
Esta función simplemente imprime un saludo.
```python
def saludar():
  """Esta función imprime un saludo en la consola."""
  print("Hola, bienvenido a Python.")

# Para llamarla, simplemente usamos su nombre:
saludar()
Función con Parámetros
Podemos pasarle datos a una función a través de parámetros.
code
Python
def sumar(a, b):
  """Esta función recibe dos números y devuelve su suma."""
  resultado = a + b
  return resultado

# La llamamos con dos argumentos
suma = sumar(5, 3)
print(f"El resultado de la suma es: {suma}") # Salida: El resultado de la suma es: 8
Función con Parámetros por Defecto
Podemos asignar valores por defecto a los parámetros. Si no se proporciona un valor al llamar a la función, usará el valor por defecto.
code
Python
def potencia(base, exponente=2):
  """Calcula la potencia de un número. Si no se especifica el exponente, se asume 2."""
  return base ** exponente

# Llamadas a la función
cuadrado = potencia(4) # Usará exponente=2 por defecto
cubo = potencia(4, 3) # Le pasamos un valor para el exponente

print(f"4 al cuadrado es: {cuadrado}") # Salida: 4 al cuadrado es: 16
print(f"4 al cubo es: {cubo}")     # Salida: 4 al cubo es: 64