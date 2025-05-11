
# DreamCar Dealership App

Welcome to the DreamCar Dealership Console App!  
This is a simple Java application designed to help users browse and manage car dealership inventory through a command-line interface.

## 📁 Project Structure

```
DreamCarWorkshop/
├── pom.xml                          # Maven build file
├── src/
│   └── main/
│       ├── java/
│       │   └── com/dreamcar/
│       │       ├── Main.java                # Entry point of the app
│       │       ├── ui/UserInterface.java   # Handles menu and user interactions
│       │       ├── model/Vehicle.java      # Represents a vehicle
│       │       ├── model/Dealership.java   # Represents the dealership and its inventory
│       │       └── data/DealershipFileManager.java # Reads vehicle data from file
│       └── resources/
│           └── dealership.csv              # Sample data file with dealership vehicles
```

## 🚀 How to Run

1. **Make sure Java is installed** (JDK 11+ recommended).
2. **Use an IDE** like IntelliJ IDEA or Eclipse, or build with Maven.

### Using Command Line:

```bash
# Navigate to the project directory
cd DreamCarWorkshop

# Compile the program
mvn compile

# Run the program
mvn exec:java -Dexec.mainClass="com.dreamcar.Main"
```

## 📦 Dependencies

- Java 11+
- Maven (for compiling and running)
- No external libraries required

## ✅ Features

- View a list of available vehicles
- Simple text-based menu
- Loads data from a CSV file
- Good for Java beginners to explore OOP and file I/O
