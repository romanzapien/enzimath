# enzimath

Este repositorio de [GitHub](https://es.wikipedia.org/wiki/GitHub) contiene los [Jupyter Notebooks](https://es.wikipedia.org/wiki/Proyecto_Jupyter#Jupyter_Notebook) de las 4 sesiones teóricas de *Enzimath: Entendiendo a las enzimas entre genes y ecuaciones* para Clubes de Ciencia México 2025 sede Guanajuato (CdCMx 2025 - GTO3). 

Da click en alguna de las ligas abajo para comenzar a interactuar con el notebook correspondiente (técnicamente al dar click estarás creando una [maquina virtual](https://es.wikipedia.org/wiki/Máquina_virtual) en un servidor en alguna parte del mundo). 
[Binder](https://mybinder.org) es el servicio en linea que creará esa máquina virtual usando la información contenida en este repositorio de Github permitiéndote interactuar con ella a través de la computadora donde estás leyendo ésto.
Una vez creada la sesión de Binder, podras utilizar y añadir texto, ecuaciones y código.
Si solo quieres vizualizar el notebook (no hacer modificaciones o ejecutar código), da click en el nombre del notebook arriba. 
GitHub tiene la habilidad de mostrar la imagen estática del notebook en el formato correcto.

Los Jupyter Notebooks que vez arriba tienen extensión `.ipynb`, una abreviación de iPython Notebook.
A pesar del nombre, en ellos trabajaremos con el lenguaje de programación `Julia` no `Python`, escribiendo texto y ecuaciones en formato `Markdown`, todo contenido en el documento de `Jupyter`. 

**Sesión 1**. *Programación (Jupyter, Markdown y Julia), Sistemas dinámicos y Mecanismos de reacción enzimática.*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_1.ipynb)

**Sesión 2**. *Cinética enzimática (Michaelis-Menten y más).* 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_2.ipynb)

**Sesión 3**. *Enzimas en el contexto de la ecología y evolución de los organismos que las contienen.*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_3.ipynb)

**Sesión 4**. *Estimación de los parámetros cinéticos de Michaelis-Menten (V_max y K_m) a partir de datos experimentales.*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_4.ipynb)

Si te interesa executar los Jupyter Notebooks en tu computadora personal, son necesarios dos pasos, que se pueden entender de la siguiente manera:
si estuvieramos hablando con coches, Julia sería el motor y Jupyter el chasis sobre el que se monta el motor. 
Por lo tanto ...

Primero, debes descargar Julia de aquí [https://julialang.org/install/](https://julialang.org/install/) e instalar los paquetes que usan los notebooks (e.g. `Catalyst`, `Plots`, etc).
Hay dos posibilidades, 
1. Instalar cualquier versión de esos paquetes, siguiendo este tutorial, [https://docs.julialang.org/en/v1/stdlib/Pkg/](https://docs.julialang.org/en/v1/stdlib/Pkg/), o
2. instalar las versiones precisas de los paquetes que usamos en CdCMx 2025 - GTO3.
Para ello debes descargar el archivo `Project.toml` (arriba) que indica las versiones precisas de los paquetes.
Cuando se instalan versiones específicas de paquetes es recomendable crear un "Environment" (Ambiente de Programación en español) en donde debes colocar el archivo `Project.toml` y seguir los pasos indicados en la sección *Creating your own environments* de [https://pkgdocs.julialang.org/v1/environments/#Creating-your-own-environments](https://pkgdocs.julialang.org/v1/environments/#Creating-your-own-environments).
La diferencia es que solo el método 2 puede garantizar que si se corre el mismo Jupyter Notebook en dos computadoras distintas se obtenga el mismo resultado.
**Para aquellos que inician en la programación la posibilidad 1 es suficiente, para aquellos en investigación, la posibilidad 2 es recomendable**.

Segundo, debes descargar una interfaz gráfica para visualizar los Jupyter Notebook en formato correcto.
Yo recomiendo Visual Studio Code (VSCode) que no solo funciona con `Julia`, sino con `Python`, `C++`, etc.
[Da click aquí para descargar VSCode](https://code.visualstudio.com/download).
Aquí puedes ver un el [tutorial sobre como usar Jupyter Notebooks en VSCode](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).

Una vez instalado Julia, sus paquetes, y VSCode estarás listx para manipular y executar los Jupyter Notebooks en tu computadora personal.
Hay bastante información en linea para si quisieras complementar esta instalación sencilla.
