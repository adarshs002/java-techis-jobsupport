# OOPs (Object-Oriented Programming System):

Object means a real-world entity such as a pen, chair, table, computer, watch, etc. Object-Oriented Programming is a methodology or paradigm to design a program using classes and objects. It simplifies software development and maintenance by providing some concepts:

* Object
* Class
* Inheritance
* Polymorphism
* Abstraction
* Encapsulation

Apart from these concepts, there are some other terms which are used in Object-Oriented design:

* Coupling
* Cohesion
* Association
* Aggregation
* Composition

The main aim of object-oriented programming is to implement real-world entities, for example, objects, classes, abstraction, inheritance, polymorphism, etc.

<img width="577" alt="Screenshot 2022-04-21 at 1 33 19 PM" src="https://user-images.githubusercontent.com/100840176/164408879-ad324538-99ef-4a43-83cd-7f3ebe10bc33.png">
 
# Classes/Objects:

* Object − Objects have states and behaviors. Example: A dog has states - color, name, breed as well as behaviors – wagging the tail, barking, eating. An object is an instance of a class.
* Class − Collection of objects is called class. It is a logical entity. A class can also be defined as a blueprint from which you can create an individual object. Class doesn't consume any space.

## Create a Class

To create a class, use the keyword class:

<img width="544" alt="Screenshot 2022-04-24 at 9 48 13 PM" src="https://user-images.githubusercontent.com/100840176/164986489-4ab49dfb-d6f6-4e9e-a48d-67104efca62a.png">

## Create an Object:

In Java, an object is created from a class. We have already created the class named Puppy, so now we can use this to create objects.

To create an object of Puppy, specify the class name, followed by the object name, and use the keyword new:

<img width="544" alt="Screenshot 2022-04-24 at 9 48 13 PM" src="https://user-images.githubusercontent.com/100840176/164985946-07863f87-73bc-4322-b6f3-e80485aa5d70.png">

Output:

<img width="499" alt="Screenshot 2022-04-24 at 9 48 56 PM" src="https://user-images.githubusercontent.com/100840176/164985976-d7003ac9-9671-4cb5-9238-950024611b60.png">

# Class Attributes:

In java, a variable within the class is referred to as a class attribute and the class attributes are also known as fields. Let’s understand the concept of a class attribute with the help of an example. Let’s say we have a class named Employee as shown in the below-given snippet:


<img width="622" alt="Screenshot 2022-04-24 at 9 49 58 PM" src="https://user-images.githubusercontent.com/100840176/164986033-3aa019cb-efe0-41c6-b701-e8a35a7512b3.png">

Here in the above snippet empName, empId, empAge, are the attributes of the “Employee” class.
The attributes of the class can be accessed with the help of the class object.

# Method:

A method must be declared within a class. It is defined with the name of the method, followed by parentheses (). Java provides some predefined methods, such as public static void main() , but you can also create your own methods to perform certain actions:

<img width="544" alt="Screenshot 2022-04-24 at 9 50 59 PM" src="https://user-images.githubusercontent.com/100840176/164986069-7888cbf7-ab9b-46fe-876c-b1d69e6af300.png">

# Java Constructors:

A constructor in Java is a special method that is used to initialize objects. The constructor is called when an object of a class is created. It can be used to set initial values for object attributes.

All classes have constructors, whether you define one or not, because Java automatically provides a default constructor that initializes all member variables to zero. However, once you define your own constructor, the default constructor is no longer used.

<img width="468" alt="Screenshot 2022-04-24 at 9 51 38 PM" src="https://user-images.githubusercontent.com/100840176/164986101-41ed9fb2-a7cd-4e36-8436-644965be57be.png">

Java allows two types of constructors namely −

* Default constructor(No-Arg Constructor) : A constructor is called "Default Constructor" when it doesn't have any parameter and it is created by default.
* Parameterized Constructor : A constructor which has a specific number of parameters is called a parameterized constructor, it is created by a programmer.
		
<img width="520" alt="Screenshot 2022-04-24 at 9 52 25 PM" src="https://user-images.githubusercontent.com/100840176/164986130-751ba198-afd1-42af-9f39-887f1bbe6f8a.png">

# Constructor Vs Method:

<img width="632" alt="Screenshot 2022-04-24 at 9 53 18 PM" src="https://user-images.githubusercontent.com/100840176/164986174-fe8889bd-c06a-47ad-a8ce-fc1f4bbbbd56.png">

# Access Modifiers in Java:

There are two types of modifiers in Java: access modifiers and non-access modifiers.

The access modifiers in Java specify the accessibility or scope of a field, method, constructor, or class. We can change the access level of fields, constructors, methods, and class by applying the access modifier on it.

There are four types of Java access modifiers:

1. Private: The access level of a private modifier is only within the class. It cannot be accessed from outside the class.
2. Default: The access level of a default modifier is only within the package. It cannot be accessed from outside the package. If you do not specify any access level, it will be the default. 
3. Protected: The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.
4. Public: The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.

There are many non-access modifiers, such as static, abstract, synchronized, native, volatile, transient, etc. Here, we are going to learn the access modifiers only.

<img width="624" alt="Screenshot 2022-04-24 at 9 55 07 PM" src="https://user-images.githubusercontent.com/100840176/164986296-f22fd253-04d1-4fef-bca3-8d0081d6616e.png">

# Encapsulation :

Encapsulation is one of the four fundamental OOP concepts. The other three are inheritance, polymorphism, and abstraction.
Encapsulation in Java is a mechanism of wrapping the data (variables) and code acting on the data (methods) together as a single unit. In encapsulation, the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class. Therefore, it is also known as data hiding.

To achieve encapsulation in Java  : 

* Declare the variables of a class as private.
* Provide public setter and getter methods to modify and view the variables values.
 
## Get and Set
You learned from the previous topic that private variables can only be accessed within the same class (an outside class has no access to it). However, it is possible to access them if we provide public get and set methods.

The get method returns the variable value, and the set method sets the value.

Syntax for both is that they start with either get or set, followed by the name of the variable, with the first letter in upper case:

Example:

<img width="540" alt="Screenshot 2022-04-24 at 10 06 20 PM" src="https://user-images.githubusercontent.com/100840176/164986721-e208f558-8e45-4e6f-9006-9e8c9ca33776.png">
	
# Java Packages & API :
A package in Java is used to group related classes. Think of it as a folder in a file directory. We use packages to avoid name conflicts, and to write a better maintainable code. Packages are divided into two categories:
 
* Built-in Packages (packages from the Java API) :The Java API is a library of prewritten classes that are free to use, included in the Java Development Environment.

Syntax:

import package.name.Class;   // Import a single class

import package.name.*;   // Import the whole package

EXAMPLE:

import java.util.Scanner;

class MyClass {

  public static void main(String[] args) {
  
    Scanner myObj = new Scanner(System.in);
    
    System.out.println("Enter username");
    
    String userName = myObj.nextLine();
    
    System.out.println("Username is: " + userName);
    
  }
  
}

* User-defined Packages (create your own packages):To create your own package, you need to understand that Java uses a file system directory to store them. Just like folders on your computer.
 
		└── root
  			└── mypack
    				└── MyPackageClass.java
 
To create a package, use the package keyword:

package mypack;

class MyPackageClass {

  public static void main(String[] args) {
  
    System.out.println("This is my package!");
    
  }
  
 
# Inheritance in Java:

In Java, it is possible to inherit attributes and methods from one class to another. We group the "inheritance concept" into two categories:

* subclass (child) - the class that inherits from another class
* superclass (parent) - the class being inherited from

To inherit from a class, use the extends keyword.

In the example below, the Car class (subclass) inherits the attributes and methods from the Vehicle class (superclass).

## Why use inheritance in java:

* For Method Overriding (so runtime polymorphism can be achieved).
* For Code Reusability.

Syntax:
	class Subclass-name extends Superclass-name  {  
	
			//methods and fields  
			
} 

## Types of Inheritance:

<img width="540" alt="Screenshot 2022-04-24 at 10 13 28 PM" src="https://user-images.githubusercontent.com/100840176/164987005-4492a3ba-7de4-44eb-ba70-7fc18ee8809f.png">

Example:

<img width="624" alt="Screenshot 2022-04-24 at 10 14 07 PM" src="https://user-images.githubusercontent.com/100840176/164987034-3a8cb6db-4343-4cf3-8ce0-380a25117689.png">

# Polymorphism:

The word polymorphism means having many forms. In simple words, we can define.polymorphism as the ability of a message to be displayed in more than one form.

## Real-life Illustration:

A person at the same time can have different characteristics. Like a man at the same time is a father, a husband, an employee. So the same person possesses different behavior in different situations. This is called polymorphism. 

## Types of Polymorphism:

In Java polymorphism is mainly divided into two types:

* Compile-time Polymorphism: It is also known as static polymorphism. This type of polymorphism is achieved by function overloading of operator overloading.

** Method Overloading: When there are multiple functions with the same name but different parameters then these functions are said to be overloaded. Functions can be overloaded by change in the number of arguments or/and a change in the type of arguments. 

* Runtime Polymorphism: It is also known as Dynamic Method Dispatch. It is a process in which a function call to the overridden method is resolved at Runtime. This type of polymorphism is achieved by Method Overriding. Method overriding, on the other hand, occurs when a derived class has a definition for one of the member functions of the base class. That base function is said to be overridden.

Example:

class Animal {

  public void animalSound() {
  
    System.out.println("The animal makes a sound");
    
  }
  
}

class Pig extends Animal {

  public void animalSound() {
  
    System.out.println("The pig says: wee wee");
    
  }
  
}

class Dog extends Animal {

  public void animalSound() {
  
    System.out.println("The dog says: bow wow");
    
  }
  
}





Public class Main {

  public static void main(String[] args) {
  
    Animal myAnimal = new Animal();  // Create a Animal object
    
    Animal myPig = new Pig();  // Create a Pig object
    
    Animal myDog = new Dog();  // Create a Dog object
    
    myAnimal.animalSound();
    
    myPig.animalSound();
    
    myDog.animalSound();
    
  }
  
}

Output:

The animal makes a sound

The pig says: wee wee

The dog says: bow wow

# Abstraction:

Abstraction is a process of hiding the implementation details and showing only functionality to the user.

Another way, it shows only essential things to the user and hides the internal details, for example, sending SMS where you type the text and send the message. You don't know the internal processing about the message delivery.

Abstraction lets you focus on what the object does instead of how it does it.

There are two ways to achieve abstraction in java :

1. Abstract class.
2. Interface.
 
The abstract keyword is a non-access modifier, used for classes and methods:

* Abstract class: is a restricted class that cannot be used to create objects (to access it, it must be inherited from another class).
* Abstract method: can only be used in an abstract class, and it does not have a body. The body is provided by the subclass (inherited from).

Example:

<img width="595" alt="Screenshot 2022-04-24 at 10 18 19 PM" src="https://user-images.githubusercontent.com/100840176/164987209-5530587e-798d-43c0-af7f-72086c74d7c9.png">

 
# Interface :

An interface in Java is a blueprint of a class. It has static constants and abstract methods.

The interface in Java is a mechanism to achieve abstraction.There can be only abstract methods in the Java interface, not method body. It is used to achieve abstraction and multiple inheritance in Java.

In other words, you can say that interfaces can have abstract methods and variables. It cannot have a method body.

There are mainly three reasons to use interfaces. They are given below:

* It is used to achieve abstraction.
* By interface, we can support the functionality of multiple inheritance.
* It can be used to achieve loose coupling.

## Syntax: 

interface Animal {

  public void animalSound(); // interface method (does not have a body)
  
  public void run(); // interface method (does not have a body)
  
}

## The relationship between classes and interfaces:

As shown in the figure given below, a class extends another class, an interface extends another interface, but a class implements an interface.

<img width="452" alt="Screenshot 2022-04-24 at 10 20 50 PM" src="https://user-images.githubusercontent.com/100840176/164987311-1d39212b-279f-4347-922c-1eb0d89c50ac.png">

Example :

<img width="468" alt="Screenshot 2022-04-24 at 10 21 17 PM" src="https://user-images.githubusercontent.com/100840176/164987334-f21a4067-28e5-4e6d-b25b-b6e1d3fbe529.png">



# User Input :

The Scanner class is used to get user input, and it is found in the java.util package.It is used to read the input of primitive types like int, double, long, short, float, and byte. It is the easiest way to read input in a Java program.

## Syntax :

Scanner sc=new Scanner(System.in);  
 
 
Methods of Java Scanner Class: 

<img width="625" alt="Screenshot 2022-04-24 at 10 25 37 PM" src="https://user-images.githubusercontent.com/100840176/164987528-b5718c4b-87dd-4a41-979e-59f4a8a17623.png">
 
 
Example: 

<img width="621" alt="Screenshot 2022-04-24 at 10 27 18 PM" src="https://user-images.githubusercontent.com/100840176/164987582-495fd444-d242-46ab-a6bc-0a958d025353.png">

# ArrayList :

Java ArrayList class uses a dynamic array.for storing the elements. It is like an array, but there is no size limit. We can add or remove elements anytime. So, it is much more flexible than the traditional array. It is found in the java.util package.

The ArrayList in Java can have the duplicate elements also. It implements the List interface so we can use all the methods of the List interface here. The ArrayList maintains the insertion order internally.

It inherits the AbstractList class and implements List interface

<img width="168" alt="Screenshot 2022-04-24 at 10 30 16 PM" src="https://user-images.githubusercontent.com/100840176/164987694-4d919477-cc91-4fe6-ba13-a390a8b2465a.png">

## The important points about the Java ArrayList class are:-

* Java ArrayList class can contain duplicate elements.
* Java ArrayList class maintains insertion order.
* Java ArrayList class is non synchronized . 
* Java ArrayList allows random access because the array works on an index basis.
* In ArrayList, manipulation is a little bit slower than the LinkedList in Java because a lot of shifting needs to occur if any element is removed from the array list.
* We can not create an array list of the primitive types, such as int, float, char, etc. It is required to use the required wrapper class in such cases.


# Methods of ArrayList :

## Add Items:

The ArrayList class has many useful methods. For example, to add elements to the ArrayList, use the add() method:

Example: 

​​import java.util.ArrayList;

public class Main {

  public static void main(String[] args) {
  
    ArrayList<String> cars = new ArrayList<String>();
    
    cars.add("Volvo");
    
    cars.add("BMW");
    
  }
  
}

## Access an Item:

To access an element in the ArrayList, use the get() method and refer to the index number:

Example:

cars.get(0);

## Change an Item:

To modify an element, use the set() method and refer to the index number:

Example:

cars.set(0, "Opel");

## Remove an Item:

* To remove an element, use the remove() method and refer to the index number:

Example:

cars.remove(0);

* To remove all the elements in the ArrayList, use the clear() method:

Example :

cars.clear();
 
# ArrayList Size:
To find out how many elements an ArrayList have, use the size method:

Example :

cars.size();

 
## Loop Through an ArrayList :

Loop through the elements of an ArrayList with a for loop, and use the size() method to specify how many times the loop should run:
 
Example:

public class Main {

  public static void main(String[] args) {
  
    ArrayList<String> cars = new ArrayList<String>();
    
    cars.add("Volvo");
    
    cars.add("BMW");
    
    cars.add("Ford");
    
    cars.add("Mazda");
    
    for (int i = 0; i < cars.size(); i++) {
    
      System.out.println(cars.get(i));
      
    }
    
  }

## Sort an ArrayList :

Another useful class in the java.util package is the Collections class, which include the sort() method for sorting lists alphabetically or numerically:

Example:

import java.util.ArrayList;

import java.util.Collections;  // Import the Collections class

public class Main {

  public static void main(String[] args) {
  
    ArrayList<String> cars = new ArrayList<String>();
    
    cars.add("Volvo");
    
    cars.add("BMW");
    
    cars.add("Ford");
    
    cars.add("Mazda");
    
    Collections.sort(cars);  // Sort cars
    
    for (String i : cars) {
    
      System.out.println(i);
      
    }
    
  }
  
}


# LinkedList class :

In the previous topic, you learned about the ArrayList class. The LinkedList class is almost identical to the ArrayList:

## ArrayList vs. LinkedList

The LinkedList class is a collection which can contain many objects of the same type, just like the ArrayList.

The LinkedList class has all of the same methods as the ArrayList class because they both implement the List interface. This means that you can add items, change items, remove items and clear the list in the same way.

However, while the ArrayList class and the LinkedList class can be used in the same way, they are built very differently.

## When To Use

Use an ArrayList for storing and accessing data, and LinkedList to manipulate data.
 
## LinkedList Methods :

<img width="655" alt="Screenshot 2022-04-24 at 10 35 28 PM" src="https://user-images.githubusercontent.com/100840176/164987910-c6fa3f63-085c-491f-bf12-c47a98296def.png">

# HashMap :

In the ArrayList chapter, you learned that Arrays store items as an ordered collection, and you have to access them with an index number (int type). A HashMap however, stores items in "key/value" pairs, and you can access them by an index of another type (e.g. a String).

One object is used as a key (index) to another object (value). It can store different types: String keys and Integer values, or the same type, like: String keys and String values:

## Points to remember

* Java HashMap contains values based on the key.
* Java HashMap contains only unique keys.
* Java HashMap may have one null key and multiple null values.
* Java HashMap is non synchronized.
* Java HashMap maintains no order.
* The initial default capacity of Java HashMap class is 16 with a load factor of 0.75.

Example:

Create a HashMap object called capitalCities that will store String keys and String values:

import java.util.HashMap; // import the HashMap class

HashMap<String, String> capitalCities = new HashMap<String, String>();

## Add Items
The HashMap class has many useful methods. For example, to add items to it, use the put() method:
 
Example: 

<img width="610" alt="Screenshot 2022-04-24 at 10 37 24 PM" src="https://user-images.githubusercontent.com/100840176/164987976-a53ecfd9-4e0b-4a2e-9ed1-8584e9b9a1fa.png">

## Access an Item:

To access a value in the HashMap, use the get() method and refer to its key:

Example: 

capitalCities.get("England");
 
## Remove an Item :

To remove an item, use the remove() method and refer to the key:

To remove all items, use the clear() method:

Example:

capitalCities.remove("England");

capitalCities.clear();

 
## HashMap Size:

To find out how many items there are, use the size() method:

Example:

capitalCities.size();

## Loop Through a HashMap :

Loop through the items of a HashMap with a for-each loop.

Note: Use the keySet() method if you only want the keys, and use the values() method if you only want the values:
 
Example:

// Print keys

for (String i : capitalCities.keySet()) {

  System.out.println(i);
  
}

// Print values

for (String i : capitalCities.values()) {

  System.out.println(i);
  
}

# Exception Handling: 

* Exception : Exception is an abnormal condition.In Java, an exception is an event that disrupts the normal flow of the program. It is an object which is thrown at runtime.

* Exception Handling : The Exception Handling in Java is one of the powerful mechanisms to handle the runtime errors so that the normal flow of the application can be maintained.

## Types of Java Exceptions

1) Checked Exception : The classes that directly inherit the Throwable class except RuntimeException and Error are known as checked exceptions. For example, IOException, SQLException, etc. Checked exceptions are checked at compile-time.

2) Unchecked Exception : The classes that inherit the RuntimeException are known as unchecked exceptions. For example, ArithmeticException, NullPointerException, ArrayIndexOutOfBoundsException, etc. Unchecked exceptions are not checked at compile-time, but they are checked at runtime.

3) Error : Error is irrecoverable.Some example of errors are OutOfMemoryError, VirtualMachineError, AssertionError etc.

<img width="335" alt="Screenshot 2022-04-24 at 10 43 12 PM" src="https://user-images.githubusercontent.com/100840176/164988216-0be33c2e-a68e-4287-97e5-bb2332f47401.png">

# Hierarchy of Java Exception classes

The java.lang.Throwable class is the root class of Java Exception hierarchy inherited by two subclasses: Exception and Error.

<img width="423" alt="Screenshot 2022-04-24 at 10 43 57 PM" src="https://user-images.githubusercontent.com/100840176/164988235-2797a43c-3d3f-47c9-9b67-ea9d258c222c.png">

# Java Exception Keywords :

Java provides five keywords that are used to handle the exception.

<img width="626" alt="Screenshot 2022-04-24 at 10 45 37 PM" src="https://user-images.githubusercontent.com/100840176/164988294-f5589bcf-dd0d-4e79-9a3a-e31e3d2e33e7.png">

Example:

<img width="549" alt="Screenshot 2022-04-24 at 10 46 17 PM" src="https://user-images.githubusercontent.com/100840176/164988330-edbb1ca7-659b-449a-9370-a59fdda32310.png">

# Lambda Expressions :

Lambda Expressions were added in Java 8.

A lambda expression is a short block of code which takes in parameters and returns a value. Lambda expressions are similar to methods, but they do not need a name and they can be implemented right in the body of a method.

## Syntax

Java lambda expression consists of three components.

1) Argument-list: It can be empty or non-empty as well.
2) Arrow-token: It is used to link arguments-list and body of expression.
3) Body: It contains expressions and statements for lambda expression.

 
The simplest lambda expression contains a single parameter and an expression:

parameter -> expression

(parameter1, parameter2) -> expression

(parameter1, parameter2) -> { code block }

## Why use Lambda Expression

1. To provide the implementation of Functional interface.
2. Less coding.

Example: 

Use a lambda expression in the ArrayList's forEach() method to print every item in the list:

<img width="500" alt="Screenshot 2022-04-24 at 10 48 18 PM" src="https://user-images.githubusercontent.com/100840176/164988410-5743d1c6-608e-4ce7-8383-7b1ef2eb8963.png">
