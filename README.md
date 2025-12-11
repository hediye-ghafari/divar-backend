# rjs-divar-api

🚀 Backend API – Divar Authentication & Admin System

This repository contains the backend of the Divar-style authentication project.
The backend was originally implemented by another developer, and this repository is included only to provide full transparency and show the complete environment that the frontend interacts with.

📌 About This Backend

Although the backend was not developed by me, the following features are available and fully functional:

🔑 Authentication System
Mobile-based OTP login
OTP generation using Node.js crypto
OTP expiration handling
Access & refresh token generation (JWT)
Token validation middleware

🧱 Admin Panel Support (Used in Frontend)

The backend includes a full CRUD system for Options, which are used within categories in the admin section:

Method Endpoint Description
POST /option Create a new option
GET /option Get all options
GET /option/:id Get a specific option by ID
PUT /option/:id Update an existing option
DELETE /option/:id Delete an option

These APIs are integrated inside the admin panel in the frontend.

📁 Tech Stack
Backend Technologies
Node.js
Express.js
MongoDB / Mongoose
JWT (Access & Refresh Tokens)
dotenv
Crypto
Modular API architecture

👤 My Role in This Backend

Only integration and usage — not development.
I worked with the backend as follows:
Integrated all backend APIs inside the frontend
Implemented OTP login flow on the client-side
Implemented admin access logic (demo mode)
Built the full CRUD UI for Options using these APIs
Managed tokens, cookies, validation, and error handling on the frontend
Collaborated with an existing backend codebase (important experience)
This repo exists for:
Reviewing backend structure
Understanding API communication
Maintaining transparency for portfolio reviewers
