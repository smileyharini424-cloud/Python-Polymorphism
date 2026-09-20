# Python Polymorphism

## Explanation

Polymorphism means "many forms". In Python, different classes can define methods with the same name but provide different implementations.

This program demonstrates method overriding using `Dog` and `Cat` classes.

## Problem Statement

Write a Python program demonstrating polymorphism where different animal classes implement the same `sound()` method differently.

## Features

* Demonstrates polymorphism
* Demonstrates method overriding
* Uses multiple classes
* Uses the same method name with different behavior
* Demonstrates flexible object handling

## How It Works

1. A `Dog` class defines a `sound()` method.
2. A `Cat` class also defines a `sound()` method.
3. Both methods have the same name but produce different results.
4. Objects of both classes are stored in a list.
5. A loop calls `sound()` on each object.
6. Python automatically uses the appropriate implementation.

## Technologies Used

* Python 3
* Object-Oriented Programming
* Polymorphism
* Method Overriding

## Program Flow

Start → Create Classes → Define Same Method → Create Objects → Call Method → Display Different Behaviors → End

## Sample Input

```text id="p6z3vq"
No user input required.
```

## Sample Output

```text id="k8m4xa"
Dog says: Woof!
Cat says: Meow!
```

## Key Learning

* Polymorphism means one interface can have multiple implementations.
* Different classes can use the same method name.
* Method overriding is a common way to achieve polymorphism.
* Python determines which method to execute based on the object.

## File Location

```text id="r2n7cs"
Python-Polymorphism/polymorphism.py
```

## Repository Structure

```text id="t5x9mp"
Python-Polymorphism/
│
├── polymorphism.py
└── README.md
```

## Author

V.Harini
