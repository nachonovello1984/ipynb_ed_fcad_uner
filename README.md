# Jupyter Notebook + RISE presentaciones de Estructuras de Datos - FCAD UNER
## Comandos para exportar a pdf

* Para generar la versión en PDF debemos primero generar la versión HTML usando **nbconvert**:

```jupyter nbconvert --to slides your_talk.ipynb --post serve```

* Se abre una página web en el navegador de la siguiente forma: ```http://127.0.0.1:8000/your_talk.slides.html#/```

* Agregamos el query param ```?print-pdf``` quedando algo así: ```http://127.0.0.1:8000/your_talk.slides.html?print-pdf```

* Notese que es necesario quitar el # al final de la URL para que las diapositivas se muestren verticalmente.

* Usar la opción de impresión del navegador para guardar como PDF.

    1. Cambiar la disposición a "apaisado".
    2. Quitar márgenes. 
    3. Habilitar la opción de fondos.
    4. Guardar