# 🚗 Java Object-Oriented Vehicle Management System

This is a simple Object-Oriented Programming (OOP) Java project simulating an elementary **Vehicle System**. It illustrates fundamental OOP principles including **abstraction**, **inheritance**, **interfaces**, and **polymorphism** via vehicles such as **Cars** and **Bikes** — with the ability to **Electric Vehicles**.

---

## 📁 Project Structure
- `App.java`: Main entry for object usage demonstration.
- `Main.java`: Illustrates memory allocation principles.
- `Vehicle.java`: Abstract class with essential vehicle methods.
- `Bike.java`: Subclass of Vehicle.
- `Car.java`: Subclass of Vehicle, implements ElectricVehicle.
- `ElectricVehicle.java`: Interface with EV-specific methods.

---

## 🎯 Features Exhibited

- **Abstraction**: `Vehicle` is an abstract class that specifies the blueprint for all vehicles.
- **Inheritance**: `Bike` and `Car` classes extend `Vehicle`.
- **Interfaces**: `Car` implements `ElectricVehicle` interface.
- **Polymorphism**: Methods perform differently depending on subclass implementation.
- **Types of Memory**: `Main.java` discusses `heap`, `stack`, and `method` memory regions.

---

## 🚀 How to Run
- **Compile all files:**
  ```bash
  javac *.java
  ```
- **Run the main App:**
  ```bash
  java App
  ```
- **Run Memory Allocation Demo(Optional):**
  ```bash
  java Main
  ```

  ---
  
  ## ✍️ Author's Note
  This is a classroom-level exercise to solidify OOP principles on Day-2 of Java Training. Ideal for beginners learning Java and software design principles.

  ---
