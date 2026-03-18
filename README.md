# 📱 Flutter Calculator App

A simple and interactive calculator application built using **Flutter**.  
This app performs basic arithmetic operations with a clean **mobile-style UI layout**.

---

## 🚀 Features

- 📟 Calculator-style button layout (Grid UI)
- ➕ Addition
- ➖ Subtraction
- ✖ Multiplication
- ➗ Division
- 🧹 Clear (C) functionality
- 📊 Real-time expression display
- ⚡ Instant result calculation

---

## 🛠️ Tech Stack

- **Flutter** (UI Framework)
- **Dart** (Programming Language)

---

## 📂 Project Structure
calculator_app/

│── lib/

│ └── main.dart # Main application logic

│── web/ # Web support files

│── pubspec.yaml # Dependencies & configuration


---

## 🧠 Concepts Used

### 🔹 StatefulWidget
Used to manage dynamic UI updates based on user interaction.

### 🔹 setState()
Updates UI when:
- Button is pressed
- Expression changes
- Result is calculated

### 🔹 GridView
Used to create calculator button layout (4x4 grid).

### 🔹 Event Handling
Each button triggers a function to update expression or calculate result.

---

## ⚙️ How It Works

1. User presses number/operator buttons  
2. Input is stored as a string expression  
3. On pressing `=`:
   - Expression is evaluated  
   - Result is displayed  
4. Pressing `C` resets the calculator  

---

## ▶️ How to Run

### 🔧 Prerequisites
- Flutter installed
- Chrome / Emulator available

### 🖥️ Run on Web

```bash
flutter run -d chrome

📱 Run on Mobile
flutter run
