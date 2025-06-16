# Under Cover Game - Backend 

**First milestone of the project.**
**Status:** *Work in Progress*

---

## 📖 Description

This is the backend API for the **Under Cover Game** application. It handles user management, game sessions, and data persistence using **MongoDB**.

---

## 🛠️ Technologies

* **Node.js** + **TypeScript**
* **Express.js**
* **MongoDB** (recommended to run via Docker)
* **dotenv** for environment variable management
* **nodemon** for development

---

## ⚙️ Prerequisites

Make sure you have the following installed:

* **Node.js**
* **Docker** (optional, to run MongoDB easily)
* A running **MongoDB** instance (can be via Docker)

---

## 🚀 Getting Started

Follow these steps to set up and run the project:

### 1. Clone the repository

```bash
git clone git@github.com:poropo97/under-cover-game.git
cd under-cover-game
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the root of the backend folder with the following content:

```env
MONGODB_URI=mongodb://localhost:27017/undercover
PORT=4000
```

Adjust `MONGODB_URI` if your MongoDB is running elsewhere.

### 4. Start MongoDB with Docker (optional but recommended)

```bash
docker run -d -p 27017:27017 --name mongodb mongo
```

Or with `docker-compose`:

```bash
docker-compose up -d
```

### 5. Run the backend server

For development with hot reload:

```bash
npm run dev
```

To build and run the production version:

```bash
npm run build
npm start
```

### 6. Access the API

Visit:

```bash
http://localhost:4000
```

---

## 📜 Scripts

* `npm run dev` — Start the server with hot reload (`nodemon + ts-node`)
* `npm run build` — Compile TypeScript to JavaScript
* `npm start` — Run the compiled JavaScript code

---

## 📝 Notes

This project is a **work in progress**. Stay tuned for updates and new features!

Contributions and issues are welcome.

