# ExpressChats 💬

A simple full-stack chat message manager inspired by WhatsApp, built using **Node.js**, **Express.js**, **MongoDB**, and **EJS**. It supports creating, viewing, editing, and deleting chat messages in a user-friendly interface.

## 🚀 Features

- Create and display chat messages between users
- Edit or delete any message using method override
- MongoDB used for storing chats with timestamps
- EJS templating for dynamic frontend rendering
- Basic CSS for UI styling

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, HTML, CSS
- **Database:** MongoDB (via Mongoose)
- **Middleware:** method-override

## 📂 Folder Structure

```
.
├── init.js              # Seeds initial chat data
├── index.js             # Main server file with Express routes
├── chat.js              # Mongoose schema
├── public/
│   └── style.css        # Styling for chat UI
├── views/
│   ├── index.ejs        # Home page showing all chats
│   ├── new.ejs          # New chat form
│   ├── edit.ejs         # Edit chat form
└── README.md            # You're here!
```

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/expresschats.git
   cd expresschats
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Make sure MongoDB is running locally:
   ```bash
   mongod
   ```

4. Seed the database:
   ```bash
   node init.js
   ```

5. Start the server:
   ```bash
   node index.js
   ```

6. Visit [http://localhost:8080/chats](http://localhost:8080/chats) in your browser.

## ✍️ Author

**Vaibhav Prasad**  
B.Tech CSE | Bharati Vidyapeeth College of Engineering, Pune
