# Test_api_linkedin

Notebook para probar busqueda de perfiles por su nombre,compannias, multiples perfiles basados en palabras clave y envio de mensajes.

Para suprimir el uso de 0auth debe disponerse de una cuenta valida de linkedin.

## Instalación

Clonamos el repositorio

```bash
git clone https://github.com/fjospinas/test_api_linkedin.git

cd test_api_linkedin
```

Instalamos poetry para manejar las dependencias y posteriormente lo ejecutamos

```bash
pip install poetry

poetry install
```

## Uso
En el mismo directorio del proyecto, y desde un editor de texto se crea el archivo config.cfg con los datos de la cuenta de linkedin de la siguiente forma:
```
[credentials]
user = <correo linkedin>
password = <contraseña linkedin>
```

Para ejecutar el notebook usamos:

```bash
poetry run jupyter notebook
```

Posterioemente se abre el navegador y se selecciona el archivo `test_api_linkedin.ipynb` y se corren sus celdas en función de lo que se necesite.
