<h1 style="text-align:center">Instructivo instalación</h1>
<h1 style="text-align:center">Python y Jupyter Notebook</h1>
<h3 style="text-align:center">ACUS099: Procesamiento Digital de señales</h3>
<p style="text-align:center">Dr. Víctor Poblete <br>
<a href="mailto:vpoblete@uach.cl">vpoblete@uach.cl</a><br>
<p style="text-align:center">Diego A. Espejo Alquinta- Ayudante <br>
<a href="mailto:diego.espejoa@gmail.com">diego.espejoa@gmail.com </a><br>
<a href="http://www.acusticauach.cl">www.acusticauach.cl</a><br>  

## Indice 
+ [Python](#id1)
+ [Jupyter Notebook](#id2)
+ [Windows](#id3)
    - [Python](#id31)
    - [Jupyter Notebook](#id32)
+ [Mac](#id4)
    - [Python](#id41)
    - [Jupyter Notebook](#id42)
+ [Ubuntu](#id5)
    - [Python](#id51)
    - [Jupyter Notebook](#id52)


## 1. Python<a name='id1'></a>.
Python es un lenguaje de programación poderoso y fácil de aprender. Cuenta con estructuras de datos eficientes y de alto nivel y un enfoque simple pero efectivo a la programación orientada a objetos. La elegante sintaxis de Python y su tipado dinámico, junto con su naturaleza interpretada, hacen de éste un lenguaje ideal para scripting y desarrollo rápido de aplicaciones en diversas áreas y sobre la mayoría de las plataformas.

Para esta asignatura se utilizará versiones >= 3.7.4.

***

## 2. Jupyter Notebook<a name='id2'></a>.

Jupyter Notebook (anteriormente IPython Notebooks) es un entorno informático interactivo basado en la web para crear documentos de Jupyter notebook. El término "notebook" puede hacer referencia coloquialmente a muchas entidades diferentes, principalmente la aplicación web Jupyter, el servidor web Jupyter Python o el formato de documento Jupyter según el contexto. Un documento de Jupyter Notebook es un documento que sigue un esquema versionado y que contiene una lista ordenada de celdas de entrada/salida que pueden contener código(usando Python en esta situacion), texto (usando Markdown), matemáticas(usando Latex), gráficos y texto enriquecidos, generalmente terminado con la extensión ".ipynb".

***

## 3. Windows<a name='id3'></a>
En una primera instancia, verificar si tu ordenador ya cuenta con Python 3, para poder realizar este checkeo, debes ejecutar el siguiente comando Windows + R , al apretar estas teclas aparecerá la ventana de Ejecutar, donde simplemente escribimos CMD y pulsamos Enter o en Aceptar con lo que nos aparecerá la ventana de comandos.

En esta ventana debemos escribir lo siguiente

```
python --version
```
o 
```
python3 --version
```
Si obtiene una respuesta favorable, es decir, el sistema le arroja la version de Python y es mayor a la anterior mente utilizada, favor dirigirse a la sección 3.2.<a name='id32'></a>

De lo contrario debe seguir a continuación.

### 3.1. Python<a name='id31'></a>
Primero comprueba si tu ordenador ejecuta la versión 32 bits de Windows o la de 64, en "Tipo de sistema" en la página de "Acerca de":

Presiona la tecla de Windows y la tecla Pause/Break al mismo tiempo. Abre el Panel de Control desde el menú de Windows, después accede a Sistema & y Seguridad, luego a Sistema.Presiona el botón de Windows, luego accede a Configuración > Sistema > Acerca de.
Puedes descargar Python para Windows desde la siguiente web <a href="https://www.python.org/downloads/windows/">https://www.python.org/downloads/windows/</a>. Clickea en el enlace "Latest Python 3 Release -Python x.x.x". Si tu ordenador ejecuta la versión de 64 bits de Windows, descarga Windows x86-64 executable installer. De lo contrario, descarga Windows x86 executable installer. Después de descargar el instalador, deberías ejecutarlo (dándole doble click) y seguir las instrucciones.

Una cosa para tener en cuenta: Durante la instalación, verás una ventana de "Setup". Asegúrate de marcar las casillas "Add Python 3.8 to PATH" o "Add Python to your environment variables" y hacer click en "Install Now".

Verifica si la instalación fue exitosa abriendo una terminal o consola, y corriendo el comando python3:

```
Input: python3 --version
Python 3.8.2
```

Tambien verificar que la herramienta PIP tambien haya sido instalada, de la misma manera en que se verificó python:

```
Input: pip3 --version
pip 20.0.2 from .../Library/Python/3.8/lib/python/site-packages/pip (python 3.8)
```

### 3.2. Jupyter Notebook<a name='id32'></a>
Para poder instalar jupyter se debe tener como requisito el tener Python ya instalado, luego de este paso haya sido realizado se debe abrir la consola de comandos y realizar lo siquiente:

```
Input: pip3 install notebook --user
```

Luego de que se haya instalado, ejecutar la siguiente linea para verificar que la instalación fue exitosa:

```
Input: jupyter notebook
```
Al ejecutar esta linea se te deberia abrir una pestaña de tu navegador predeterminado con la plataforma *Jupyter Notebook* 

***
Si al instalar "jupyter" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable. Acceder a
<a href="https://andrezgz.wordpress.com/2014/06/04/agregar-ruta-a-la-variable-path-en-windows/">https://andrezgz.wordpress.com/2014/06/04/agregar-ruta-a-la-variable-path-en-windows/</a> para resolver problema.
***

## 4 Mac<a name='id4'></a>

Para abrir la terminal de MacOS haz clic en el icono "Finder" situado en el Dock, luego selecciona "Aplicaciones > Utilidades"
Finalmente dale doble clic al icono "Terminal".

Verificar versión con la que se cuenta en su ordenador con la siguiente linea en terminal:

```
python --version
```
o 
```
python3 --version
```
Si cumple con los requisitos mencionados en 1.<a name='id1'></a> dirigirse a la sección 4.2.<a name='id42'></a>

De lo contrario, para este sistema operativo se necesita instalar una herramienta llamada *Homebrew* cuya finalidad es ser un proveedor e instalador de herramientas y programas.

El gestor de paquetes se obtiene en <a href="https://brew.sh/index_es">https://brew.sh/index_es</a>., las instrucciones de su instalación se encuentran claramente pauteadas en el enlace.

### 4.1. Python<a name='id41'></a>
Una vez ya instalado *Homebrew* se procede a utilizarlo, en la terminal de su computador con la siguiente linea:

```
brew install python3
```
luego que ya se haya ejecutado la linea anterior se  procede a verificar su instalacion, nuevamente con la linea: 

```
python3 --version
```

    NOTA: brew busca la version de python3 mas reciente y mas estable de las presentes en la red

### 4.2. Jupyter Notebook<a name='id42'></a>

Para poder instalar jupyter se debe tener como requisito el tener Python ya instalado, luego de este paso haya sido realizado se debe abrir la consola de comandos y realizar lo siquiente:

```
Input: pip3 install notebook --user
```

Luego de que se haya instalado, ejecutar la siguiente linea para verificar que la instalación fue exitosa:

```
Input: jupyter notebook
```
Al ejecutar esta linea se te deberia abrir una pestaña de tu navegador predeterminado con la plataforma *Jupyter Notebook* 

***

## 5 Ubuntu<a name='id5'></a>

Para este sistema operativo la instalación es mas sencilla, ya que este depende solo de su terminal.


### 5.1. Python<a name='id51'></a>
Instalar Python se debe realizar en la terminal y con el gestor de paquetes llamado 'apt-get' que viene por defecto en tu computadora.
Las lineas para obtener el lenguaje son las siguientes:

```
sudo apt update
sudo apt install software-properties-common
sudo apt install python3.8
```
Una vez realizadas estas lineas verificar que la instalación de estas haya sido correcta, con la siguiente linea:

```
Input:python3 --version
Python 3.8.2
```

### 5.2. Jupyter Notebook<a name='id52'></a>

Para poder instalar jupyter se debe tener como requisito el tener Python ya instalado, luego de este paso haya sido realizado se debe abrir la consola de comandos y realizar lo siquiente:

```
Input: pip3 install notebook --user
```

Luego de que se haya instalado, ejecutar la siguiente linea para verificar que la instalación fue exitosa:

```
Input: jupyter notebook
```
Al ejecutar esta linea se te deberia abrir una pestaña de tu navegador predeterminado con la plataforma *Jupyter Notebook* 

***


## Bibliografía

<a href="http://docs.python.org.ar/tutorial/3/real-index.html">http://docs.python.org.ar/tutorial/3/real-index.html</a>.

<a href="https://tutorial.djangogirls.org/es/python_installation/">https://tutorial.djangogirls.org/es/python_installation/</a>.

<a href="https://jupyter.org/install">https://jupyter.org/install</a>.
