# Dev-Log

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Dev-Log** is a full-stack web-based social media application that allows authenticated users to create and view posts. It demonstrates user authentication, persistent storage, and server-side API design using Node.js and Express. Additional interaction features like post reactions, chat, and user profile dashboard are planned for future releases.

---

## 📌 Table of Contents

- [About](#about)  
- [Features](#features)  
- [Demo / Screenshots](#demo--screenshots)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Database](#database)  
- [Contributing](#contributing)  
- [Future Enhancements](#future-enhancements)  
- [License](#license)

---

## 📍 About

Dev-Log is designed as a social logging platform where users can:

- Register and log in  
- Create, view, and delete posts  
- Persist content with a server database  
- (Future) Interact with others via chat, likes, and comments

This project provides hands-on experience with full-stack HTTP API design, routing, and persistent data storage. 

---

## ✨ Features

- Authentication (sign up / log in / session management)  
- Create and view posts  
- Server-side routing with Express  
- Data persistence with SQLite  
- Modular file structure for separation of concerns

---

## 📸 Demo / Screenshots

<img width="708" height="430.5" alt="image" src="https://github.com/user-attachments/assets/8cd2012a-3182-48bc-8ffd-705245c47e28" />

<img width="708" height="430.5" alt="image" src="https://github.com/user-attachments/assets/de8b8ab3-b809-4770-9081-cbaad6a5047c" />


---

## 🧱 Tech Stack

**Backend**  
- Node.js  
- Express.js  

**Templating**  
- EJS (Embedded JavaScript Templates)

**Database**  
- SQLite (development database)

**Other Tools**
- npm (package management)

> This combination enables a lightweight full-stack application that handles routing, dynamic rendering, and persistent storage. 

---

## 🛠 Installation

Follow these steps to run the project locally:

1. **Clone the repository**
    ```bash
    git clone https://github.com/SammamAhmed/Dev-Log.git
    ```
2. **Install dependencies**
    ```bash
    cd Dev-Log
    npm install
    ```
3. **Create and configure environment**
    - If using environment variables (sessions, database path), add a `.env` file:
      ```
      JWTSECRET=your_secret_key_here
      ```
4. **Start the server**
    ```bash
    npm start
    ```

5. Open your browser and go to:
    ```
    http://localhost:3000
    ```

---

## ▶️ Usage

- Register or log in using the provided forms  
- Create a post with text content  
- Browse existing posts on the feed  
- (Eventual) Interact with posts or other users

---

## 🗄 Database

This project uses **SQLite** as a lightweight server-side database suitable for development workflows.

- Database file: `devlog.db`
- Tables: users, posts (as defined in project migrations/creation scripts)

If you add migrations in the future, include instructions here.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repo  
2. Create your feature branch  
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes  
4. Push to your branch  
5. Open a pull request

Please include descriptive commit messages and test any features before submitting. :contentReference[oaicite:3]{index=3}

---

## 🚀 Future Enhancements

- Post interactions (likes, comments)  
- Real-time chat with WebSockets  
- User profile dashboard  
- Pagination for feeds  
- Deployment to a cloud provider

Feel free to open issues for feature requests or bugs.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

