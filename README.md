
# Project Title
### Real-Time Chat Application 

A fully responsive web-based real-time chat app built using HTML, CSS, JavaScript, Node.js, Express, and Socket.IO.


## Technologies Used
### Frontend:
- HTML
- CSS (Responsive Design)
- JavaScript

### Backend:
- Node.js
- Express.js
- Socket.IO
- Moment.js (for timestamp formatting)
## Features

- Real-time messaging using WebSockets
- Create, join, and delete chat rooms
- Display usernames and message timestamps
- Responsive design for mobile and desktop
- Automatically scrolls to new messages
- Separate backend and frontend hosting


## Run Locally

###  How to Run Locally

### Prerequisites:
- Node.js and npm installed

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/AkashManolkar/Chat-App.git
   cd Chat-App
```
npm install

npm start

http://localhost:3000


```

## Deployment


Backend (Render):
Create an account at https://render.com

Click New → Web Service and connect your GitHub repo.

Set:

Build Command: npm install

Start Command: node server.js

Deploy and copy the backend URL.

Frontend (GitHub Pages):
Copy files from public/ to the root of a new GitHub repo.

Update index.html:

```
<script src="https://your-backend.onrender.com/socket.io/socket.io.js"></script>
```
Update script.js:

```
const socket = io("https://your-backend.onrender.com");
```
Enable GitHub Pages in your repo settings.


##  To-Do / Future Enhancements
Add authentication (login/password)

Store chat history with MongoDB

Add emojis and message reactions

Support private messaging (DMs)
### Author


Name: Akash Manolkar

GitHub: - [AkashManolkar](https://github.com/AkashManolkar)

Email: akashmanolkar85@example.com

