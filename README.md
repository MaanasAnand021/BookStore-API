# Book Store API

A simple RESTful API for managing books using Node.js, Express, and MongoDB.

##  Installation

```bash
git clone <repo-url>
cd bookstore-api-mongodb
npm install
```

##  Configuration

Create a `.env` file based on the `.env.example`:

```env
MONGO_URI=mongodb://localhost:27017/bookstore
PORT=3000
```

##  Run the API

```bash
npm run dev
```

##  API Endpoints

- `GET /books` – Get all books
- `POST /books` – Add a new book
- `PUT /books/:id` – Update a book's details
- `DELETE /books/:id` – Delete a book
