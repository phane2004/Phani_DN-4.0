# Week 1: Design Pattern Implementations

This folder contains Java implementations of 11 commonly used software design patterns as part of the Digital Nurture 4.0 Java FSE training.

## 📘 List of Design Patterns

### 1. Singleton Pattern
- Ensures a class has only one instance and provides a global point of access to it.
- Example: Logger utility.

### 2. Factory Method Pattern
- Defines an interface for creating an object, but lets subclasses alter the type of objects that will be created.
- Example: Creating Word, PDF, and Excel documents using separate factories.

### 3. Builder Pattern
- Separates the construction of a complex object from its representation.
- Example: Constructing a `Computer` with optional parts.

### 4. Adapter Pattern
- Allows incompatible interfaces to work together by converting one interface into another.
- Example: Unifying third-party payment gateway APIs under one interface.

### 5. Decorator Pattern
- Dynamically adds new behavior to objects by placing them inside wrapper objects.
- Example: Sending notifications via Email, SMS, and Slack using decorators.

### 6. Proxy Pattern
- Provides a surrogate or placeholder for another object to control access.
- Example: Image loading system using lazy initialization and caching.

### 7. Observer Pattern
- Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified.
- Example: Stock price updates to mobile and web apps.

### 8. Strategy Pattern
- Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
- Example: Payment system supporting Credit Card and PayPal strategies.

### 9. Command Pattern
- Encapsulates a request as an object, thereby allowing for parameterization and queuing of requests.
- Example: Home automation system to control light on/off using commands.

### 10. MVC Pattern
- Separates the application into three interconnected components (Model, View, Controller).
- Example: Student record management.

### 11. Dependency Injection
- A technique where an object receives its dependencies from an external source rather than creating them itself.
- Example: Injecting `CustomerRepository` into `CustomerService`.

## 🛠️ How to Run

For each pattern folder:
1. Open terminal inside the folder.
2. Compile and run using:

```bash
javac Main.java
java Main
