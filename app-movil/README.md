# App Móvil — Android (Kotlin)

## Historia de este sprint
- US-01: Visualizar perfiles con avatar — Karla (rama movil-karla)

## Cómo levantarlo
1. Crear el proyecto en Android Studio: Empty Activity, lenguaje Kotlin, arquitectura MVVM.
2. Agregar en build.gradle: Retrofit, Coil (o Glide) y corrutinas.
3. Configurar la URL base del backend en un archivo de constantes o BuildConfig.

## Estructura sugerida
app/src/main/java/com/proyecto/movil/
- ui/codigoaula/    (pantalla para ingresar el código)
- ui/perfiles/      (pantalla con la cuadrícula de avatares)
- data/remote/      (Retrofit, DTOs)
- data/repository/
- viewmodel/
