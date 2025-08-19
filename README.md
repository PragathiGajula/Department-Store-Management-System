# 🏬 Department Store Management System  

A **C-based console application** that helps manage a department store by handling operations like billing, adding items, editing records, searching, and deleting items. This project demonstrates **file handling, structures, and menu-driven programming in C**.  

---

## ✨ Features  
- 📋 **Main Menu with navigation** (using `gotoxy` for cursor movement).  
- 💰 **Billing system** – calculate total bill and update stock.  
- ➕ **Add new items** to the store inventory.  
- ✏️ **Edit item details** (name, code, rate, quantity).  
- 🔍 **Search items** by code, rate, or quantity.  
- 📂 **Display all items** stored in `record.txt`.  
- ❌ **Delete items** from the inventory.  
- 🗂️ Uses a **binary file (record.txt)** to store data persistently.  

---

## 🛠️ Technologies Used  
- **Language:** C  
- **Libraries:** `<stdio.h>`, `<stdlib.h>`, `<string.h>`, `<conio.h>`, `<windows.h>`  
- **Platform:** Windows (due to `conio.h` and `windows.h` dependencies)  

---

## 🚀 How to Run  

### On Windows (with GCC / MinGW):  
```sh
gcc "department store management system.c" -o store.exe
store.exe
```

### On Turbo C++ (DOS-based):  
- Open Turbo C++  
- Compile (`Ctrl+F9`)  
- Run (`Ctrl+F10`)  

⚠️ Note: This program is **Windows-only** since it uses `<windows.h>` and `<conio.h>`.  

---

## 📂 File Structure  
```
department-store-management-system/
│── department store management system.c   # Main source code
│── record.txt                             # Auto-created file storing items
│── README.md                              # Project description
```

---

## 📖 Learning Objectives  
- Working with **structures** in C  
- Implementing **file handling** (`fopen`, `fread`, `fwrite`, `fseek`)  
- Creating a **menu-driven console application**  
- Using **cursor positioning** (`gotoxy`) for interactive menus  

---

## 📸 Screenshots (Optional)  
*(Add screenshots of your console UI here if you want)*  

---

## 📌 Future Improvements  
- Port the project to **Linux/Mac (remove windows.h)**  
- Add **graphical UI (GTK/Qt)**  
- Add **user authentication** for admin access  

---

## 👨‍💻 Author  
Developed as a **C programming project** for learning **file handling and inventory management system implementation**.  
