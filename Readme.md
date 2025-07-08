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
├── middlewares/ # Custom Express middlewares
│ └── authentication.js # JWT authentication middleware
├── models/ # Mongoose schema models
│ ├── blog.js # Blog schema
│ ├── comments.js # Comment schema
│ └── user.js # User schema
├── node_modules/ # Installed dependencies
├── public/ # Public assets
│ ├── images/ # (Unused / can be used for static images)
│ └── uploads/ # Uploaded blog cover images
├── routes/ # Express route handlers
│ ├── blog.js # Blog-related routes
│ └── user.js # User authentication routes
├── services/ # Logic services
│ └── authentication.js # Token creation/validation logic
├── views/ # EJS templates
│ ├── partials/ # Reusable EJS components
│ │ ├── head.ejs # HTML tag contents
│ │ ├── nav.ejs # Navbar
│ │ └── scripts.ejs # Scripts included at bottom
│ ├── addBlog.ejs # Page for adding a blog
│ ├── blog.ejs # Blog detail view
│ ├── home.ejs # Homepage with all blogs
│ ├── signin.ejs # Login page
│ └── signup.ejs # Register page
├── index.js # Main Express app entry point
├── package.json # Project dependencies and scripts
├── package-lock.json # Exact versions of installed packages
└── README.md # Project overview and instructions
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
