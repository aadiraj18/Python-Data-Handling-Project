📔 CSV Contact Book (CLI)
A lightweight, terminal-based contact management system powered by Python. This tool allows users to store, search, update, and delete contacts using a persistent contacts.csv file.

🚀 Features
Persistent Storage: All data is saved in a standard CSV format.

Duplicate Prevention: Automatically checks if a name already exists before adding.

Search Functionality: Supports partial name matching to find contacts quickly.

Full CRUD Operations:

Create new contacts.

Read/View all saved contacts.

Update existing contact details.

Delete unwanted entries.

Auto-Initialization: Automatically creates the contacts.csv file with headers if it doesn't exist.

🛠️ Requirements
Python 3.x

No external libraries required (uses built-in csv and os modules).

📥 Installation & Usage
Clone the repository:

Bash
git clone https://github.com/your-username/contact-book-cli.git
cd contact-book-cli
Run the application:

Bash
python contact_book.py
Navigate the Menu:
Follow the on-screen prompts (1-6) to manage your contact list.

📊 CSV Structure
The data is stored in the following format:
| Name | Phone | Email |
| :--- | :--- | :--- |
| John Doe | 123-456-7890 | john@example.com |

📝 To-Do / Future Improvements
[ ] Add input validation for phone numbers and email formats.

[ ] Implement a prettier table view using the tabulate library.

[ ] Add a confirmation prompt before deleting a contact.

📄 License
This project is open-source and available under the MIT License.
