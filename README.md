# api-students

API para manejar estudiantes con Flask

## Endpoints

-   GET /students - Lista todos los estudiantes
-   POST /students - Agregar estudiante
-   GET /students/{id} - Ver estudiante específico
-   PUT /students/{id} - Editar estudiante
-   DELETE /students/{id} - Borrar estudiante

## Instalación

1. Crear la base de datos:

    ```
    python db.py
    ```

2. Correr la aplicación:
    ```
    python app.py
    ```

La API funciona en http://IP-MV:8000

## Docker

Construir:

```
docker build -t api-students .
```

Ejecutar:

```
docker run -p 8000:8000 api-students
```
