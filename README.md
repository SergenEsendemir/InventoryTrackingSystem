# Fixed Asset & Inventory Tracking System

![CSharp](https://img.shields.io/badge/C%23-.NET-green)
![WinForms](https://img.shields.io/badge/UI-Windows%20Forms-blue)
![Database](https://img.shields.io/badge/Database-SQL%20Server%20Express-orange)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Status](https://img.shields.io/badge/Status-Demo%20Project-yellow)
![License](https://img.shields.io/badge/License-Not%20Specified-red)

A **Fixed Asset & Inventory Tracking System** desktop application developed using **C# (.NET Framework)** and **Windows Forms**, with **SQL Server Express** as the database.

This project provides a form-based stock and fixed-asset management system including admin panels, menus, search screens, and CRUD operations.

---

## 🧠 Overview

This project demonstrates:

- Desktop application development with **C# WinForms**
- Fixed asset (Demirbaş) and stock tracking workflows
- Multi-form navigation (Admin, Main Menu, Search screens, etc.)
- Database-driven CRUD operations
- Integration with **SQL Server Express**

It is suitable for **educational purposes**, **practice projects**, and **small-scale enterprise demos**.

---

## ✨ Features

- 🔐 Admin login & authorization screens
- 🧑‍💼 Admin panel management
- 🧾 Fixed asset (demirbaş) records
- 📦 Stock / inventory tracking
- 🔍 Search & filter forms
- 🧭 Main menu–based navigation
- 💾 Persistent data storage via SQL Server Express

---

## 🧰 Tech Stack

- **C#**
- **.NET Framework**
- **Windows Forms**
- **SQL Server Express**
- **ADO.NET** for database operations

---

## 📂 Project Structure

```text
DemirbasStokTakipProgrami/
├── Properties/                    # Project properties
├── Resources/                     # UI resources
├── bin/                           # Build output
├── obj/                           # Build intermediates
├── App.config                     # SQL Server connection string
├── Program.cs                     # Application entry point
├── YazilimSinamaProjesi.csproj    # Project file
├── Test1.cs                       # Test / helper class
├── frmAdmin.cs                    # Admin panel form
├── frmAdmin.Designer.cs
├── frmAdmin.resx
├── frmAnaMenu.cs                  # Main menu form
├── frmAnaMenu.Designer.cs
├── frmAnaMenu.resx
├── frmAramalar.cs                 # Search operations form
├── frmAramalar.Designer.cs
├── frmAramalar.resx
├── ...                            # Other form-based pages
└── README.md
```

> The project follows a **classic Windows Forms architecture**, where each screen is represented by its own Form (`frm*.cs`).

---

## 🗄️ Database

- Database technology: **SQL Server Express**
- Connection string is defined in `App.config`
- Used for storing:
  - Fixed asset records
  - Stock / inventory data
  - User and admin information

Database access is handled using **ADO.NET**.

---

## 📌 Prerequisites

To run this project locally, you need:

- Windows OS
- Visual Studio 2019 or later
- .NET Framework installed
- SQL Server Express installed

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/SergenEsendemir/InventoryTrackingSystem.git
   ```

2. **Open the solution**
   - Open the `.csproj` or `.sln` file in Visual Studio

3. **Configure Database**
   - Ensure SQL Server Express is running
   - Update the connection string in `App.config` if necessary

4. **Run**
   - Press **F5** or click **Start Debugging**

---

## 🎯 Purpose

This project was created to:

- Practice C# Windows Forms development
- Learn SQL Server Express integration
- Build multi-form desktop business applications
- Understand fixed asset & stock tracking workflows

It is a **learning-focused demo project**, not intended for production use.

---

## 🤝 Contributing

Contributions are welcome:

- UI improvements
- Code refactoring
- Database schema enhancements
- Feature extensions

---

## 👤 Author

**Sergen Esendemir**  
GitHub: https://github.com/SergenEsendemir

---

## 📄 License

No license is currently specified.  
You may add one if required (e.g., MIT License).
