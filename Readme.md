# 🌐 Blogify – A Full-Stack Blogging Platform

Blogify is a full-featured blogging web application built using the **MERN (without React)** stack. It allows users to sign up, sign in, create blog posts with image uploads, and view their personalized content securely.

---

## 🚀 Features

- 🧑‍💻 User authentication with secure JWT-based session handling
- ✍️ Create, read, and view blog posts with cover image support
- 📸 Image uploads handled with Multer and stored locally
- 🧭 Dynamic UI rendering based on user login state
- 📚 Clean MVC architecture with EJS templating
- 🎨 Responsive Bootstrap 5 UI

---

## 🛠️ Tech Stack

| Layer          | Technology                          |
| -------------- | ----------------------------------- |
| Backend        | Node.js, Express.js                 |
| Frontend       | EJS (Embedded JavaScript) templates |
| Database       | MongoDB with Mongoose ODM           |
| Authentication | JWT (JSON Web Tokens) via cookies   |
| File Uploads   | Multer                              |
| Styling        | Bootstrap 5                         |

---

## 📂 Folder Structure

```
Blog-App/
├── middlewares/              # Custom Express middlewares
│   └── authentication.js     # JWT authentication logic
├── models/                   # Mongoose schema models
│   ├── blog.js               # Blog schema
│   ├── comments.js           # Comment schema (optional)
│   └── user.js               # User schema
├── node_modules/             # Installed dependencies
├── public/                   # Static assets
│   ├── images/               # Placeholder/static images
│   └── uploads/              # Uploaded blog cover images
├── routes/                   # Express route handlers
│   ├── blog.js               # Blog-related routes
│   └── user.js               # User routes (signup/signin/logout)
├── services/                 # Logic services
│   └── authentication.js     # Token generation/validation
├── views/                    # EJS templates
│   ├── partials/             # Reusable partial templates
│   │   ├── head.ejs
│   │   ├── nav.ejs
│   │   └── scripts.ejs
│   ├── addBlog.ejs           # Add new blog form
│   ├── blog.ejs              # Blog detail view
│   ├── home.ejs              # Home page with all blogs
│   ├── signin.ejs            # Login page
│   └── signup.ejs            # Register page
├── index.js                  # Main Express app
├── package.json              # Project dependencies
├── package-lock.json         # Locked versions of dependencies
└── README.md                 # Project documentation
```

## 🛠️ Installation & Setup

To run this project locally, follow these steps:

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/blogify.git
   cd blogify

   ```

2. **Install all Dependencies**

npm install

3. **Ensure MongoDB is running locally**

By default, the app connects to:
mongodb://localhost:27017/blogify

4. **Start the development server**
   npm run dev

5. **Visit the app in your browser**

http://localhost:8000
