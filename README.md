# YetAnotherTodoList

## Simple todo list webapp(s) in every language and frameworks i heard of


### might discard it soon, made in the heat of 3 AM motivation :) 


## Rules: 
### For Backend: 
- Backend consists of _ Api endpoints 
    1. (POST/GET) /api/login (oauth with google)
    2. POST /api/todo/createTodo
    3. PUT /api/todo/toggleTodo/{todoId}
    4. DELETE /api/todo/deleteTodo/{todoId}
    5. GET /api/todo/getTodos
- Middleware authorising user before /api/todo routes
- JWT Cookie based auth
- All backend shares the same sqlite database
- Todo Schema:
```
Type Todo {
    title: String,
    isCompleted: Int (Sqlite doesn't supports boolean)
}
```
### For Frontend:
- Every Frontend can switch between all the backends for API calls
- Similar/Indistinguishable UI
- Cookie based auth
- Error Handling


## Backend Frameworks:
- JavaScript/TypeScript:
    - Express
    - Hono
    - Fastify
    - NestJs
    - Raw Bun
    - Koa
- Python:
    - Django
    - Flask
    - FastApi
    - Dash
- Rust:
    - Actix
    - Axum
    - Warp
    - Rocket
    - Raw Rust
- Go:
    - Gin
    - Echo
    - FastHTTP
    - Raw Go
- Ruby on Rails (Ruby)
- Laravel (PHP)
- Spring Boot (JAVA, Kotlin)
- ASP .Net (C#)
- Drogon (C++)

## Frontend Frameworks: 
- React + Vite
- NextJs
- Astro
- Remix
- Svelte
- Vue
- Vanilla
- Angular
- SolidJs
- Qwik
- Yew (WASM, Rust)