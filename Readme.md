🔐 FUTURE_CS_03 — Secure File Sharing System
📌 Project Title

Secure File Sharing System Using AES Encryption

📖 Description

This project is developed as part of Future Interns – Cyber Security Internship (Task-3).
It is a secure web-based application that allows users to upload files, encrypt them using AES (Advanced Encryption Standard), and securely download the decrypted files.

The goal of this project is to demonstrate data protection, encryption at rest, and secure file handling.

🎯 Features

✔ Secure file upload
✔ AES encryption of files
✔ Encrypted storage on server
✔ Secure file decryption
✔ File download in original format
✔ Web-based interface using Flask

🛠️ Technologies Used

Python 3

Flask

AES Encryption (PyCryptodome)

HTML

🔐 How Security is Implemented

When a user uploads a file:

The file is encrypted using AES (EAX Mode)

The encrypted file is stored in the server

The original content is not readable

On download, the file is decrypted securely

This ensures data confidentiality and protection against unauthorized access.

🧪 How to Run

Install dependencies

pip install flask pycryptodome


Run the application

python app.py


Open in browser

http://127.0.0.1:5000

📁 Project Structure
secure_file_app
│
├── app.py
├── uploads
└── encrypted

📸 Proof of Work

Uploaded files become unreadable inside the encrypted folder

Downloaded files return in original format

This proves AES encryption and decryption are working correctly.

🎓 Internship Task

This project fulfills Task-3 of the Future Interns Cyber Security Internship Program
by implementing a Secure File Sharing System using Encryption.

👩‍💻 Developed by

Priya Dharshini L
Cyber Security Intern – Future Interns
