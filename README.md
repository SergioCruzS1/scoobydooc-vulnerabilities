# scoobydooc-vulnerabilities
 
 ## Introducción
 El propósito de este proyecto es la automatización en la extracción de vulnerabilidades (por servidor) de los documentos de ciberseguridad. Con la finalidad de ahorrar tiempo en análisis de las incidencias.

 ## Ambientación
El proyecto está creado en python, sin embargo se ocupó un entorno de desarrollo llamado [Jupyter Notebook](https://docs.jupyter.org/en/latest/), el cual nos permite la compilación de código por bloque (celdas).

Existen diversas maneras de trabajar con este ambiente, a continuación se describen 2: 

* Google Colab: La opción más sencilla y sin tener que instalar nada, nos permite la ejecución en la nube con recursos proporcionados por google. Se requiere una cuenta de Google para su utilización.
    ### Pasos a seguir
    1. Ingresar a [Google Colab](https://colab.research.google.com/)
    2. Iniciar sesión con su cuenta de google
    3. En la pestaña archivo seleccionar **Abrir bloc de notas**, nos abrirá una pestaña como la que se presenta a continuación: ![Abrir bloc notas Google Colab Img](/docs/AbrirBlocNotasGoogleColab.png)
    4. Ingresamos al apartado **Github** e ingresamos la url del proyecto en el cuadro de búsqueda, deben aparecernos los archivos del proyecto, hacemos click en el archivo podemos ejecutar.
    **Nota:** Esta es la forma más rápida de ejecutar el proyecto, sin embargo los documentos a analizar se deben cargar a Google Drive.

* Anaconda Navigator: Es un software que nos permite gestionar paquetes y entornos de desarrollo de Python desde una interfaz gráfica.
    ### Pasos a seguir
    1. Descargar [Anaconda Navigator](https://anaconda.org/anaconda/anaconda-navigator)
    2. Instalar (Next)
    3. Crear un nuevo entorno 
    ![Entorno Conda](/docs/CondaEnviroment.png)
    4. Una vez creado en entorno, regresar a la sección Home y seleccionar nuestro entorno.
    5. Instalar Jupyter Notebook y ejecutarlo
    6. Abrir el archivo desde nuestra carpeta donde descargamos el repositorio