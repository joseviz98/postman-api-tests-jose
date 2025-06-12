# Pruebas de API con Postman - Jose Vizcarra

Este repositorio contiene pruebas básicas de API realizadas con Postman usando el sitio público [reqres.in](https://reqres.in).

---

## 🧪 Herramientas utilizadas:
- Postman
- Git & GitHub

---

## 📋 Pruebas realizadas:

### ✅ 1. Prueba GET – Lista de usuarios
- **Endpoint:** `https://reqres.in/api/users?page=2`
- **Resultado esperado:** Código 200 OK
- ✅ Se obtuvo correctamente el listado de usuarios

📸 Captura de pantalla:
![GET](./prueba_get.png)
![GET](./prueba_post.png)
---

### ✅ 2. Prueba POST – Crear nuevo usuario
- **Endpoint:** `https://reqres.in/api/users`
- **Método:** `POST`
- **Body enviado (JSON):**
```json
{
  "name": "Jose",
  "job": "QA Tester"
}
📸 Captura de pantalla:
![GET](./prueba_post.png)
