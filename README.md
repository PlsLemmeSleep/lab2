This is a simple CRUD API built with Node.js, Espress, and MySQL. It manages students and courses data for creating, reading, updating, and deleting records. 

How to run:
1. Clone the repo:
    git clone https://github.com/your-username/lab-crud-api.git
    cd lab-crud-api
3. Install dependencies: 
    npm install

4. Create a .env file based on .env.example and update it with your database credentials.
5. Run the server:
    npm start
6. Run npm start and open Postman. The server runs at:
    http://localhost:3000/api

## API Endpoints

### Courses
- `GET    /api/courses` → Get all courses
- `GET    /api/courses/:id` → Get a course by ID
- `POST   /api/courses` → Create a new course
- `PUT    /api/courses/:id` → Update a course
- `DELETE /api/courses/:id` → Delete a course

### Students
- `GET    /api/students` → Get all students
- `GET    /api/students/:id` → Get a student by ID
- `POST   /api/students` → Create a new student
- `PUT    /api/students/:id` → Update a student
- `DELETE /api/students/:id` → Delete a student
