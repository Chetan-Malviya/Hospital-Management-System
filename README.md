# 🏥 Hospital Management System (C++)

A console-based Hospital Management System implemented in C++.  
Simple patient/doctor appointment recording and basic staff info storage — designed as a learning/demo project demonstrating basic file I/O and object-oriented design.

---

## 🔎 Overview

This implementation provides:
- Patient appointment entry per doctor (three doctor files)
- View patient appointments
- Save and view staff information
- Hard-coded doctor schedule display
- Console menu-driven UI

Source file: `Hospital Management System/Hospital_Management_System.cpp`

---

## ⚙️ Build & Run

> **Notes:** current code uses Windows-only headers (`<conio.h>`, `<windows.h>`), `system("cls")`, and `getch()` — it is primarily targeted at Windows (MSVC or MinGW).

### Windows (MinGW / g++)
```bash
# from repo root
g++ -std=c++17 "Hospital Management System/Hospital_Management_System.cpp" -o HospitalManagement.exe
./HospitalManagement.exe
```

## ✅ Features

- Add patient appointments (name, time, age, appointment number)
- Store appointments separately for each doctor (`Ram.txt`, `arvind.txt`, `bhavesh.txt`)
- View and display saved patient appointments
- Save and display hospital staff details (`staff.txt`)
- View available doctor schedules and timings
