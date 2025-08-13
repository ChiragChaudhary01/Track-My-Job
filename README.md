# 📌 Track My Job

**Track My Job** is a MERN stack web application to help users manage and track their job applications efficiently.  
It allows adding, updating, deleting, and filtering job entries, making job hunting more organized.

🔗 **Live Demo:** [Add your deployed link here]  
💻 **GitHub Repo:** [This Repo URL]  
📥 **Open to contributions — feel free to fork and make a pull request!**

---

## 🚀 Features

- 🔐 **Secure Authentication** (JWT-based login/signup)
- 📋 **Add, Update, Delete** job applications
- 🔍 **Search & Filter** jobs with debounce optimization (fewer API calls, faster UX)
- 📊 **View total jobs count**
- 🖥 **Responsive design** for desktop & mobile
- 📧 **Email integration** (for OTP or notifications via Nodemailer)

---

## 🛠 Tech Stack

**Frontend:**

- React.js (Vite)
- TailwindCSS
- Axios

**Backend:**

- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- bcrypt.js (password hashing)
- Nodemailer (Email sending)

---

## 📂 Project Structure

TRACKMYJOB/
│
├── client/ # Frontend (React + Vite)
│ ├── src/
│ ├── public/
│ ├── .env
│ └── vite.config.js
│
├── server/ # Backend (Node + Express)
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── .env
│ └── server.js
│
└── README.md

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
# Clone the repo
git clone https://github.com/ChiragChaudhary01/Track-My-Job

# Go into the project folder
cd <REPO-NAME>
```

2️⃣ Install Dependencies

Frontend

> cd client
> npm install

Backend

> cd ../server
> npm install

Frontend (client/.env):

> VITE_API_URL=http://localhost:5000

Backend (server/.env):

> PORT=5000
> MONGO_URI=your_mongodb_connection_string
> JWT_SECRET=your_secret_key
> EMAIL_USER=your_email@example.com
> EMAIL_PASS=your_email_app_password

4️⃣ Run the Project
Backend

> cd server
> npm start

Frontend

> cd ../client
> npm run dev

| Method | Endpoint             | Description       |
| ------ | -------------------- | ----------------- |
| POST   | `/api/auth/register` | Register new user |
| POST   | `/api/auth/login`    | Login user        |
| GET    | `/api/jobs`          | Get all jobs      |
| POST   | `/api/jobs`          | Add a new job     |
| PUT    | `/api/jobs/:id`      | Update a job      |
| DELETE | `/api/jobs/:id`      | Delete a job      |

🤝 Contributing
Contributions are welcome!

Fork the repository

Clone your fork locally

Create a new branch (git checkout -b feature-branch)

Make your changes

Commit changes (git commit -m "Add feature")

Push to your branch (git push origin feature-branch)

Open a Pull Request

📜 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Chirag Chaudhary
💼 LinkedIn
🐙 GitHub
