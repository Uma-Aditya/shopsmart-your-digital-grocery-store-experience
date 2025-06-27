# 🛒 Shopez E-Commerce MERN

Shopez is a full-stack E-Commerce web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This project includes both user and admin dashboards, product listing, cart functionality, and order management.

---

## 🎥 Video Demo

▶️ [Watch Demo on Google Drive](https://drive.google.com/file/d/19TIBzTza5mqvQqxUaAJXcldrt9jD-Qcf/view?usp=drive_link)

---

## 📄 Full Documentation

📘 [View Full Project Documentation](https://docs.google.com/document/d/1msB2N33dqSA7NrtTNJzwArgweQCdu3ai/edit?usp=drive_link&ouid=104024728896694154293&rtpof=true&sd=true)

---

## 📌 Features

### 👤 User Panel
- User registration & login
- Browse products
- View product details
- Add to cart and checkout
- View past orders

### 🛠 Admin Panel
- Admin login
- Manage products (CRUD)
- View and manage orders
- Manage registered users

---

## 📁 Project Structure

```
Shopez-E-Commerce-MERN/
│
├── client/                  # React Frontend
│   ├── public/
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Page-level React components
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│
├── server/                  # Node + Express Backend
│   ├── config/              # DB connection
│   ├── controllers/         # Request handling logic
│   ├── middleware/          # Authentication, etc.
│   ├── models/              # Mongoose schemas
│   ├── routes/              # REST API endpoints
│   ├── seed.js              # Sample data population
│   ├── server.js
│   └── package.json
│
├── README.md
├── .gitignore
└── Document/               # Additional files (if any)
```

---

## 🧑‍💻 Technologies Used

| Frontend         | Backend        | Database | Tools         |
|------------------|----------------|----------|----------------|
| React.js         | Node.js        | MongoDB  | Git & GitHub   |
| React Router     | Express.js     | Mongoose | Postman        |
| Axios            | JWT Auth       |          | Google Drive   |

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Shopez-E-Commerce-MERN.git
   cd Shopez-E-Commerce-MERN
   ```

2. **Install client dependencies**
   ```bash
   cd client
   npm install
   ```

3. **Install server dependencies**
   ```bash
   cd ../server
   npm install
   ```

4. **Set up environment variables**  
   Create a `.env` file in the `/server` directory:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the app**
   ```bash
   # In client/
   npm start

   # In server/
   npm run dev
   ```

---

## 🧪 Sample Admin & User Credentials (Optional)

> You can use `seed.js` to populate your database with default admin and product data.

---

## 🙌 Contributing

Pull requests are welcome! If you find a bug or want to suggest an enhancement, please open an issue or PR.

---

## 📬 Contact

For questions or collaborations:

**Author**: UMA ADITYA 
📧 Email: mohanaditya706@gmail.com 


---

## 📌 License

This project is licensed under the MIT License.



