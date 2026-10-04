# Proyecto Integrador — Plataforma Educativa Gamificada

Plataforma móvil y web para fortalecer las competencias comunicativas en escuelas rurales multigrado del Perú.

## Estructura del repositorio

| Carpeta | Tecnología | Responsable (Sprint 1) | Rama |
|---|---|---|---|
| `backend/` (Admin) | Spring Boot (Java) | Daniela | `admin-daniela` |
| `backend/` + `web-portal/` (Docente) | Spring Boot + React | Noemi | `web-noemi` |
| `app-movil/` | Kotlin (Android nativo) | Karla | `movil-karla` |

## Estrategia de ramas

El equipo trabaja con **una rama fija por integrante** durante todo el proyecto, no una rama por tarea. Cada quien hace sus commits en su propia rama y abre un Pull Request hacia `main` cuando termina su historia.

```
main            ← código siempre estable
├── movil-karla    (US-01: perfiles con avatar)
├── admin-daniela  (US-43: crear cuentas de docentes)
└── web-noemi      (US-23: registrar aula multigrado)
```

## Cómo clonar y trabajar

```bash
git clone <URL-del-repositorio>
cd proyecto-integrador

# La primera vez (crear tu rama):
git checkout -b movil-karla        # o admin-daniela / web-noemi

# Al iniciar cada sprint nuevo (traer lo último de main):
git checkout movil-karla
git pull origin main

# Cada vez que avanzas una tarea:
git add .
git commit -m "Descripción corta de lo que hiciste"
git push origin movil-karla

# Al terminar tu historia completa:
# Abres un Pull Request en GitHub de tu rama hacia main
```

