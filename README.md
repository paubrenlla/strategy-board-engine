# Board Game Strategy System

> **Academic Capstone Project** | Programming 2 (Programación 2)  
> **Universidad ORT Uruguay** | Semester: March 2023

## Project Overview
This project is a fully functional, turn-based strategy board game developed in **Java**. It was designed to demonstrate advanced Object-Oriented Programming (OOP) concepts, focusing on game state management, complex validation rules, and external library integration.

## Features
* **Custom Game Engine:** Implementation of board logic, including player movements and scoring systems.
* **PDF Report Generation:** Integrated **iText** library to export match results and player statistics into professional PDF documents.
* **Data Management:** System for registering players, tracking match history, and maintaining global rankings.
* **OOP Best Practices:** Use of inheritance, polymorphism, and custom sorting criteria (Comparators) to manage game entities.
* **Input Validation:** Robust handling of user inputs to ensure a seamless gameplay experience.

## Technical Stack
* **Language:** Java 11+
* **Libraries:** iText PDF (for report generation).
* **Paradigm:** Object-Oriented Programming.
* **Tools:** NetBeans / Apache Ant.

## Key Components
* `src/dominio`: Core logic including `Partida`, `Jugador`, and `TableroColcha`.
* `src/interfaz`: Console-based user interface and menu navigation.
* `lib/`: External dependencies (iText PDF).

## How to Play
The game follows a strategy-based logic where players compete on a board to build the most efficient "quilt" (Colcha). Results can be exported at the end of each session for performance analysis.
