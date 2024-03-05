# Figuras geométricas 

Este ejercicicio ayuda a prácticar conceptos relacionados con
herencia y polimorfismo en C++

## Objetivos de aprendizaje
* Diseñar un diagrama UML considerando relaciones de herencia
* Implementar relaciones de herencia
* Implementar comportamientos polimórficos 

Puede ver un ejemplo (realizado en clase) de implementación de herencia en C++ con polimorfismo en:
https://github.com/300CIS017-Object-Oriented-Programming/HerenciaPOO

## Requerimientos funcionales
Se pide construir un programa para manipular Figuras geométricas. Existen tres tipos específicos de figuras geométricas: circulo, cuadrado y triángulo equilátero.
Para cada figura geométrica el programa debería permitir: 
1. Dibujar una representación de la figura geométrica en pantalla ( puede hacerlo por ejemplo usando *. Puede simplemente imprimir una cadena con la figura correcta)
2. Calcular el área de la figura geométrica
3. Calcular el perímetro de la figura geométrica

Su programa debería permitir
* Agregar figuras geométricas al programa de cualquier tipo disponible
* Dibujar todas las figuras geométricas disponibles 
* Mostrar el área de todas las figuras geométricas adicionadas
* Mostrar el perímetro de todas las figuras geométricas adicionadas+
* Sumar el área de todas las figuras geométricas adicionadas al programa.

Además debería
* Incorporar un nuevo tipo de figura geométrica
* Permitir que la figura geométrica se pueda dibujar en consola utilizando algún color(usted define el color)

## Requerimientos no funcionales
* Use relaciones de herencia entre clases
* Use sobreescritura de métodos entre clases para lograr polimorfismo para los métodos que permiten *mostrar la figura*, *calcular el área* y el *perímetro*. Recuerde que para lograr este comportamiento los métodos se deben llamar igual en la clase padre y en las clases hijas.

> Recuerde agregar un gitignore a su repositorio y hacer las verificaciones necesarias para garantizar la calidad de su código

## Entregables
* Diagrama UML -> PNG y Link 
* Código fuente subido al github classroom
Equipos de dos personas. 
