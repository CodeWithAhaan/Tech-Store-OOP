📦 Tech Store Inventory System – Java OOP (ICS4U Unit 4 Project)

A complete Java Object-Oriented Programming project demonstrating abstract classes, inheritance, method overriding, method overloading, polymorphism, constructors, static variables, and arrays of objects.

This project simulates a tech store that sells laptops and phones, calculates discounted prices, and tracks the total number of laptops created.

📘 Project Overview

This program uses a base abstract class, Product, and extends it into two subclasses: Laptop and Phone.
Each product calculates its own discount, and polymorphism is demonstrated by storing mixed objects inside a Product[] array.

The project is based on the ICS4U Unit 4 OOP topics, designed to help students build strong understanding of Java OOP fundamentals.

🧩 Concepts Used

This project includes the following OOP concepts:

Abstract Classes
Inheritance
Method Overriding
Method Overloading
Constructors
Access Modifiers
Static Variables
Arrays of Objects
Polymorphism

📝 Assignment Requirements

PART 1 — Abstract Class: Product

Create an abstract class with:

private fields: name, price
constructor
getters
abstract method: double discountPrice()
method: void info() → prints product name

PART 2 — Laptop Class

extends Product
fields: ram, static count
constructor(name, price, ram)
overloaded constructor (name, price) → default ram = 8
override discountPrice() → 10% off
override info() → show name + ram
increment count for each laptop
static method getCount()

PART 3 — Phone Class

extends Product
field: carrier
constructor(name, price, carrier)
override discountPrice() → 5% off
override info() → show name + carrier

PART 4 — StoreMain Class

Create a Product[] array of size 5
Fill with Laptop and Phone objects

Loop through array:
print info
print discounted price

Print total laptops created

This demonstrates polymorphism, since the array holds multiple subclasses.

🖥 Sample Output
Product: Macbook M1
RAM: 8
Discounted Price: 900.0

Product: Iphone 16 Pro
Carrier: UPS
Discounted Price: 1377.5

Product: Samsung s24
Carrier: Fedex
Discounted Price: 1425.0

Product: Chrome Book
RAM: 2
Discounted Price: 180.0

Product: Google Pixel 9
Carrier: UPS
Discounted Price: 1140.0

Total laptops created: 2

📂 File Structure
Tech-Store-OOP/
├── Product.java
├── Laptop.java
├── Phone.java
└── StoreMain.java

🚀 How to Run

Compile all .java files: javac *.java
Run the program: java StoreMain

⭐ Why This Project Is Valuable

Understanding Java OOP fundamentals
Learning polymorphism and abstraction
Java beginner–intermediate practice

📄 License

This project is open-source under the MIT License.
