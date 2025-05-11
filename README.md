# core_java

✅ **1. OOPs Concepts (Object-Oriented Programming)**
➤ **Class:**
A class is a blueprint or template that defines properties (fields) and behaviors (methods) of an object.
```ssh
class Car {
   String color;
   void drive() {
     System.out.println("Driving...");
   }
}
```

➤ **Object:**
An object is an instance of a class. It occupies memory and has state and behavior.
```ssh
Car myCar = new Car();
```

➤ **Inheritance:**
Allows one class (child) to inherit fields and methods from another class (parent).
```ssh
class Animal {
  void sound() { System.out.println("Animal Sound"); }
}
class Dog extends Animal {
  void bark() { System.out.println("Bark"); }
}
```

➤ **Polymorphism:**
Means "many forms". A method behaves differently based on the context.
 - Compile-time: Method Overloading
 - Runtime: Method Overriding

➤ **Encapsulation:**
Hides internal data using private access and exposes via public methods (getters/setters).
```ssh
class Person {
  private int age;
  public void setAge(int a) { age = a; }
  public int getAge() { return age; }
}
```

➤ **Abstraction:**
Hides complex implementation details and shows only necessary parts using abstract classes or interfaces.

<hr>

✅ **2. Data Types in Java** <br>
➤ **Primitive Types :**
int, float, char, double, byte, short, long, boolean
```ssh
int x = 10;
char c = 'A';
```

➤ **Non-Primitive Types :**
Arrays, Strings, Classes, Interfaces
```ssh
String name = "Java";
```

<hr>

✅ **3. Control Statements**  <br>
➤ **Conditional :**  if, else, switch - decision making
```ssh
if (a > b) { System.out.println("A is greater"); }
```

➤ **Loops :**  for, while, do-while - to repeat code
```ssh
for (int i = 0; i < 5; i++) {
  System.out.println(i);
}
```

➤ **Jumping :**  break, continue, return
```ssh
for (int i = 0; i < 10; i++) {
  if (i == 5) break;
}
```

<hr>

✅ **4. Access Modifiers**  <br>
Control visibility of classes and members:
```ssh
| Modifier    | Class | Package | Subclass | World |
| ----------- | ----- | ------- | -------- | ----- |
| `private`   | ✅     | ❌       | ❌        | ❌     |
| (default)   | ✅     | ✅       | ❌        | ❌     |
| `protected` | ✅     | ✅       | ✅        | ❌     |
| `public`    | ✅     | ✅       | ✅        | ✅     |
```

