# Challenge: Páginas Amarillas


## Antes de empezar

1. Crea un fork del repo actual
2. Clona/Descarga el repo forkeado:
  ```bash
    git clone URL-DEL-REPO-FORKEADO
  ```
3. Una vez descargado, estarás listo para iniciar el challenge:

## El problema

La empresa COMPUMUNDOHIPERMEGARED te solicita crear un directorio telefónico. Para ello, te comparte la información de algunos de sus clientes en el archivo `data.py`.
El directorio telefónico deberá funcionar a través de la terminal. La idea es que crees un menú interactivo con las siguientes funcionalidades:
1. Listar todos los usuarios
2. Agregar un nuevo usuario. Para ello deberás solicitar el nombre y el número al usuario
3. Modificar un usuario existente. Para ello deberás solicitar el nombre del cliente, buscarlo, y en caso de encontrarlo, solicitar el nuevo número. En caso de no encontrarlo, hazle saber al usuario que el nombre del cliente no existe.
4. Eliminar un usuario existente. 
5. Salir

## A tener en cuenta
- Ubica todo tu código dentro del archivo `main.py`
- El archivo `data.py` contiene un diccionario de nombres y números de teléfono. Puedes importarlos dentro del `main.py` utilizando la siguiente línea de código:

    ```python
      from data import people
    ```
- Puedes utilizar la librería [rich](https://github.com/Textualize/rich). Para instalarla, puedes utilizar la siguiente línea de código en la terminal:
  ```bash
    pip install rich
  ```

## Consejos
- Intenta tener claro los pasos a seguir antes de empezar a escribir código
- Quizá pueda serte de ayuda el tomar notas, hacer un diagrama de flujo, etc.
- Utiliza herramientas como chatgpt o la documentación de python y las librerías que utilices, para buscar ideas, inspiración, etc.
