# Java Assignment 2 – RadioButtonDemo

## Description
A Java Swing application that uses **five radio buttons** to let the user choose which kind of pet is displayed. The application draws each pet using Java2D graphics and shows a **JOptionPane message box** confirming the user's selection.

## Pets Supported
- 🐦 Bird
- 🐱 Cat
- 🐶 Dog
- 🐰 Rabbit
- 🐷 Pig (default selection)

## Features
- Five mutually-exclusive radio buttons using `ButtonGroup`
- Pet illustration drawn in real-time with Java2D (`Graphics2D`)
- Message dialog (`JOptionPane`) on every selection
- Keyboard mnemonics on all buttons (Alt + B/C/D/R/P)

## How to Run

### Option 1 — Double-click
Run `run.bat` (uses the Adoptium JDK 17 cached by Gradle on this machine).

### Option 2 — Command line (if Java is on your PATH)
```bash
javac -encoding UTF-8 RadioButtonDemo.java
java RadioButtonDemo
```

## Screenshots
Screenshots of the running application are in the [`images/`](images/) folder.

## Source Code
- [`RadioButtonDemo.java`](RadioButtonDemo.java) — single-file application

## Author
Java Assignment 2 | Object-Oriented Programming
