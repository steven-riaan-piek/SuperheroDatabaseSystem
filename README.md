# 🦸 One Kick Heroes Academy - Superhero Management System

**By:**  
Steven Riaan Piek (602240)  
Adin Henry Greyling (603116)  
Wildre Fourie (601625)  
Ryno Martin Goetz (602306)  

---

## 📌 Project Overview

This C# Windows Forms application manages superhero records for the One Kick Heroes Academy.  
The system tracks trainee heroes, automatically calculates their ranks based on exam scores, and generates comprehensive reports to support the academy's assessment process.

---

## ⚙️ Features

### 🔹 Core Functionality

- **Add New Superhero**  
  Input hero details including ID, name, age, superpower, and exam score

- **View All Superheroes**  
  Display all records in a DataGridView with calculated ranks and threat levels

- **Update Superhero Information**  
  Search by ID and modify hero details with automatic rank recalculation

- **Delete Superhero**  
  Remove heroes from the system with confirmation

- **Generate Summary Report**  
  Calculate statistics and save to `summary.txt`

---

## 🏆 Ranking System

| Rank   | Score Range | Threat Level |
|--------|------------|-------------|
| S-Rank | 81-100     | Finals Week (threat to the entire academy) |
| A-Rank | 61-80      | Midterm Madness (threat to a department) |
| B-Rank | 41-60      | Group Project Gone Wrong (threat to a study group) |
| C-Rank | 0-40       | Pop Quiz (potential threat to an individual student) |

---

## 🛠️ Technical Details

### 💻 Technologies Used

- **Language:** C# (.NET 8.0)
- **Framework:** Windows Forms
- **Data Storage:** Text files (`superheroes.txt`, `summary.txt`)
- **Version Control:** Git with GitHub integration

---

## 📁 Project Structure
Project_PRG282_Final/
│
├── Project_PRG282/
│ ├── Form1.cs # Main form logic
│ ├── Form1.Designer.cs # Form design
│ ├── Hero.cs # Hero class definition
│ ├── Program.cs # Application entry point
│ ├── Project_PRG282.csproj
│
├── Project_PRG282.sln # Solution file
├── .gitignore # Git ignore rules
├── README.md # This file


---


---

## ⚡ Setup Instructions

### 📋 Prerequisites

- Visual Studio 2022 or later  
- .NET 8.0 SDK  
- Git  

---

### 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/SuperheroDatabaseSystem.git
cd Project_PRG282_Final

```

2. Open the solution in Visual Studio:
```bash
Project_PRG282/Project_PRG282.sln
```

3. Build and run the application:
Press F5 or click Start Debugging

▶️ Usage
1. Adding Heroes
Fill in the form fields and click Add
2. Viewing Heroes
Click View All
3. Updating Heroes
Select a row → edit → click Update

📄 File Formats
🦸 superheroes.txt

Each line contains comma-separated values:
```bash
HeroID,Name,Age,Superpower,ExamScore,Rank,ThreatLevel
```
📊 summary.txt

Contains formatted statistics:

Total number of superheroes
Average age and exam score
Count of heroes per rank
Timestamp


🔁 Version Control

This project uses Git with the following structure:

Initial project setup
Feature commits (add, update, delete, report)
Clear and meaningful commit messages

⚠️ Error Handling

The application includes error handling for:

File I/O operations
Input validation (age, exam score ranges)
Data parsing
User input validation

👨‍💻 Development Team

This project was developed as part of PRG282 coursework for the One Kick Heroes Academy system.

📜 License

This project is developed for educational purposes.

Built with C# Windows Forms for the One Kick Heroes Academy
