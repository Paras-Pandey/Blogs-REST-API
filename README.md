# Blog API with Express

This is a simple RESTful API for managing blogs, implemented using Node.js and the Express.js framework. It supports basic CRUD operations for blog posts.

## Features

- **Create:** Add new blog posts.
- **Read:** Retrieve a list of all blog posts or a specific blog by its unique ID.
- **Update:** Modify an existing blog post.
- **Delete:** Remove a blog post.

## API Endpoints

### Get All Blogs

- **URL:** `/blogs`
- **Method:** `GET`
- **Description:** Retrieve a list of all blog posts.

### Get a Blog by ID

- **URL:** `/blogs/:id`
- **Method:** `GET`
- **Description:** Retrieve a specific blog post by its unique ID.

### Create a Blog

- **URL:** `/blogs`
- **Method:** `POST`
- **Description:** Add a new blog post.

### Update a Blog

- **URL:** `/blogs/:id`
- **Method:** `PUT`
- **Description:** Modify an existing blog post by its unique ID.

### Delete a Blog

- **URL:** `/blogs/:id`
- **Method:** `DELETE`
- **Description:** Remove a blog post from the database by its unique ID.

## Technologies Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)

## Installation

1. Clone this repository: `git clone https://github.com/Paras-Pandey/Blogs-REST-API.git`
2. Install dependencies: `npm install`
3. Start the server: `npm start`

## Usage

- Ensure the server is running.
- Use API endpoints to perform CRUD operations on blogs.
- You can test the API using tools like [Postman](https://www.postman.com/).

## License

This project is open-source and available under the [MIT License](LICENSE).

Feel free to fork and modify it to suit your needs.
