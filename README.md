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
3. [OOP Interview One-Line Definitions](#3-oop-interview-one-line-definitions) 
4. [OOPs Concepts](#4-oop-concept)

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

## 3. OOP Interview One-Line Definitions

    | Concept       | Definition                                           |
    | ------------- | ---------------------------------------------------- |
    | OOP           | Programming using objects and classes                |
    | Class         | Blueprint for creating objects                       |
    | Object        | Instance of a class                                  |
    | Property      | Variable inside a class                              |
    | Method        | Function inside a class                              |
    | Constructor   | Method called automatically when object is created   |
    | Encapsulation | Hiding data and controlling access                   |
    | Inheritance   | Acquiring properties and methods from another class  |
    | Polymorphism  | Same method behaves differently                      |
    | Abstraction   | Hiding implementation details and showing essentials |
