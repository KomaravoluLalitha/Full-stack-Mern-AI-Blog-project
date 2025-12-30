
---

```md
#  QuickBlog – Full Stack MERN Blog Application

QuickBlog is a full-stack blog application built using the **MERN stack**.  
It enables admins to create and manage blog posts while users can view blogs and interact through comments.

---

## Features

- Admin authentication & authorization
- Create, edit, and delete blog posts
- Image upload support
- Blog listing and detailed blog view
- Comment system
- Secure RESTful APIs
- Responsive user interface

---

##  Tech Stack

### Frontend
- React (Vite)
- JavaScript
- HTML5 & CSS3
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication


### Tools & Services
- ImageKit
- Gemini API
- Vercel (Frontend Deployment)

---

##  Project Structure

```

QuickBlog-FullStack/
├── client/                 # React frontend
│   ├── public/
│   ├── src/
│   ├── .env
│   └── package.json
│
├── server/                 # Node.js backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── server.js
│
└── README.md

```

---

##  Environment Variables

### Backend (`server/.env`)
```

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url

```

### Frontend (`client/.env`)
```

VITE_API_BASE_URL=[http://localhost:5000](http://localhost:5000)

````

---

##  How to Run the Project Locally

###  Clone the Repository
```bash
git clone https://github.com/your-username/quickblog-fullstack.git
cd QuickBlog-FullStack
````

###  Backend Setup

```bash
cd server
npm install
npm run dev
```

###  Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

##  Sample API Endpoints

* `POST /api/admin/login`
* `POST /api/blog/create`
* `GET /api/blog/all`
* `POST /api/blog/comment`

---

## Future Enhancements

* User profile management
* Blog likes & bookmarks
* Search and filter functionality
* Role-based access control
* Improved UI/UX

---

 If you like this project, please give it a star!

```
