# Blog API

A simple RESTful API for a blog system built with Express.js and MongoDB.

## Setup

1. Install dependencies
```
npm install
```

2. Configure environment
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/blog_api
JWT_SECRET=yourSecretKey
```

3. Run the server
```
npm run dev
```

## Endpoints

### Posts
- GET /api/posts
- GET /api/posts/:id
- POST /api/posts
- PUT /api/posts/:id
- DELETE /api/posts/:id

### Authors
- GET /api/authors
- GET /api/authors/:id
