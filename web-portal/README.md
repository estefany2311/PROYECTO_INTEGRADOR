# Portal Web — React

## Historias de este sprint
- US-43: Formulario "Crear docente" — Daniela (rama admin-daniela)
- US-23: Formulario de registro de aula — Noemi (rama web-noemi)

## Cómo levantarlo
1. Crear el proyecto: npx create-react-app web-portal (o Vite, si el equipo lo prefiere).
2. Instalar un cliente HTTP: npm install axios
3. Ejecutar con npm start

## Estructura sugerida
src/
- pages/admin/      (CrearDocente.jsx, ListaDocentes.jsx — Daniela)
- pages/docente/    (RegistrarAula.jsx, ListaAulas.jsx — Noemi)
- services/         (llamadas a la API)
- components/       (elementos reutilizables)
