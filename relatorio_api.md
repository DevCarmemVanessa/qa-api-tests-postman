# 📋 Relatório de Testes de API

## 🎯 Objetivo

Validar endpoints REST utilizando Postman, verificando comportamento das respostas, status codes e estrutura dos dados retornados.

---

# 🔍 Testes Realizados

## ✅ GET — Usuário válido

### Endpoint:
https://jsonplaceholder.typicode.com/users/1

### Resultado:
A API retornou corretamente os dados do usuário com status 200 OK.

---

## ✅ GET — Usuário inexistente

### Endpoint:
https://jsonplaceholder.typicode.com/users/999

### Resultado:
A API retornou status 404 Not Found e objeto vazio.

---

## ✅ POST — Criação de usuário

### Endpoint:
https://jsonplaceholder.typicode.com/users

### Body enviado:

```json
{
  "name": "Carmem Vanessa",
  "email": "carmem@email.com"
}
