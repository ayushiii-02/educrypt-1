# 🛡️ EduCrypt - Secure Education Management Platform

EduCrypt is a robust web-based application designed to streamline and secure educational workflows such as student management, assignments, real-time chat, online code compilation, attendance, and more. It leverages authentication, role-based access control, and modern development tools to offer a full-stack solution for educational institutions.

---

## 🚀 Features

- 🔐 **Authentication & Authorization**
  - JWT-based login for Admin, Faculty, and Students
  - Google OAuth integration

- 📚 **Course & Assignment Management**
  - Admins and faculty can upload and manage assignments
  - Students can view and submit assignments

- 📆 **Attendance System**
  - Faculty can mark and view attendance
  - Students can check their attendance status

- 💬 **Real-time Chat**
  - In-app messaging between students and faculty

- 💻 **Online Compiler**
  - Compile and run code snippets in-browser for coding exercises

- 📂 **Document Handling**
  - Upload, parse, and manage PDF documents
 
## ✨ Extra Features

- 🔎 **Student PDF Upload Parsing**
  - Extract and parse PDFs with student assignments
- 🧠 **Gemini AI API Integration**
  - Experimental AI-based support system (for document Q&A or code analysis)
- 📧 **Email Notifications**
  - Auto-email students or faculty via Gmail SMTP
- 🛡️ **Role-based Access Control**
  - Custom dashboards for Admin, Faculty, and Students
- 📝 **Assignment Grading/Tracking**
  - Faculty can view and manage student submissions
- 🔐 **Secure Token-Based Auth**
  - JWT sessions, token validation, and protected routes
- ⏳ **Timestamps & Submission Logs**
  - Logs of assignment uploads with auto time capture
---

## 🛠️ Tech Stack

**Frontend:**
- HTML5, CSS3, TailwindCSS
- JavaScript (vanilla)
- Student-side views (file upload, compiler interface, attendance display)
- Responsive layout design for usability across devices
- 
**Backend:**
- Node.js with Express
- MongoDB with Mongoose
- Passport.js for authentication
- JWT for session management
- Nodemailer for email alerts
- Axios, Bcrypt.js, dotenv

**Dev Tools & APIs:**
- Postman (for API testing)
- Google OAuth
- Gemini AI API (experimental integration)
- Email via Gmail SMTP

---

## 📁 Project Structure
/Backend
│
├── server.js # Main server entry
├── package.json # Dependencies
├── .env # Environment variables (excluded)
│
├── config/ # DB and passport configurations
│
├── controllers/ # Core app logic
│ ├── adminController.js
│ ├── assignmentController.js
│ ├── attendanceController.js
│ └── ...
│
├── routes/ # API routing (add if applicable)
├── models/ # MongoDB schemas (add if applicable)
└── views/ # HTML templates (if used)


---

## 🧪 How to Run Locally

```bash
# Clone this repo
git clone https://github.com/your-username/educrypt.git
cd educrypt/Backend

# Install dependencies
npm install

# Set up .env (use your own secrets)
touch .env

# Start the server
node server.js

EduCrypt demonstrates:

Full-stack engineering capability

RESTful API development

MongoDB schema design

Role-based access and session handling

Security-first mindset (token auth, API key safety)

Scalable project structure for education tech

📬 Contact
Built by Pooja Liladhar Bagul & Ayushi Soni 
LinkedIn: www.linkedin.com/in/poojabagul | www.linkedin.com/in/ayushi2
Email: pooja.l.bagul9805@gmail.com | ayushiii2212@gmail.com

