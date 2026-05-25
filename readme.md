# 📚 Book API

A simple REST API for managing books using `json-server`.

---

## 🚀 Live API

🔗 https://book-api-1-b2dc.onrender.com/

---

## 📦 GitHub Repository

🔗 https://github.com/HASANCoU/book-api

---

## 🛠️ Technologies Used

- Node.js
- JSON Server
- REST API
- Render Deployment

---

## 📂 Project Structure

```bash
book-api/
│── db.json
│── package.json
│── package-lock.json
│── README.md
│── public/
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/HASANCoU/book-api.git
```

Move into the project directory:

```bash
cd book-api
```

Install dependencies:

```bash
npm install
```

---

## ▶️ Run the Project Locally

```bash
npm run server
```

Local server will run at:

```bash
http://localhost:3004
```

---

## 📖 API Endpoints

### 🔹 Get All Books

```http
GET /books
```

Example:

```bash
https://book-api-1-b2dc.onrender.com/books
```

---

### 🔹 Get Single Book

```http
GET /books/:id
```

Example:

```bash
https://book-api-1-b2dc.onrender.com/books/1
```

---

### 🔹 Add New Book

```http
POST /books
```

Sample Request Body:

```json
{
  "title": "Atomic Habits",
  "author": "James Clear",
  "price": 450
}
```

---

### 🔹 Update Book

```http
PUT /books/:id
```

---

### 🔹 Delete Book

```http
DELETE /books/:id
```

---

## 📜 Available Scripts

```json
"scripts": {
  "server": "json-server --watch db.json --port 3004 --host 0.0.0.0"
}
```

---

## 🌐 Deployment

This project is deployed using Render.

---

## 👨‍💻 Author

### Md. Mehedi Hasan

GitHub Profile:  
https://github.com/HASANCoU

---

## 📄 License

This project is licensed under the MIT License.