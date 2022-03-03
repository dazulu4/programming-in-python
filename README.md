# programming-in-python
Programming Fundamentals in Python

## Python 3.8
* Realizar la instalación de Python <a href="https://www.python.org/downloads/windows/" target="_blank">3.8.x</a>. Siga el asistente de instalación y al final verifique que en la variable de ambiente **PATH** se encuentra la ruta *bin* de Python.
* Realizar la instalación de Jupyter Notebook. Abra una consola **CMD** y lance el comando **pip**; si el programa responde proceda con la  instalación:
  * Actualizar la instalación de pip a la última versión:
  ```
  python -m pip install --upgrade pip
  ```
  * Realizar la instalación del componente Notebook:
  ```
  pip install notebook
  ```
  * Realizar la instalación del componente Jupyter:
  ```
  pip install jupyter
  ```
* Valide la instalación anterior lanzando el comando **jupyter notebook** en la consola **CMD**, se debe abrir el navegador por defecto y se debe poder visualizar los archivos del directorio actual.

## Visual Studio Code (*Opcional*)
* Realizar la instalación de Visual Studio Code *(Opcional)*. Descargue e instale el producto, la url para descarga es la siguiente: <a href="https://code.visualstudio.com/download" target="_blank">code.visualstudio.com</a>.
* Abra el IDE y realice la instalación de los plugins Python que desee. Los recomendados son los siguientes: Python extension for Visual Studio Code, Code Runner (Ejecutor de scripts en cualquier lenguaje).

## Creación Variables de Ambiente
Verifica que la variable de ambiente **PATH** contenga las rutas correspondiente a los *bin* de Python. Ejemplo:
```
PATH=%PATH%;D:\Programas\Anaconda3;D:\Programas\Anaconda3\Library\bin;D:\Programas\Anaconda3\Scripts;D:\Programas\R\R-3.5.0\bin\x64
```

## Sincronización del Repositorio GitHub
Primero, debes estar en una consola **CMD** y navegar a un directorio para la sincronización del proyecto con los recursos de la capacitación.
1. Clona el repositorio:
```
git clone https://github.com/dazulu4/programming-in-python.git
```
2. Ingresa en el directorio de trabajo
```
cd programming-in-python
```

## Ejecución de Documentos Jupyter
Posicionado en el directorio **programming-in-python** ejecute el comando:
```
jupyter notebook
```
