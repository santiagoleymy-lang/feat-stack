# StackSpring - API de una pila

Proyecto Spring Boot con Gradle para practicar la estructura de datos pila mediante una API REST. Usa Java 17 y los endpoints `POST /pila`, `GET /pila`, `GET /pila/pop` y `GET /pila/peek`.

## Abrir y ejecutar

Abre esta carpeta en IntelliJ IDEA. IntelliJ reconocerá `build.gradle` y descargará las dependencias de Spring Boot. Ejecuta `StackSpringApplication`.

## Peticiones

Puedes usar `peticiones.http` desde IntelliJ IDEA para probar la API.

- `POST /pila?valor=uno`: agrega un elemento.
- `GET /pila`: muestra los elementos.
- `GET /pila/peek`: consulta el elemento del tope.
- `GET /pila/pop`: saca y devuelve el elemento del tope.
