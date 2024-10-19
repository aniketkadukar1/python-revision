# Python OOP Quick Revision Notes

## 1. Four Pillars of OOP:
- **Encapsulation**: Bundling of data (attributes) and methods (functions) that operate on the data into a single unit or class. Access to variables and methods can be controlled using access modifiers (`private`, `public`).
- **Abstraction**: Hiding complex details and showing only the essentials. Achieved through abstract classes and methods.
- **Inheritance**: Mechanism for a new class to derive properties and behavior from an existing class. Promotes code reusability.
- **Polymorphism**: Ability of different classes to be treated as instances of the same class through method overriding and overloading.

## 2. Key Concepts:

### 2.1 Classes and Objects:
- **Class**: A blueprint for creating objects. It defines properties (attributes) and behaviors (methods).
- **Object**: An instance of a class.

```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

car1 = Car("Toyota", "Camry")
```
