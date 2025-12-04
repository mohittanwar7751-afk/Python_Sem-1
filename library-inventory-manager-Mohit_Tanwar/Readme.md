📚 Library Inventory Manager

A command-line based library management tool built using Python, applying OOP principles, JSON storage, and logging to manage and track books efficiently.

⸻

📌 Features

✔ Add new books
✔ Issue a book
✔ Return a book
✔ View all books
✔ Search for a book
✔ Exit the application

(Available as a menu-driven CLI interface)  ￼

⸻

🧰 Technologies Used
	•	Python
	•	JSON
	•	pathlib
	•	logging  ￼

⸻

🗂️ Data Storage

All book records are stored in:
data/books.json
Format: JSON for easy retrieval and modification  


📝 Logging

Application logs and operations are saved in:
library.log
This helps track issued/returned books and errors during program execution.


🏗️ Project Structure 

Library-Inventory-Manager/
│
├── cli/
│   └── main.py
│
├── data/
│   └── books.json
│
├── logs/
│   └── library.log
│
├── report/
│   └── Library_Inventory_Manager_Report.pdf
│
└── README.md

🖥️ How to Run
	1.	Install Python (3.8+ recommended)
	2.	Open terminal in the project folder
	3.	Run:
  python -m cli.main
  4.	Follow the menu options displayed on screen.


  📷 Screenshots

This project includes screenshots of:
	•	Program running in terminal
	•	JSON book file
	•	Logging details

Screenshots are documented inside your project report PDF. 

🧾 Report File

Full project description, objectives, screenshots, and explanations are available in:

Library_Inventory_Manager_Report.pdf (already provided)



🚀 Future Improvements 
	•	GUI version using Tkinter or PyQt
	•	User login system (Admin / Student)
	•	Book due-date tracking
	•	Export PDF report of issued books

