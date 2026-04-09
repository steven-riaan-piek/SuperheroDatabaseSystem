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
