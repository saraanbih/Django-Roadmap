# Django Learning Roadmap (3 Months)

> This roadmap is designed to guide you from beginner to advanced level in Django through practical projects and focused learning.
> **Goal**: Build real Django projects in 3 months.

**Full Roadmap:** [Django Roadmap Repository](https://github.com/RadwanHegazy/Django-Roadmap/)

---

## Important Guidelines

1. **Send your completed tasks privately on Discord.**
2. **You must complete all tasks in the current phase to move to the next one.**
3. Do not rely on AI tools to complete your tasks. Searching and understanding is key.
4. Share your progress and posts in the `#linkedin-support` channel.
5. Follow the roadmap **in order**.
6. If you face difficulty understanding something, contact me privately.

---

## Beginner Section

### Phase 1 (10 Days) - Python Basics

* [Python Basics](https://www.youtube.com/playlist?list=PLDoPjvoNmBAyE_gei5d18qkfIe-Z8mocs)
* [Python OOP](https://www.youtube.com/playlist?list=PLUgz8T_NoattU54gGARPXPmmawQNl-1_T)

#### Task:

* Build a simple calculator to perform `+ - * / // %` between two numbers.
* Build a basic To-Do system with Create, Read, and Delete features.

---

### Phase 2 (15 Days) - Django Basics

* [What is Django](https://www.youtube.com/watch?v=t_p4ZyAYyaY)
* [Django Architecture](https://www.youtube.com/watch?v=xFkzKxQz9gE)
* [Django Starter Series (1:36)](https://www.youtube.com/playlist?list=PL2z1gXAKH9c3XUn2HYMWRbAon4z6AQ4CL)
* [GitHub Crash Course in Arabic](https://www.youtube.com/watch?v=5i_FzxdqWc8)

#### Task:

Build a Django To-Do system with the following:

* User registration, login, logout
* Each user has their own To-Dos
* CRUD operations for To-Dos
* Todo model:

  * `user`: ForeignKey
  * `text`: TextField
  * `is_done`: BooleanField
  * `created_at`: DateTimeField
* Admin can view, update, and delete all todos.

Push your project to GitHub.

---

### Phase 3 (5 Days) - Network & HTTP

* Network Basics (1:19)
* HTTP Protocol

#### Task:

* Write a **LinkedIn post** summarizing your understanding of HTTP.

---

## Intermediate Section

### Phase 1 (10 Days) - Authentication & ORM

* [Authentication & Authorization](https://www.youtube.com/watch?v=7ijBiXddB7w)
* [What is ORM](https://www.youtube.com/watch?v=KthQ0UmBmxE)
* [Django ORM Playlist](https://www.youtube.com/playlist?list=PLdLYbRBk3sGmWHmS4fYTucOImkssv8K3R)

#### Task:

* Write a LinkedIn post explaining:

  * Authentication vs Authorization
  * Importance of ORM in Django

---

### Phase 2 (10 Days) - REST API

* [What is an API](https://www.youtube.com/watch?v=nomcoLwnHS4)
* [REST APIs Playlist](https://www.youtube.com/playlist?list=PLTCrU9sGybupzS5-3iYTsYUI1emBDKdHu)
* [Postman](https://www.youtube.com/watch?v=zD8HaT7uX5A)
* [Django Rest Framework (1:7)](https://www.youtube.com/watch?v=TJnvIyk_7xU)

#### Task:

* Create a To-Do system using **DRF**.
* Build CRUD APIs for todos.
* Test endpoints in **Postman** and save a collection.

---

### Phase 3 (10 Days) - JWT & Testing

* [Django Serializers](https://www.youtube.com/watch?v=hSGVNlEmmyE)
* [What is JWT](https://www.youtube.com/watch?v=B-x7eeYtFIA)
* [Using JWT in DRF](https://www.youtube.com/watch?v=KLua_cYGLec)
* [API Testing with DRF](https://www.youtube.com/watch?v=sRluxnmZ-H8)

#### Task:

Enhance the To-Do system:

1. Integrate **JWT Authentication**
2. Register/Login users
3. Protect APIs with authentication
4. Return tasks only for the authenticated user
5. Write unit tests for all endpoints
6. Push project to GitHub

---

## Advanced Section

### Topics:

1. **Caching**

   * [Caching in DRF](https://www.youtube.com/watch?v=tJVNUYvjTUk)
   * [Redis Installation](https://www.youtube.com/watch?v=DLKzd3bvgt8)

2. **WebSockets**

   * [Intro](https://www.youtube.com/watch?v=G0_e02DdH7I)
   * [Django Channels](https://www.youtube.com/watch?v=G0_e02DdH7I)

3. **Celery & Celery Beat**

   * [Playlist](https://www.youtube.com/playlist?list=PLLz6Bi1mIXhHKA1Szy2aj9Jbs6nw9fhNY)

4. **Advanced Django ORM**

   * [Playlist](https://www.youtube.com/playlist?list=PL-2EBeDYMIbQXKsyNweppuFptuogJe2L-)

5. **Deployment**

   * [Render](https://www.youtube.com/watch?v=wczWm8j4v9w)
   * [Railway](https://www.youtube.com/watch?v=AjKhxWgGpjY)

---

### Final Phase Task: Real-Time Chat App

Build a chat system with:

* User profiles & friend system
* Private messages & group rooms
* Room admin controls (update/delete)
* Real-time messaging using **Django Channels**
* Notifications for new messages
* Send message to all users using **Celery**
* **Redis** for caching & as broker
* **JWT** Authentication
* **DRF** for APIs
* **Postman Docs**
* **Unit testing**
* Push to GitHub with clean `README.md`
* Dockerize & deploy to **Render/Railway**

---
