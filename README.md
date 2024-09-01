# 🚀 Vercel Clone - Host Locally

Welcome to the **Vercel Clone** project! 🌐 This suite of repositories replicates Vercel's functionalities for hosting applications locally, providing a seamless experience for deploying, managing, and scaling your web projects.

This Vercel Clone consists of four key components:

1. **vercel-frontend** 🎨 - The user interface for managing deployments.
2. **vercel-upload** 📤 - Handles file uploads and storage.
3. **vercel-req-handler** 🛠️ - Manages incoming requests and routes them appropriately.
4. **vercel-deploy** 🚧 - Handles deployment operations, ensuring that your code runs smoothly.

Built using **React (Vite)**, **Tailwind CSS**, **Redis**, and **Digital Ocean Volume Storage**, this project aims to bring the power of Vercel’s hosting capabilities to your local environment.

---

## 📁 Repositories Overview

### 1. vercel-frontend 🎨

- **Description:** The frontend interface of the Vercel clone, built with React and styled with Tailwind CSS.
- **Features:** User-friendly UI to view, manage, and deploy projects.
- **Tech Stack:** React (Vite), Tailwind CSS, Axios.

### 2. vercel-upload 📤

- **Description:** Handles file uploads and interacts with Digital Ocean Volume Storage to keep your assets safe.
- **Features:** Secure file upload, management, and retrieval.
- **Tech Stack:** Node.js, Express, Digital Ocean Volume Storage.

### 3. vercel-req-handler 🛠️

- **Description:** The core request handler that routes traffic and manages APIs.
- **Features:** Efficiently handles routing, middleware integration, and API requests.
- **Tech Stack:** Node.js, Express, Redis for caching.

### 4. vercel-deploy 🚧

- **Description:** Manages the deployment pipeline, automating builds and deployments.
- **Features:** Continuous integration and deployment support, real-time build logs.
- **Tech Stack:** Node.js, Docker, Shell scripts.

---

## 🔧 Tech Stack

- **Frontend:** React (Vite) ⚛️
- **Styling:** Tailwind CSS 🎨
- **Backend:** Node.js 🟢, Express 🚀
- **Storage:** Digital Ocean Volume Storage 🗄️
- **Caching:** Redis 📌

---

## 🚀 Getting Started

To get started with the Vercel Clone, follow the steps below:

### Prerequisites

- Node.js (v14.x or higher)
- Redis
- Docker (for deployment module)
- Digital Ocean Volume Storage setup

### Installation

1. **Clone the repositories**

   ```bash
   git clone https://github.com/retr0717/vercel-frontend.git
   git clone https://github.com/retr0717/vercel-upload.git
   git clone https://github.com/retr0717/vercel-req-handler.git
   git clone https://github.com/retr0717/vercel-deploy.git
2. **Install dependencies in each repository**
   
    ```bash
    npm i
3. **Start Dev Server**

    ```bash
    npm run dev  [in vercel-frontend]
    npm start [for the rest of the repos]
