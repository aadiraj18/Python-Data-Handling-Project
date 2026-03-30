# 📔 CLI Contact Book (CSV-Powered)

A simple and efficient **Command Line Contact Book** built using Python.
This application allows users to store, manage, search, update, and delete contacts using a CSV file.

---

## 🚀 Features

* ➕ Add new contacts (Name, Phone, Email)
* 📋 View all saved contacts
* 🔍 Search contacts with **partial name matching**
* ✏️ Update existing contacts
* ❌ Delete contacts
* 🛡️ Prevent duplicate contact names
* 📂 Automatic CSV file creation
* 🧾 Clean and simple CLI interface

---

## 🛠️ Technologies Used

* Python
* CSV Module
* OS Module

---

## 📁 File Structure

```
📦 CLI-Contact-Book
 ┣ 📜 contacts.csv   # Stores contact data
 ┣ 📜 main.py        # Main Python program
 ┗ 📜 README.md      # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/aadiraj18/Python-Data-Handling-Project.git
cd Python-Data-Handling-Project
python contact_book.py
```

## 💻 Usage

After running the program, you will see:

```
📔 Contact Book
1. Add Contact
2. View All Contact
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit
```

* Choose an option by entering a number.
* Follow on-screen prompts.

---

## 📌 Example

```
Name: John Doe
Phone: 9876543210
Email: john@example.com

Contact added successfully!
```

---

## ⚡ Improvements You Can Add

* 📊 Table formatting using `tabulate`
* 📱 Phone number validation
* 📧 Email validation
* 🔒 Data encryption
* 🖥️ GUI version using Tkinter or PyQt
* 🌐 Convert to a web app (Flask/Django)

---

## 🐞 Known Issues

* Update function currently adds a new contact instead of modifying existing one
* No strict validation for phone/email

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is open-source and available



# 🎓 Student Marks Analyzer (Python CLI Project)

A simple command-line based Python program to manage and analyze student marks. This project allows users to input student data and generate a structured report with useful statistics.

---

## 🚀 Features

* ➕ Add multiple students with their marks
* ❌ Prevent duplicate student entries
* 📊 Automatically calculate:

  * Average marks
  * Highest marks (with student names)
  * Lowest marks (with student names)
  * Total number of students
* 📋 Display a clean report with detailed marks
* ⚠️ Handles invalid inputs (non-numeric marks)

---

## 🛠️ Technologies Used

* Python 3
* Built-in functions (`max`, `min`, `sum`, `list`, `dict`)
* Exception handling (`try-except`)

---

## 📂 Project Structure

```
student-marks-analyzer/
│
├── student_marks_analyzer.py   # Main Python program
└── README.md                  # Project documentation
```

---

## ▶️ How to Run

```bash
git clone https://github.com/aadiraj18/student-marks-analyzer.git
cd Python-Data-Handling-Project
python student_marks_analyzer.py
```

---

## 💡 Usage

* Enter student names and marks when prompted
* Type `done` to finish data entry
* View the generated report instantly

---

## 🧠 Example Output

```
Student marks report 📝
------------------------------
Total students: 3
Average marks: 78.33
Highest marks: 90 by Aadi
Lowest marks: 65 by Rahul
------------------------------
Detailed Marks 📝
 - Aadi: 90
 - Rahul: 65
 - Neha: 80
```

---

## ✨ Future Improvements

* Save data to a file (CSV/JSON)
* Add grade classification (A, B, C, etc.)
* Create a GUI version using Tkinter
* Add sorting (rank-wise display)

---

## 👨‍💻 Author

**Aadi Raj**
B.Tech CSE (Data Science)

---

## ⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
