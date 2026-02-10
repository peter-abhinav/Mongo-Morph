# DO RESEARCH AND DO CHANGES OR DELETE THIS REPO

## Mongo Morph 🧬

**Mongo Morph** is a **template repository** built for rapid backend development using **TypeScript + Node.js**. It includes a basic user authentication system with signup, login, and fetch-all-users functionality.

## 🛠 Features

* ⚡ **TypeScript + Node.js** boilerplate
* 🔐 **Basic Authentication APIs** (Signup, Login, Get Users)
* ✅ **Pre-configured `tsconfig.json`** with sensible defaults
* 🎯 **ESLint & Prettier** integration (optional)
* 📦 **Pre-configured `package.json`** for quick dependency setup

---

## 🔐 API Routes

```ts
POST   /api/signup    # Register a new user
POST   /api/login     # Authenticate and receive a token
GET    /api/users     # Fetch all registered users
```

> Note: Auth middleware and protected routes are scaffolded but not enabled yet.

---

### 🔑 Generate a 32-Character JWT Secret

Use the following command to generate a **secure 32-character JWT secret**:

```bash
openssl rand -base64 32
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/Hello-Ship-Code/Mongo-Morph
cd Mongo-Morph
```

### 2️⃣ Initialize TypeScript

```sh
tsc --init
```

### 3️⃣ Install Dependencies

```sh
npm install
```

### 4️⃣ Run the Project

```sh
npx ts-node src/index.ts
```

---

## 📂 Folder Structure

```c
Mongo-Morph/
│── src/
│   ├── index.ts               # App entry point
│   ├── controllers/
│   │   ├── api/
│   │   │   ├── login-controller.ts
│   │   │   ├── signup-controller.ts
│   │   │   └── users-controllers.ts
│   ├── routes/
│   │   └── app-router.ts      # API routes setup
│── package.json
│── tsconfig.json
│── .gitignore
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## **Build fast. Stay simple. Welcome to Mongo Morph! 🚀**
