# flask-api
Creamos la aplicación balance de movimientos con Flask API y JS

## Configuración

### Requisitos

- Python 3.x
- Flask

### Instalación

1. Clona este repositorio.
2. Instala las dependencias usando `pip install -r requirements.txt`.
3. Configura el archivo `config.sample.py` con tus preferencias y renómbralo a `config.py`.
4. Ejecuta la aplicación con `python app.py`.

## Uso

### Ejecución

Para iniciar la aplicación localmente, usa el siguiente comando:

```bash
python app.py
```

Esto iniciará el servidor en http://localhost:5000.

## Endpoints de la API
La API sigue una estructura RESTful:

-GET /movimientos: Lista todos los movimientos.
-POST /movimientos: Crea un nuevo movimiento.
-GET /movimientos/<id>: Obtiene un movimiento específico.
-PUT /movimientos/<id>: Actualiza parcialmente un movimiento.
-DELETE /movimientos/<id>: Elimina un movimiento.

## Interfaz Web
/: Página principal.
/movimientos/nuevo: Formulario para agregar un nuevo movimiento.
/movimientos/<id>/modificar: Formulario para modificar un movimiento existente.
Contribución

Si deseas contribuir a este proyecto, sigue los pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Haz tus cambios.
Haz commit de tus cambios (git commit -am 'Agrega nueva funcionalidad').
Haz push de la rama (git push origin feature/nueva-funcionalidad).
Abre un Pull Request.