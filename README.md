Project Description
This project demonstrates polymorphism in Java by creating an interface Shape3DInterface for 3D shapes. Three classes (Sphere, Cylinder, and Cube) implement this interface, each defining methods to calculate the surface area and volume of their respective shapes. The program generates random objects of these classes, calculates their properties, and displays the results.

Polymorphism Explanation
Polymorphism in this task is achieved through the Shape3DInterface. Each class (Sphere, Cylinder, and Cube) implements the interface, overriding the surfaceArea() and volume() methods. The program uses a list of Shape3DInterface references to store objects of different shapes. At runtime, the appropriate method implementation is invoked based on the actual object type (Sphere, Cylinder, or Cube), showcasing runtime polymorphism.


