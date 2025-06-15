# 📝 Todo Application (Spring Boot Practice)

This is a simple **Todo List** web application built with **Spring Boot**, **Thymeleaf**, and **Bootstrap**.  
The project is intended as a **practice project** to learn and understand how Spring Boot works — including controller handling, form submission, model binding, and Thymeleaf templating.

---

## 🚀 Features

- Add new tasks via a form
- Toggle task completion (strike-through effect)
- Delete tasks
- Use of Thymeleaf conditionals and iterations
- Simple Bootstrap styling

---

## 🛠 Tech Stack

| Layer         | Technology               |
|---------------|---------------------------|
| Backend       | Spring Boot (Java)        |
| View          | Thymeleaf HTML templates  |
| UI Styling    | Bootstrap 5               |
| Build Tool    | Maven                     |
| Java Version  | 17+ recommended           |
| Database      | In-memory (e.g., H2) or MySQL (customizable) |

---

## 📁 Project Structure

```bash
src/
 └── main/
     ├── java/
     │   └── com.example.todoapp
     │        ├── Controller/TaskController.java
     │        ├── Service/TaskService.java
     │        └── models/Task.java
     └── resources/
         ├── templates/
         │    └── tasks.html
         └── application.properties
