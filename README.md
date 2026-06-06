# OOP Interview Questions & Answers
> Please click⭐ If this repository helps you, please give it a star. Follow me on linkedIn [Abhishek Shrivastav](https://www.linkedin.com/in/abhi2249/) for technical updates.

---

## Why This Repository?

Most developers know the definitions of OOP concepts but struggle to explain them during interviews.

This repository focuses on:

✅ Simple definitions

✅ Real-world examples

✅ Interview-oriented answers

✅ Beginner to advanced questions

✅ Frequently asked questions from top companies

The goal is to help developers confidently answer OOP questions in technical interviews.

---

## Questions

1. [What is OOP?](#1-what-is-oop)
2. [Four Pillars of OOP](#2-four-pillars-of-oop)
3. [OOPs Concepts](#3-oop-concept)
4. [OOP Concepts Interview One-Line Definitions](#4-oop-concept-interview-one-line-definitions) 

---

## 1. What is OOP?
Object-Oriented Programming (OOP) is a programming style that organizes code using objects, which contain data (properties) and behavior (methods).

## 2. Four Pillars of OOP
### a)  Abstraction
Data abstraction refers to the act of representing essential features without including the background detail or explanation.

**Example:**
We drive a car without thinking that how car subsystems is working.
```php
abstract class Vehicle
{
    abstract public function start();
}

class Car extends Vehicle
{
    public function start()
    {
        echo "Car Started";
    }
}
```

### b) Encapsulation
Wrapping data and methods into a single unit and controlling access.
```php
class BankAccount
{
    private $balance = 1000;

    public function getBalance()
    {
        return $this->balance;
    }
}

```
    
### c) Inheritance
Inheritance is the process by which one object acquires the properties of another class
```php
class Animal
{
    public function eat()
    {
        echo "Eating";
    }
}

class Dog extends Animal
{
}
```

### d) Polymorphism
Polymorphism means ability to take more the one form
```php
class Animal
{
    public function sound()
    {
        echo "Animal Sound";
    }
}

class Dog extends Animal
{
    public function sound()
    {
        echo "Bark";
    }
}
```

## 3. OOP Concept
There are 8 type of oop concept:
1. Object
2. Class
3. Encapsultion
4. Abstraction
5. Polymorphism
6. Inheritance
7. Message Passing
8. Dynamic Binding

### 4. OOP Concept Interview One Line Definitions
| Concept           | Definition                                                            |
| ----------------- | --------------------------------------------------------------------- |
| Object            | Instance of a class                                                   |
| Class             | Blueprint for creating objects                                        |
| Encapsulation     | Hiding data and controlling access                                    |
| Abstraction       | Hiding implementation details and showing essentials                  |
| Polymorphism      | Same method behaves differently                                       |
| Inheritance       | Acquiring properties and methods from another class                   |
| Message Passing   | Communication between objects by calling methods and exchanging data  |
| Dynamic Binding   | Deciding which method to execute at runtime instead of compile time   |
