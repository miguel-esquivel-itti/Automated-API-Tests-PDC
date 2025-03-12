# 🚀 Automatización de APIs

Este proyecto contiene pruebas automatizadas para garantizar la funcionalidad y consistencia de los endpoints del portal de comercios.

---

## 🔍 Propósito

Validar que las APIs del portal de comercios operen correctamente, proporcionando:

- **Autenticación segura**: Login y manejo de tokens (`access_token`).
- **Gestión de datos**: Validación y actualización de información del comercio.
- **Procesamiento de transacciones**: Validación de pagos y consultas.
- **Generación de reportes**: Comprobación de endpoints relacionados con informes.

---

## 📂 Estructura del Proyecto

### 📌 Colección Principal
- **Autenticación** (login y manejo de tokens).
- **Gestión de datos del comercio** (e.g., `sellerId`).
- **Transacciones** (validaciones de pagos y consultas).
- **Gestión de usuarios**.

### 🌎 Entornos Configurados
- **Variables dinámicas:**
  - `{{base_url}}`
  - `{{onb_backend_access_token}}`
  - `{{sellerId}}`

### 🤖 Automatización de Pruebas
- **Pre-request Scripts**: Configuración automática de tokens.
- **Tests**: Validaciones automatizadas de respuestas y códigos de estado.

---

## 💡 Cómo Usar

1. Configura las variables de entorno:
   - `{{base_url}}`: URL base del entorno.
   - `{{onb_backend_access_token}}`: Token de acceso.
2. Ejecuta la colección completa o una solicitud específica según el caso.
3. Revisa los resultados en el **Test Runner** de Postman.

---

## ✅ Criterios de Aceptación

- Todos los endpoints deben devolver el código de estado esperado (`200`, `401`, etc.).
- Los tokens deben gestionarse dinámicamente sin interrupciones.
- La información clave, como `sellerId`, debe coincidir con los valores esperados.

---

## 📊 Beneficios del Proyecto

✔ **Eficiencia**: Reducción de tiempos manuales en pruebas.
✔ **Confiabilidad**: Identificación rápida de errores en las APIs.
✔ **Escalabilidad**: Fácil incorporación de nuevos endpoints.

---

## 🔗 Recursos Adicionales

- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [Documentación de Postman](https://learning.postman.com/)

---

¡Automatiza y optimiza tus pruebas de API con este proyecto! 🚀

