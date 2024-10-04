- Debe descomprimir assets.zip dentro de la misma carpeta donde se encuentre el notebook tarea_2_código_base.ipynb

- Para garantizar una correcta ejecución del .ipynb se recomienda seguir los siguientes pasos:

  1.  Para evitar bugs utilice Visual Studio Code u otro IDE que tenga instalado localmente en lugar de Google Colab.
  2.  En la consola cree el entorno "env" con el siguiente comando:
      `python -m venv env`

  3.  Para activar el entorno en Windows:
      `env\Scripts\activate`
      Para activar el entorno en Unix/Linux:
      `source env/bin/activate`

  4.  Luego, ejecute el siguiente comando para instalar las dependencias de requirements.txt (puede ser dentro del mismo notebook):
      `pip install -r requirements.txt`

  5.  Para desactivar el entorno:
      `deactivate`

Para más información revisar el siguiente link: https://docs.python.org/es/3/tutorial/venv.html
