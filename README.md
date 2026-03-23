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
git clone https://github.com/your-username/cli-contact-book.git
```

2. Navigate to the project folder:

```bash
cd cli-contact-book
```

3. Run the program:

```bash
python main.py
```

---

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
