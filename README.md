# Advanced Polymorphism in Java

## Assignment Overview

This assignment aims to deepen your understanding of polymorphism in Java by implementing a complex class hierarchy and demonstrating both compile-time and runtime polymorphism.

## Problem Statement

You are required to create a simulation of a simple drawing application. The application should be able to handle different shapes (Circle, Rectangle, Triangle) and perform operations like drawing the shape and calculating its area. You will use both method overloading and method overriding to achieve polymorphism.

## Requirements

1. **Create an interface `Drawable` with a method `void draw()`.**
2. **Create an abstract class `Shape` that implements `Drawable` and has the following:**
   - Protected attributes `int x` and `int y` for the position of the shape.
   - A constructor to initialize `x` and `y`.
   - An abstract method `double getArea()`.
3. **Create the following classes that extend `Shape`:**
   - `Circle` with an additional attribute `double radius`.
   - `Rectangle` with additional attributes `double width` and `double height`.
   - `Triangle` with additional attributes `double base` and `double height`.
4. **Implement the `draw()` and `getArea()` methods in each of the above classes.**
5. **Create a class `DrawingProgram` with a `main` method that:**
   - Creates instances of `Circle`, `Rectangle`, and `Triangle`.
   - Stores them in an array of type `Shape`.
   - Iterates through the array and calls the `draw()` and `getArea()` methods on each shape.
6. **Demonstrate method overloading by creating a class `ShapePrinter` with overloaded methods `printShapeInfo(Shape shape)`, `printShapeInfo(Circle circle)`, and `printShapeInfo(Rectangle rectangle)`.**

## Expected Output

The program should output the drawing and area calculation for each shape. The output should look something like this:

```
Drawing a circle at (10, 20) with radius 5.0
Area of the circle: 78.54

Drawing a rectangle at (30, 40) with width 10.0 and height 20.0
Area of the rectangle: 200.0

Drawing a triangle at (50, 60) with base 15.0 and height 25.0
Area of the triangle: 187.5
```

## Instructions

1. **Clone the classroom repository:**


2. **Implement the `Drawable` interface:**


3. **Implement the `Shape` abstract class:**


4. **Implement the `Circle`, `Rectangle`, and `Triangle` classes:**
 

5. **Implement the `DrawingProgram` class:**


6. **Implement the `ShapePrinter` class:**
