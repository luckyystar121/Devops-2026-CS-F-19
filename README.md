# CampusCart

## Overview

CampusCart is a student-focused marketplace designed to make buying and selling within a college community easier. <br><br> Students often rely on WhatsApp groups, Instagram pages, or word of mouth to sell old  items, which can make it difficult to find the right thing at the right time. <br><br>CampusCart brings these listings into one place so students can browse, post, and manage items more conveniently.

## Tech Stack

The project is divided into two main parts: client and server. <br>
The client contains everything related to the frontend and what the user sees and interacts with. <br> <br>
**Frontend:** React.js, JavaScript, HTML, CSS <br>

The server handles the backend side of the application. It manages the API routes, business logic, authentication, database operations, and communication with external services.<br> <br>
**Backend:** Node.js, Express.js <br>
**Database:** MongoDB <br>
**Authentication:** JWT <br>
**Cloud Services:** Cloudinary <br>
**Development & Collaboration:** Git, GitHub, VS Code <br>

Keeping the client and server separate makes the project easier to develop, maintain, and update as the application grows.

## Structure And Getting started

```bash
CampusCart/
│
├── client/              # Frontend application
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── assets/
│   │   └── ...
│   ├── public/
│   └── package.json
│
├── server/              # Backend application
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   └── server.js
│
├── README.md
└── package.json
```

Clone the repository and move into the project folder:
```
git clone https://github.com/shreyasaxena121/Devops-2026-CS-F-19.git
cd Devops-2026-CS-F-19
```

The backend requires environment variables for things such as the MongoDB connection, JWT secret, Cloudinary configuration, and other API keys used by the application. 
<br> Create a .env file inside the server folder and add the required values.
<br>Once everything is configured, start the backend:
```
cd server
npm run dev
```
Then open another terminal, start the frontend, and visit the local URL shown by Vite:
```
cd client
npm run dev
```
  
## Future Scope

We could add features such as <br>
in-app messaging between buyers and sellers <br>
better search and filtering, ratings and reviews<br>
item recommendations, auction functionality, and stronger verification using college IDs.<br>
The platform could also be expanded to support multiple colleges, making it possible for students from different campuses to use the same marketplace.
