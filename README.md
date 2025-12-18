# 💬 Chat App: Socket Programming & System Integration

A real-time communication platform built to demonstrate **Socket Programming**, **TCP/UDP protocols**, and **Full-Stack Integration**.
This project serves as a practical implementation of the **Advanced Java Programming (21IPE336T)** syllabus.

## 📖 Academic Context
This project implements core concepts from the following units of the Advanced Java curriculum:
* **Unit 1 & 2: Data Handling** – Utilizing JSON for message exchange and Regex for input validation.
* **Unit 5: System Integration** – Practical application of machine-to-machine communication over a network using Web Services and Sockets.

---

## 🛠️ Tech Stack
* **Backend:** Node.js with `Express.js` and `Socket.io` for real-time bi-directional communication (via `server.js`).
* **Frontend:** HTML5, JavaScript, and **Tailwind CSS** for a responsive chat interface.
* **Networking:** Implementation of TCP/UDP port logic for stable and fast data transmission.
* **Deployment:** Optimized for **Vercel**.

---

## 🚀 Key Features
* **Real-time Messaging:** Low-latency communication using Sockets.
* *Protocol Flexibility:** Demonstrates the difference between TCP (reliable) and UDP (fast) communication styles.
* **Secure Validation:** Uses Regular Expressions to validate user credentials and room IDs before connection.
* **Microservice Ready:** Designed with a decoupled architecture, making it easy to transition into a Microservices environment.



---

## 📂 Repository Structure
* `server.js`: The core engine handling socket connections and port listening.
* `package.json`: Manages dependencies like Express and Socket libraries.
* `tailwind.config.js`: Custom styling configurations for the chat UI.
* `.gitignore`: Ensures environment files and `node_modules` remain private.

---

## ⚙️ Setup & Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/Chat-App-Using-Socket.git](https://github.com/your-username/Chat-App-Using-Socket.git)
    ```
2.  **Install Dependencies:**
    ```bash
    npm install
    ```
3.  **Start the Server:**
    ```bash
    npm start
    ```
    *The app will run by default on port 8080 (or as configured in your environment).*

---

## 🎓 Exam-Specific Concepts Implemented
* **Socket Communication:** Facilitating machine-to-machine interaction.
* **HTTP Status Handling:** Integrated error handling for 404 (Not Found) and 500 (Server Error) responses.
* **Data Binding:** Real-time UI updates similar to AngularJS two-way binding principles.

---
*Developed as part of the Advanced Java Programming (21IPE336T) Lab requirements.* 

