# 📘 Student Registration System (SRS)

A **Student Registration System** built with **Python (Tkinter GUI)** that allows you to manage student data, save it into **Excel (xlsx)**, and upload student profile pictures.  

This application is useful for small institutes, schools, or demo projects where maintaining student records digitally is required.

---

## 🚀 Features

- 📋 **Student Data Entry**  
  Register students with details such as name, class, gender, date of birth, religion, skills, and parents' details.

- 🖼️ **Profile Picture Upload**  
  Upload and save each student’s photo in a separate folder.

- 🔎 **Search & Update**  
  Search students by registration number and update their details.

- 💾 **Excel Integration**  
  Automatically saves student data in `Student_data.xlsx`.

- 🔐 **Auto Registration Number**  
  Auto-increments registration numbers for each new entry.

- 🎨 **Modern Tkinter GUI**  
  Simple, clean, and user-friendly interface.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Tkinter** (GUI framework)
- **Pillow** (for handling images)
- **openpyxl** (for Excel integration)
- **xlrd** (for reading Excel files)

---

## 📂 Project Structure

```
Student_Registration_sys/
│-- images/                # Icons and UI images (search, upload, update buttons)
│-- SRS_Pics/              # Uploaded student profile pictures
│-- Student_data.xlsx      # Generated Excel file containing student data
│-- SRS.py                 # Main application script
│-- requirements.txt       # Dependencies
│-- README.md              # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Student_Registration_System.git
   cd Student_Registration_System
   ```

2. **Create virtual environment (recommended)**
   ```bash
   python -m venv venv-SRS
   source venv-SRS/Scripts/activate   # On Windows (PowerShell)
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python SRS.py
   ```

---

## 📦 Requirements

Add these to your `requirements.txt`:
```txt
pillow
openpyxl
xlrd
```

---

## 📸 Screenshots (Optional)

> *(You can add screenshots of your UI here after running the project)*

---

## 🧑‍💻 Author

**Shahriyar Khan**  
📧 Email: shahriyarkhanpk1@gmail.com  

---

## 📜 License

This project is open-source and available under the **MIT License**.
