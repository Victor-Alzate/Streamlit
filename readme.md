Objetivo: Crear una aplicación web simple utilizando Streamlit para cargar un archivo CSV, procesarlo con Pandas y mostrar la información en una tabla.

Entorno Virtual:

Crea un directorio para tu proyecto: mkdir mi-proyecto-streamlit
Navega al directorio: cd mi-proyecto-streamlit
Crea un entorno virtual: python3 -m venv .venv
Activa el entorno virtual: .venv/bin/activate (Linux/Mac) or .venv\Scripts\activate (Windows)
Instala las librerías: pip install pandas streamlit

Pasos:

Paso 1: Crear el archivo app.py

Crea el archivo app.py en el directorio del proyecto.

Importa las bibliotecas necesarias:

Crea un título para la aplicación:

Crea un widget de carga de archivos:

Paso 2: Procesar el archivo CSV

Verifica si se ha cargado un archivo:

Paso 3: Mostrar la tabla en Streamlit

Muestra el DataFrame como una tabla:

Paso 4: Ejecutar la aplicación

Ejecuta la aplicación Streamlit: streamlit run app.py
Abre la aplicación web en el navegador: http://localhost:8501/