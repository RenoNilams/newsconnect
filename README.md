# 📰 News Connect: Real-Time Aggregator & Secure Chat

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

## 📌 Overview

**News Connect** is a robust full-stack web application that merges information consumption with social interaction. Developed using the **MVC (Model-View-Controller)** architecture, it pulls structured news data from various national APIs and integrates a secure, real-time messaging room for registered users.

<div align="center">
  <img src="newsconnect.png" alt="News Connect Showcase" width="100%">
</div>

## 🚀 Backend & Security Architecture

*   **REST API Integration:** Utilizes `axios` and `Promise.all` for parallel, asynchronous fetching of live news data from multiple external endpoints.
*   **Enterprise-Grade Security:** Implements **bcrypt.js** for password hashing and **JSON Web Tokens (JWT)** for stateless, secure session authorization.
*   **Real-Time Communication:** Features an instant messaging system optimized for low latency and auto-reconnection handling.
*   **Dynamic Data Filtering:** Allows users to filter aggregated feeds by specific publishers (e.g., CNN, Antara) and categories.

## 💻 Tech Stack
*   **Runtime & Framework:** Node.js, Express.js
*   **Database:** MongoDB, Mongoose ODM
*   **Security:** JWT, bcryptjs
*   **Frontend:** EJS (Embedded JavaScript templating), Vanilla CSS3
