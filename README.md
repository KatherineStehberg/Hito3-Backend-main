# Hito3-Backend
Desafio Latam Proyecto final (G62)

https://github.com/KatherineStehberg/Biodiversidad-master

thunder client

1. Login (POST /api/auth/Frontend/Src/pages/Login.html)
Método: POST
URL: /api/auth/Frontend/Src/pages/Login.html
Body (JSON):
{
  "username": "user",
  "password": "password123"
}

Resultado esperado: 200 OK (si el login es exitoso) o 401 Unauthorized (si el login falla).

2. Obtener todos los productos (GET /api/products)
Método: GET
URL: /api/products
Body: N/A (no es necesario enviar un body).
Resultado esperado: 200 OK con una lista de productos en el cuerpo de la respuesta.
3. Crear un nuevo servicio (POST /api/services)
Método: POST
URL: /api/services
Headers:
Authorization: Bearer [your-token]
Body (JSON):
{
  "title": "Nuevo Servicio",
  "description": "Descripción del nuevo servicio",
  "price": 29.99
}

Resultado esperado: 201 Created con los detalles del servicio recién creado.

4. Obtener todos los usuarios (GET /api/users)
Método: GET
URL: /api/users
Body: N/A (no es necesario enviar un body).
Resultado esperado: 200 OK con una lista de usuarios en el cuerpo de la respuesta.

![Captura de pantalla 2024-09-08 a la(s) 22 56 42](https://github.com/user-attachments/assets/cd906162-620f-4c5a-bf75-3de069385d83)

