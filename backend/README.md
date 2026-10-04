# Backend — Spring Boot

## Historias de este sprint
- US-43: Crear cuentas de docentes — Daniela (rama admin-daniela)
- US-23: Registrar aula multigrado — Noemi (rama web-noemi)

## Cómo levantarlo
1. Crear el proyecto con Spring Initializr (start.spring.io) con las dependencias: Spring Web, Spring Data JPA, PostgreSQL Driver, Spring Security, Validation.
2. Configurar la conexión a PostgreSQL en src/main/resources/application.properties usando variables de entorno, nunca contraseñas escritas directamente.
3. Ejecutar con ./mvnw spring-boot:run

## Estructura sugerida
src/main/java/com/proyecto/
- admin/        (US-43: usuarios, docentes — Daniela)
- docente/      (US-23: aulas, grados — Noemi)
- common/       (manejo de errores, seguridad)
- config/
