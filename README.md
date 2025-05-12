# Práctica Docker - Contenedores

## Descripción
Práctica Formativa Obligatoria N2 sobre Docker, imágenes y contenedores. Implementación de una aplicación web con PHP y MySQL utilizando Docker.

## Estructura del Proyecto
- `Dockerfile`: Configuración para crear la imagen PHP con Apache
- `docker-compose.yml`: Configuración de los servicios (web y MySQL)
- `html/index.php`: Aplicación web que muestra productos desde MySQL

## Comandos principales

```bash
# Ejecutar los servicios
docker-compose up -d

# Ver contenedores en ejecución
docker ps
```
## Puertos
- Aplicación web: http://localhost:8080
- MySQL: localhost:3306

