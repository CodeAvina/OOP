Readme.md

#Object Oriented Programming(OOP)

The goal of object-oriented programming (OOP) is to create clear code.
Classes and objects are at the heart of OOP.

##Sample code

```
class Employee:
    def __init__(self, name, age, salary, position, department, marital_status):
        self.name = name
        self.age = age
        self.salary = salary
        self.position = position
        self.department = department
        self.marital_status = marital_status
        
    def add_age(self):
        self.age += 1
        
    def get_age(self):
        return "Age is {}".format(self.age)
```

## Pillars of OOP

-Encapsulation
-Inheritance
-Polymorphism
-Abstraction
