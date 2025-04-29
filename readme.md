# Figuras geométricas: Aplicación de Herencia y Polimorfismo en C++

Este ejercicio tiene como finalidad afianzar los conceptos de **herencia** y **polimorfismo** en el lenguaje de programación C++, a través del diseño e implementación de un sistema orientado a objetos para la representación y manipulación de figuras geométricas. La actividad pone énfasis en el diseño estructurado mediante clases, la reutilización de código y el comportamiento dinámico de los objetos.

## 🎯 Objetivos de aprendizaje

Al finalizar este ejercicio, el estudiante será capaz de:

- Diseñar un modelo orientado a objetos que utilice relaciones de herencia entre clases, representado mediante un diagrama UML.
- Implementar una jerarquía de clases en C++ que haga uso de herencia.
- Aplicar el principio de polimorfismo a través de la sobrescritura de métodos en clases derivadas.

Se recomienda revisar el siguiente ejemplo como referencia técnica: 👉 [Ejemplo de herencia y polimorfismo en C++](https://github.com/300CIS017-Object-Oriented-Programming/HerenciaPOO)

## ✅ Requerimientos funcionales

El sistema debe permitir representar y operar sobre distintas figuras geométricas. Inicialmente se trabajará con tres figuras: **círculo**, **cuadrado** y **triángulo equilátero**. Para cada una, se deberá implementar la siguiente funcionalidad:

- Generar una representación gráfica simple en consola (por ejemplo, utilizando caracteres como el asterisco `*`).
- Calcular y mostrar el área de la figura.
- Calcular y mostrar el perímetro de la figura.

Además, el sistema deberá permitir:

- Registrar múltiples figuras geométricas de distintos tipos.
- Mostrar en consola la representación de todas las figuras almacenadas.
- Presentar el área y el perímetro de cada figura agregada.
- Calcular y mostrar el área total de todas las figuras registradas.

### Requerimientos adicionales

- Incorporar al menos una nueva figura geométrica adicional, no incluida en las iniciales.
- Implementar un mecanismo para colorear la representación de las figuras en la consola (por ejemplo, mediante códigos ANSI).
- Diseñar una clase abstracta que defina el método `pintar()`, el cual deberá ser implementado obligatoriamente por todas las figuras para establecer su color de impresión.

## ⚙️ Requerimientos no funcionales

- La solución debe implementar relaciones de herencia de manera adecuada y explícita.
- Se debe aplicar polimorfismo mediante la sobrescritura de métodos, tales como `dibujar()`, `calcularArea()` y `calcularPerimetro()`, manteniendo las mismas firmas en la clase base y en las derivadas.
- Se recomienda incorporar un archivo `.gitignore` en el repositorio para excluir del repo carpetas de archivos de compilación como la carpeta cmake-build-debug y la .idea.
- Organice el proyecto en carpetas, en el ejemplo puede ver una estructura de directorios que podría seguir.

## 📦 Entregables

- Diagrama UML desarrollado con sintaxis **Mermaid**.
- Código fuente documentado y subido al repositorio de **GitHub Classroom** correspondiente.
- El trabajo debe ser realizado en equipos de **tres (3) estudiantes**. Se evaluará el trabajo en clase más que el producto final.


## Contenido de apoyo

### 1. Herencia en Programación Orientada a Objetos
✅ ¿Qué es la herencia?
La herencia es una característica fundamental de la programación orientada a objetos que permite que una clase nueva (llamada clase derivada o subclase) herede atributos y métodos de otra clase existente (llamada clase base o superclase).

Esto facilita:

* 🔁 Reutilización de código (no repetir lo común entre clases).
* 🧩 Especialización de comportamientos (las subclases pueden modificar o extender funcionalidades).
* 🏛️ Organización jerárquica del diseño del software.

#### 🌍 Analogía del mundo real
* 🔹 Ejemplo 1: Empleados
Clase base: Empleado (tiene nombre, salario, trabajar()).

Clases derivadas: Ingeniero, Diseñador, Gerente.
Todos son empleados, pero sus tareas (trabajar()) pueden variar. Y todos comparten datos comunes como el nombre y el salario.
