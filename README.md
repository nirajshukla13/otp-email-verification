# OTP Email Verification

A simple Node.js application for sending and verifying One-Time Passwords (OTP) via email.  
This project uses **Express**, **Nodemailer**, and **dotenv** to send OTPs to users securely.

---

## 📂 Project Structure

OTP/
├── node_modules/ # Dependencies
├── public/
│ └── index.html # Frontend form for OTP input
├── server.js # Main backend server file
├── package.json # Project metadata and dependencies
├── .env # Environment variables
└── README.md # Project documentation

---

## ⚙️ Features

- Send OTP via email
- Verify OTP entered by the user
- Environment variable support for secure credentials
- Simple frontend for input

---

## 📦 Installation

1. **Clone the repository** (or download the project folder)
   ```
   git clone <your-repo-url>
   cd OTP
Install dependencies

npm install
Create .env file in the project root with your configuration:

EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
PORT=3000
🚀 Usage
Start the server

node server.js
or (if using nodemon for auto-restart):

npx nodemon server.js
Open the app
Go to http://localhost:3000 in your browser.

Enter your email
The app will send an OTP to the provided email, which you can then enter to verify.

🛠 Technologies Used
Node.js

Express.js

Nodemailer

dotenv

📜 License
This project is licensed under the MIT License.

---

If you want, I can also **add a "Message" along with the OTP** inside `server.js` so the email looks more professional instead of just a raw number. That way the OTP email says something like:  

> *"Your OTP for verification is: 123456. It is valid for 5 minutes."*  

Do you want me to add that now?



