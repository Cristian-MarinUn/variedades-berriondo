# Django App

Este es un proyecto desarrollado con Django. A continuación, se presentan las instrucciones para ejecutarlo correctamente.

## Requisitos

- Python 3.x
- Pip
- Virtualenv (opcional pero recomendado)

## Instalación

1. Clona este repositorio:
   ```sh
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_PROYECTO>
   ```

2. Crea y activa un entorno virtual (opcional pero recomendado):
   ```sh
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. Instala las dependencias del proyecto:
   ```sh
   pip install -r requirements.txt
   ```

## Ejecución del Servidor

Para ejecutar el servidor de desarrollo, abre una terminal en la misma ruta donde se encuentra el archivo `manage.py` y ejecuta:

```sh
python manage.py runserver
```

Esto iniciará el servidor en `http://127.0.0.1:8000/`.

## Acceso a la Administración

El sistema tiene un superusuario predefinido:

- **Usuario:** berriondo
- **Contraseña:** puespuespues

Puedes acceder al panel de administración en:

```
http://127.0.0.1:8000/admin/
```

## Usuario de Pruebas

Próximamente se agregará otro usuario de pruebas.

## Migraciones y Base de Datos

Si es la primera vez que ejecutas el proyecto, asegúrate de aplicar las migraciones:

```sh
python manage.py migrate
```

Si necesitas crear un superusuario adicional, usa:

```sh
python manage.py createsuperuser
```

## Notas

- Asegúrate de tener todas las variables de entorno configuradas correctamente.
- Puedes cambiar la configuración en `settings.py` según sea necesario.
- Recuerda activar el entorno virtual antes de ejecutar comandos relacionados con Django.

---

_Disfruta trabajando en tu aplicación Django!_ 🚀

# Django App

Este es un proyecto desarrollado con Django. A continuación, se presentan las instrucciones para ejecutarlo correctamente.

## Requisitos

- Python 3.x
- Pip
- Virtualenv (opcional pero recomendado)

## Instalación

1. Clona este repositorio:
   ```sh
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_PROYECTO>
   ```

2. Crea y activa un entorno virtual (opcional pero recomendado):
   ```sh
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. Instala las dependencias del proyecto:
   ```sh
   pip install -r requirements.txt
   ```

## Ejecución del Servidor

Para ejecutar el servidor de desarrollo, abre una terminal en la misma ruta donde se encuentra el archivo `manage.py` y ejecuta:

```sh
python manage.py runserver
```

Esto iniciará el servidor en `http://127.0.0.1:8000/`.

## Acceso a la Administración

El sistema tiene un superusuario predefinido:

- **Usuario:** berriondo
- **Contraseña:** puespuespues

Puedes acceder al panel de administración en:

```
http://127.0.0.1:8000/admin/
```

## Usuario de Pruebas NO ADMIN 

- **Usuario:** paisa_comprador
- **Contraseña:** puespuespues

## Migraciones y Base de Datos

Si es la primera vez que ejecutas el proyecto, asegúrate de aplicar las migraciones:

```sh
python manage.py migrate
```

Si necesitas crear un superusuario adicional, usa:

```sh
python manage.py createsuperuser
```

## Notas

- Asegúrate de tener todas las variables de entorno configuradas correctamente.
- Puedes cambiar la configuración en `settings.py` según sea necesario.
- Recuerda activar el entorno virtual antes de ejecutar comandos relacionados con Django.

---

_Disfruta trabajando en tu aplicación Django!_ 🚀

