# 📝 BlogWrite

A modern blog application built with **React.js**, **Redux Toolkit**, and **Appwrite** that allows users to create, edit, manage, and read blog posts. The application provides secure authentication, rich text editing, and a responsive user interface.

---

## 🚀 Features

- 🔐 User Authentication (Sign Up, Login, Logout)
- ✍️ Create, Edit, and Delete Blog Posts
- 📖 View All Published Posts
- 🖼️ Upload Featured Images
- 📝 Rich Text Editor using TinyMCE
- 🔒 Protected Routes for Authenticated Users
- 📱 Responsive UI with Tailwind CSS
- ⚡ State Management using Redux Toolkit

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- React Router DOM
- Tailwind CSS
- React Hook Form
- TinyMCE

### Backend / BaaS
- Appwrite
  - Authentication
  - Database
  - Storage

### Tools
- Vite
- Git & GitHub

---

## 📂 Project Structure

```
BlogWrite/
│── public/
│── src/
│   ├── appwrite/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── store/
│   ├── conf/
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/vikalp9236/Blog-Write.git
```

### Navigate to the project

```bash
cd Blogwrite
```

### Install dependencies

```bash
npm install
```

### Create a `.env` file

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
VITE_APPWRITE_BUCKET_ID=
VITE_TINYMCE_API_KEY=
```

Fill these values with your Appwrite project credentials.

---

### Start the development server

```bash
npm run dev
```

The application will run at

```
http://localhost:5173
```

---

## 📸 Screenshots

Add screenshots here.

Example:

```
screenshots/
    home.png
    login.png
    add-post.png
    post-details.png
```

---

## 📚 What I Learned

- Building React applications using functional components
- State management with Redux Toolkit
- Client-side routing using React Router
- Authentication using Appwrite
- Managing files and databases with Appwrite
- Form handling using React Hook Form
- Building responsive interfaces with Tailwind CSS
- Integrating third-party libraries like TinyMCE

---

## 🔮 Future Improvements

- Search functionality
- Categories and tags
- User profile page
- Comments system
- Like and bookmark posts
- Dark mode
- Pagination
- Rich text image embedding

---
