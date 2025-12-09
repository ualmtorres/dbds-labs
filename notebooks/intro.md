# Laboratorios de bases de datos con Jupyter

Manuel Torres, Departamento de Informática, Universidad de Almería

Este libro Jupyter está diseñado para practicar conceptos de bases de datos utilizando Jupyter Notebooks junto con motores de bases de datos PostgreSQL y MySQL. Proporciona un entorno interactivo para aprender y experimentar con consultas SQL, modelado de datos y análisis de rendimiento.

## Detalles del libro

Este repositorio contiene:

- Carpeta `setup-enviroment`: Incluye un archivo `docker-compose.yml` para levantar un entorno de Jupyter con PostgreSQL y MySQL. Los puertos predeterminados son: 
    - Jupyter: 8888
    - PostgreSQL: 5432
    - MySQL: 3306
- Carpeta `notebooks`: Incluye los notebooks de Jupyter con los ejemplos y ejercicios para aprender bases de datos.

- Archivos `README.md` y `LICENSE.md`: Archivos de información y licencia.

## Despliegue

Si quieres ejecutar los notebooks localmente, sigue estos pasos dispones de un entorno Docker que facilita la configuración. El entorno de Jupyter se levanta con Docker Compose. El entorno contiene JupyterLab, PostgreSQL y MySQL. Para levantar el entorno, ejecutar el siguiente comando en la carpeta `setup-enviroment`:

```bash
docker-compose up -d
```

* El entorno de Jupyter estará disponible en `http://localhost:8888` y se accede sin contraseña.
* El servidor de PostgreSQL estará disponible en `http://localhost:5432` con usuario `example` y contraseña `example`. La base de datos de ejemplo se llama `example`. El nombre del servidor para acceder a él desde Jupyter es `postgres`.
* El servidor de MySQL estará disponible en `http://localhost:3306` con usuario `example` y contraseña `example`. La base de datos de ejemplo se llama `example`. El nombre del servidor para acceder a él desde Jupyter es `mysql`.


## Licencia

Licencia CC BY-NC-ND 4.0

Copyright (c) 2025 [Manuel Torres - Departamento de Informática - Universidad de Almería]

Este proyecto está licenciado bajo la Licencia CC BY-NC-ND 4.0. Esto significa que puedes compartir el proyecto siempre que cites al autor, no lo uses para fines comerciales y no realices obras derivadas.
