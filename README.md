---
# 📘 DOCUMENTACIÓN DE EJERCICIOS
## 🧠 Tema: Lógica de Programación Básica
## 📌 1. Introducción

La lógica de programación es la base para aprender a programar.
Nos ayuda a resolver problemas paso a paso usando instrucciones claras y ordenadas.

En esta documentación se presentan ejercicios básicos para practicar estructuras simples como variables, condicionales y ciclos.

---

## 🎯 2. Objetivos

* Comprender cómo resolver problemas de forma lógica.
* Practicar el uso de variables.
* Aplicar estructuras condicionales (if).
* Utilizar ciclos repetitivos (for y while).

---

# 📝 3. Ejercicios

---

## 🔹 Ejercicio 1: Suma de dos números

### 📌 Enunciado:

Crear un programa que pida dos números y muestre la suma.

### 💻 Ejemplo en Python:

```python
num1 = int(input("Ingrese el primer número: "))
num2 = int(input("Ingrese el segundo número: "))

suma = num1 + num2

print("La suma es:", suma)
```

### ✅ Explicación:

* Se guardan los números en variables.
* Se suman.
* Se muestra el resultado.

---

## 🔹 Ejercicio 2: Número par o impar

### 📌 Enunciado:

Determinar si un número es par o impar.

### 💻 Código:

```python
numero = int(input("Ingrese un número: "))

if numero % 2 == 0:
    print("Es un número par")
else:
    print("Es un número impar")
```

### ✅ Explicación:

* El operador `%` calcula el residuo.
* Si el residuo es 0, es par.
* Si no, es impar.

---

## 🔹 Ejercicio 3: Tabla de multiplicar

### 📌 Enunciado:

Mostrar la tabla de multiplicar de un número.

### 💻 Código:

```python
numero = int(input("Ingrese un número: "))

for i in range(1, 11):
    print(numero, "x", i, "=", numero * i)
```

### ✅ Explicación:

* Se usa un ciclo `for`.
* Se repite del 1 al 10.
* Se imprime la multiplicación.

---

## 🔹 Ejercicio 4: Contar del 1 al 10 con while

### 💻 Código:

```python
contador = 1

while contador <= 10:
    print(contador)
    contador += 1
```

### ✅ Explicación:

* El ciclo se ejecuta mientras la condición sea verdadera.
* Se aumenta el contador en cada repetición.

---

# 📌 4. Conclusión

Estos ejercicios ayudan a fortalecer la lógica de programación y comprender cómo funcionan las estructuras básicas en Python.
La práctica constante permite mejorar la capacidad de resolver problemas de forma organizada y eficiente.

-