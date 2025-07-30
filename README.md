# TollDevice 🚗💳

A simple Java application that simulates a toll device, allowing input and management of vehicle data, charges, and routes.

## 📦 Project Structure

The project structure is as follows:

```
TollDevice/
├── bin/                     # Compiled class files
├── lib/                     # Future libraries (currently empty)
├── src/                     # Java source code
│   ├── TollDevice.java
│   └── TollDeviceApp.java
├── .vscode/                 # VSCode settings (optional)
│   └── settings.json
└── README.md                # This file
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

- [Java JDK 11 or higher](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- Java compiler (`javac`)
- Optional: Visual Studio Code with Java Extension Pack

### 🛠️ Compilation

From the root project directory:

```bash
javac -d bin src/*.java
```

### ▶️ Run

From the `bin/` directory:

```bash
cd bin
java TollDeviceApp
```

---

## 📚 Class Description

### `TollDevice.java`

- Contains the main logic for toll operations.
- Implements features such as recording passages, calculating costs, and storing data.

### `TollDeviceApp.java`

- The application entry point (contains the `main()` method).
- Provides a simple text-based user interface.

---

## 🧪 Usage Examples

1. Register a new vehicle passage
2. Display passage history
3. Calculate total route cost

> ✅ The program works via terminal-based interaction.

---

## 💡 Future Improvements

- Support for data storage in files or databases
- Graphical User Interface (GUI) with JavaFX or Swing
- Exporting reports to PDF/CSV

---

## 🧑‍💻 Author

> **[George]** – [Add your GitHub link if you want.](https://github.com/GPap223)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
