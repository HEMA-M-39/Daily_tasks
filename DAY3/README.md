# Object-Oriented Programming (OOP) Learning Reflection  

## Task 1: Class Creation (New Class - Vehicle Class)  

### What I Learned:  
I learned how to define a class in Python and create objects from it. Implementing methods like `start_engine()` and `stop_engine()` helped me understand how objects interact with class attributes and behaviors.  

### Difficulties Faced:  
Initially, structuring the class correctly was challenging. I had to ensure that each method was properly defined and used `self` correctly to reference instance attributes. Forgetting `self` in method definitions caused errors, which I had to debug.  

### Final Thought:  
Understanding how to create and use classes helped me realize the importance of object-oriented design in making code more modular and organized.  

---

## Task 2: Constructor Usage (Car Class)  

### What I Learned:  
I explored how constructors (`__init__`) automatically initialize object attributes when an instance is created. This allowed me to pass values dynamically instead of setting them manually.  

### Difficulties Faced:  
I initially forgot to use `self.attribute = value` inside the constructor, leading to issues when accessing attributes later. Differentiating between instance attributes (specific to objects) and class attributes (shared across objects) took some effort to understand.  

### Final Thought:  
Constructors improve the efficiency and flexibility of object creation, making code more dynamic and reusable.  

---

## Task 3: Inheritance (ElectricCar Class)  

### What I Learned:  
Inheritance allows a new class (`ElectricCar`) to reuse attributes and methods from a parent class (`Car`). This reduced code duplication while allowing modifications specific to electric cars.  

### Difficulties Faced:  
I initially forgot to call the parent constructor using `super().__init__()`, causing errors when trying to access inherited attributes. Understanding how method overriding works was also a learning curve.  

### Final Thought:  
Inheritance simplifies code by creating a logical hierarchy, allowing reusability while keeping the structure clear and maintainable.  

---

## Task 4: Multiple Inheritance (HybridVehicle Class)  

### What I Learned:  
I learned how multiple inheritance enables a class (`HybridVehicle`) to inherit from both `ElectricCar` and `FuelCar`, combining attributes and behaviors from multiple sources.  

### Difficulties Faced:  
Handling method conflicts was tricky, especially when both parent classes had methods with the same name. Understanding method resolution order (MRO) and using `super()` correctly helped resolve conflicts.  

### Final Thought:  
Multiple inheritance is a powerful concept but requires careful structuring to avoid ambiguity and unexpected behavior in method execution.  

---

## Task 5: Encapsulation (BankAccount Class)  

### What I Learned:  
Encapsulation allows controlling access to object attributes using access modifiers. I implemented private attributes (`__balance`) and used getter and setter methods to enforce controlled access.  

### Difficulties Faced:  
Initially, I tried accessing private attributes directly, which raised errors. Implementing getter and setter methods helped resolve this, but understanding when to use protected (`_attribute`) vs private (`__attribute`) attributes took time.  

### Final Thought:  
Encapsulation enhances data security and prevents unintended modifications, making code more reliable and maintainable.  

---

## Task 6: Polymorphism (Shape Class)  

### What I Learned:  
Polymorphism allows different classes (`Circle`, `Rectangle`, `Triangle`) to share a common method (`area()`) while implementing it differently. This made it easier to handle multiple object types under a single interface.  

### Difficulties Faced:  
I initially defined the `area()` method in the base class but forgot to raise `NotImplementedError`, causing confusion when calling it directly. Ensuring each subclass properly implemented its own version of `area()` took practice.  

### Final Thought:  
Polymorphism makes code more flexible by allowing different objects to be used interchangeably while maintaining their unique behaviors.  

---

## Overall Reflection on OOP Learning  

### What I Gained:  
- A deeper understanding of class creation and object interactions.  
- How constructors simplify attribute initialization dynamically.  
- The benefits of inheritance for code reusability.  
- How multiple inheritance works and its challenges.  
- Encapsulation for protecting and managing data access.  
- Polymorphism for writing flexible and scalable code.  

### Challenges Faced:  
- Structuring classes correctly and debugging method errors.  
- Applying inheritance while ensuring proper method resolution.  
- Managing access control with private and protected attributes.  
- Implementing polymorphism correctly across multiple subclasses.  

### Final Thought:  
Object-Oriented Programming provides a structured approach to software development, making applications more maintainable, reusable, and scalable.
