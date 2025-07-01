# eBook Store - React

![Screenshot 2024-09-03 at 19 04 34](https://github.com/user-attachments/assets/a1701da8-19dc-4493-b02d-f2cb4e37feea) ![Screenshot 2024-09-03 at 19 04 50](https://github.com/user-attachments/assets/580eb690-e02b-4123-be4f-7c6b82bb4985) ![Screenshot 2024-09-03 at 19 05 04](https://github.com/user-attachments/assets/695f1bd5-3d8f-4049-9a11-f3f3a7805fda) ![Screenshot 2024-09-03 at 19 05 24](https://github.com/user-attachments/assets/25cf13dc-84c3-46f7-a9f9-9449da72123a) ![Screenshot 2024-09-03 at 19 06 17](https://github.com/user-attachments/assets/f35ea3d3-43ba-4114-8508-fb6509af8232) ![Screenshot 2024-09-03 at 19 07 19](https://github.com/user-attachments/assets/b8d5f055-7719-47d7-901c-f86b7b7f78f5) ![Screenshot 2024-09-03 at 19 07 42](https://github.com/user-attachments/assets/64583a22-c1b6-42e3-b459-d9c95002b2af) ![Screenshot 2024-09-03 at 19 07 52](https://github.com/user-attachments/assets/8772d23c-f95f-454d-957f-16d98936cf32) ![Screenshot 2024-09-03 at 19 08 45](https://github.com/user-attachments/assets/5e1a348b-f873-463d-9e8c-27e4f1e12aff) ![Screenshot 2024-09-03 at 19 09 19](https://github.com/user-attachments/assets/2dafa0c2-451a-4333-99a8-0167d9493df4) ![Screenshot 2024-09-03 at 19 09 29](https://github.com/user-attachments/assets/7a565cef-3caf-4295-b1b0-b3cc35086276) ![Screenshot 2024-09-03 at 19 09 43](https://github.com/user-attachments/assets/26854077-9177-40c6-9337-3bb3ec0ebd19) ![Screenshot 2024-09-03 at 19 10 10](https://github.com/user-attachments/assets/006d3b5b-a967-4dd6-9dee-2bf662c4d6c2) ![Screenshot 2024-09-03 at 19 04 12](https://github.com/user-attachments/assets/fbfa7567-799e-4415-b37d-0a82fa96fbc7)

---

## Project Summary

**eBookStore--React** is a full-featured E-Commerce web application built with React. Designed for ordering codebooks, it demonstrates modern web development with a robust, global state-managed frontend and a mock backend. The project is ideal for learning full-stack concepts, React best practices, and real-world deployment (Netlify & Render). It showcases advanced routing, authentication, CRUD operations, and seamless integration between frontend and backend.

## Demo Links

- **Frontend Live:** [https://ebookstore-arnob.netlify.app](https://ebookstore-arnob.netlify.app)
- **Backend Live:** [https://codebook-mock-server-j8n3.onrender.com](https://codebook-mock-server-j8n3.onrender.com)
- **Backend Source:** [eBookStore-Mock-Server Repo](https://github.com/arnobt78/eBookStore-Mock-Server)

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Demo Links](#demo-links)
4. [Project Structure](#project-structure)
5. [Technology Stack](#technology-stack)
6. [Installation & Setup](#installation--setup)
    - [Prerequisites](#prerequisites)
    - [Frontend Setup](#frontend-setup)
    - [Backend Setup](#backend-setup)
    - [Environment Variables](#environment-variables)
7. [Available Scripts](#available-scripts)
8. [Deployment](#deployment)
    - [Netlify (Frontend)](#netlify-frontend)
    - [Render (Backend)](#render-backend)
9. [API & Routing](#api--routing)
10. [Component & Feature Walkthrough](#component--feature-walkthrough)
11. [Learning Resources](#learning-resources)
12. [Example Usage](#example-usage)
13. [Keywords](#keywords)
14. [Conclusion](#conclusion)

---

## Project Overview

eBookStore--React is a demonstration of a scalable and modular React E-Commerce site. Users can browse, search, and order codebooks, register/login (with JWT-based authentication), and manage their cart—all with persistent state. The backend is a mock server (JSON Server + Auth), making the project easy to run locally without extra setup.

- **Frontend:** React (with global state)
- **Backend:** JSON Server + JSON Server Auth (mock REST API)
- **Deployment:** Netlify (Frontend), Render (Backend)

---

## Key Features

- 💡 **Modern React with Hooks & Context API**
- 🛒 **Shopping Cart Functionality**
- 🔑 **User Authentication (JWT)**
- 🔄 **RESTful API Integration**
- 🔗 **React Router v6 for Navigation**
- 🌐 **Responsive UI with Tailwind CSS**
- 🚀 **Deployed & Production-Ready Workflow**
- 🧪 **Testing Setup**
- ⚙️ **Environment Variables for Security**
- 📝 **Example Scripts & Learning Resources**

---

## Project Structure

```
eBookStore--React/
├── data/                  # Mock database & routes config
│   ├── db.json
│   └── routes.json
├── public/                # Static assets and index.html
├── src/                   # Main React source code
│   ├── components/        # Reusable and page components
│   ├── context/           # Global state (Context API, Providers)
│   ├── hooks/             # Custom React hooks
│   ├── pages/             # Page-level components
│   ├── styles/            # Tailwind / CSS styles
│   ├── utils/             # Utility functions (API, helpers)
│   ├── App.js             # Root component & routing
│   ├── index.js           # Entry point
│   └── ...other files
├── .env                   # Environment variables (not committed)
├── package.json           # Project metadata & dependencies
├── tailwind.config.js     # Tailwind CSS config
├── netlify.toml           # Netlify deployment config
└── README.md              # Documentation (this file)
```

---

## Technology Stack

- **Frontend:** React, React Router, Context API, Tailwind CSS
- **Backend:** JSON Server, JSON Server Auth (Mock REST API)
- **Testing:** React Testing Library, Jest
- **Deployment:** Netlify (Frontend), Render (Backend)
- **Utilities:** dotenv, JWT, Axios/Fetch

---

## Installation & Setup

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v14+ recommended)
- npm (comes with Node.js)

---

### Frontend Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/arnobt78/eBookStore--React.git
    cd eBookStore--React
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Install React Router:**
    ```bash
    npm install react-router-dom
    ```

---

### Backend Setup

1. **Install JSON Server and Auth:**
    ```bash
    npm install -D json-server json-server-auth
    ```

2. **Run JSON Server:**
    ```bash
    npx json-server data/db.json
    ```

3. **Run Auth Server (in a second terminal):**
    ```bash
    npx json-server data/db.json -m ./node_modules/json-server-auth -r data/routes.json --port 8000
    ```

   > The React app runs on port 3000. The backend (mock server) runs on port 8000.

---

### Environment Variables

Create a `.env` file in your root project directory:

```
REACT_APP_HOST=http://localhost:8000
REACT_APP_GUEST_LOGIN=arnob@example.com
REACT_APP_GUEST_PASSWORD=learnreact
```

---

## Available Scripts

Within the project directory, you can run:

- **Start Development Server**
    ```bash
    npm start
    ```
    Open [http://localhost:3000](http://localhost:3000) in your browser.

- **Run Tests**
    ```bash
    npm test
    ```
    Launches the test runner in interactive mode.

- **Build for Production**
    ```bash
    npm run build
    ```

- **Eject Configuration** (irreversible)
    ```bash
    npm run eject
    ```

---

## Deployment

### Netlify (Frontend)

1. Login at [Netlify](https://app.netlify.com/).
2. Import project from GitHub.
3. Configure environment variables (`Site settings > Build & deploy > Environment > Environment variables`).
4. Deploy site.
5. For 404 issues, see:
   - [Netlify React Router 404 Fix 1](https://stackoverflow.com/questions/58065603/netlify-renders-404-on-page-refresh-using-react-and-react-router)
   - [Netlify Redirects Docs](https://www.netlify.com/blog/2019/01/16/redirect-rules-for-all-how-to-configure-redirects-for-your-static-site/)

---

### Render (Backend)

1. Login at [Render](https://render.com/).
2. Create a new Web Service, select your backend repo.
3. Deploy.
4. For deployment errors, check logs and push fixes to `main` branch.

---

## API & Routing

- **Backend REST API** (mocked with JSON Server + Auth)
    - `/books` — Fetch all books
    - `/cart` — Get/add/remove items in cart
    - `/users` — User registration/login (JWT)
    - **Custom routes** configured in `data/routes.json`
- **Frontend Routing** (React Router)
    - `/` — Home
    - `/login` — Login
    - `/register` — Signup
    - `/books` — Book listing
    - `/cart` — Shopping cart
    - `/profile` — User profile
    - ...and more

---

## Component & Feature Walkthrough

- **Global State Management:** Uses React's Context API for cart and auth state.
- **Authentication:** JWT-based, login/register with protected routes.
- **Cart:** Add/remove books, persistent across sessions.
- **Book CRUD:** List, add, and remove books via API.
- **Responsive UI:** Tailwind CSS for modern design.
- **Custom Hooks:** For API calls and state logic.
- **API Layer:** Centralized utility for all server interactions.
- **Error Handling:** Graceful fallbacks for failed requests.
- **Testing:** Ready for expansion with React Testing Library.

---

## Learning Resources

- [Create React App Docs](https://facebook.github.io/create-react-app/docs/getting-started)
- [React Documentation](https://reactjs.org/)
- [React Router](https://reactrouter.com/en/main)
- [JSON Server](https://www.npmjs.com/package/json-server)
- [JSON Server Auth](https://www.npmjs.com/package/json-server-auth)
- [JWT Debugger](https://jwt.io/#debugger-io)
- [Netlify Docs](https://docs.netlify.com/)
- [Render Docs](https://render.com/docs)

---

## Example Usage

**Sample API Call:**

```js
// src/utils/api.js
export async function loginUser(email, password) {
  const response = await fetch(`${process.env.REACT_APP_HOST}/login`, {
    method: 'POST',
    headers: {'Content-Type': 'application/json'},
    body: JSON.stringify({ email, password })
  });
  return response.json();
}
```

**Sample Route:**

```jsx
// src/App.js
import { BrowserRouter, Routes, Route } from 'react-router-dom';
import Home from './pages/Home';
import Login from './pages/Login';

function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/login" element={<Login />} />
        {/* ...other routes */}
      </Routes>
    </BrowserRouter>
  );
}
```

---

## Keywords

`React`, `E-Commerce`, `Mock Server`, `JWT Auth`, `React Router`, `Tailwind CSS`, `Full Stack`, `Netlify`, `Render`, `Learning Project`, `REST API`, `Codebooks`, `Global State`, `Context API`

---

## Conclusion

**eBookStore--React** is not just a project—it's a learning journey. This repository combines real-world tech stacks, best practices, and deployment workflows, making it perfect for both beginners and intermediate developers keen to master modern React and full-stack development. Fork, clone, and start coding!

---

## Happy Coding! 🚀

Thank you for using and learning from this project. If you have questions or suggestions, feel free to open an issue or pull request.

---
