# 🩸 LifeConnect

LifeConnect is a full-stack Blood Donation Platform that connects blood donors with recipients in real time. The platform enables users to register as donors or recipients, search for blood donors by location and blood group, and communicate through an integrated chat system.

---

# ✨ Features

### 👤 Authentication
- User Registration & Login
- JWT Authentication
- Password Encryption using bcrypt
- Protected Routes

### 🩸 Blood Donation
- Register as Blood Donor
- Request Blood
- Search Donors by
  - Blood Group
  - City
  - State
- View Donor Profiles

### 💬 Real-Time Chat
- One-to-One Messaging
- Socket.IO Integration
- Online User Status
- Message History
- Automatic Message Expiry

### 🔔 Notifications
- Unread Message Count
- Real-Time Notifications

### 📊 Dashboard
- User Profile
- Donor Information
- Recipient Requests
- Chat List

---

# 🛠 Tech Stack

## Frontend

- React.js
- Material UI
- Axios
- React Router
- React Toastify
- Socket.IO Client

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Joi Validation
- Socket.IO

## Database

- MongoDB Atlas

## Deployment

- Frontend → Vercel
- Backend → Render

---

# 📂 Project Structure

```
LifeConnect
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── socket
│   ├── utils
│   └── server.js
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   ├── hooks
│   │   ├── services
│   │   └── App.js
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/shreyanshshardul/LifeConnect.git
```

```bash
cd LifeConnect
```

---

## Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file.

```env
PORT=5000

MONGO_URI=Your MongoDB URI

JWT_SECRET=Your Secret Key

CLIENT_URL=http://localhost:3000
```

Run Backend

```bash
npm start
```

---

## Frontend Setup

```bash
cd frontend

npm install
```

Create `.env`

```env
REACT_APP_BACKEND_LINK=http://localhost:5000
```

Run

```bash
npm start
```

---

# 🔑 Environment Variables

Backend

```env
PORT=

MONGO_URI=

JWT_SECRET=

CLIENT_URL=
```

Frontend

```env
REACT_APP_BACKEND_LINK=
```

---

# 📡 API Endpoints

## Authentication

```
POST /api/auth/signup

POST /api/auth/login
```

## User

```
GET /api/user/profile

PUT /api/user/update
```

## Donor

```
GET /api/donor

POST /api/donor/register

GET /api/donor/:id
```

## Chat

```
POST /api/chat/sendmsg

GET /api/chat/getmsg/:userId

GET /api/chat/allchat
```

---

# 🔒 Security

- JWT Authentication
- Password Hashing (bcrypt)
- Input Validation (Joi)
- CORS Protection
- Environment Variables
- Protected Routes

---

# 📸 Screenshots

Add screenshots here.

```
Home Page

Login

Dashboard

Donor Search

Chat
```

---

# 📈 Future Improvements

- Blood Request Notifications
- AI Blood Availability Prediction
- Nearby Donor Detection
- Hospital Integration
- Email Notifications
- SMS Alerts
- Video Calling
- Admin Panel
- Donation History
- Medical Verification

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Shreyansh Shardul**

- GitHub: https://github.com/shreyanshshardul
- LinkedIn: https://www.linkedin.com/in/shreyansh-shardul/

---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub. It motivates me to build more open-source projects!
