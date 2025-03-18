# api-students
API to manage 'Golang do Zero' course students

Routes:
- GET /students - list all students 
- POST /students - create students
- GET /students/:id - get infos from a specific student
- PUT /students/:id - update student info
- DELETE /students/:id - delete student

Struct Student:
- Name
- CPF
- Email
- Age
- Active