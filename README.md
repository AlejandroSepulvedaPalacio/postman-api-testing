# postman-api-testing
# 🔍 Validaciones de API con Postman – TeamTrack

Este repositorio contiene las validaciones funcionales de múltiples endpoints REST realizadas con **Postman**, como parte de mis actividades como QA Engineer. Las pruebas están organizadas por recursos y ejecutadas manualmente o mediante Newman.

---

## 📁 Estructura del proyecto

postman-api-validations/
├── docs-api-team-track.postman_collection.json
├── test-api-santiago.postman_collection.json
└── README.md


---

## ✅ ¿Qué contiene?

- Validación de endpoints de autenticación, usuarios, roles, proyectos, evaluaciones, etc.
- Pruebas para:
  - Respuestas HTTP correctas (200, 400, 401, etc.)
  - Cuerpo de respuesta (`JSON schema`, propiedades esperadas)
  - Flujo de autenticación (`Login`, generación de reportes, permisos)
- Uso de variables de entorno como `{{END_POINT}}`
- Separación por colecciones temáticas

---

🧠 Notas
Las variables como {{END_POINT}} o {{TOKEN}} deben definirse en el entorno (environment) de Postman o vía CLI.

Puedes usar el Collection Runner para pruebas más automatizadas con datasets.

Se puede integrar con CI/CD (GitHub Actions, Jenkins, etc.)


👤 Autor
Santiago Alejandro Sepúlveda Palacio
QA Engineer
📧 santiagosepulveda.engineer@gmail.com
