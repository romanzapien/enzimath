# enzimath

Este repositorio contiene los Jupyter Notebooks de las 4 sesiones teóricas de *Enzimath: Entendiendo a las enzimas entre genes y ecuaciones*. Da click en alguna de las siguiente ligas para comenzar a usar el notebook correspondiente (técnicamente estarás creando una maquina virtual en un servidor en alguna parte del mundo). Binder permite crear esa máquina virtual usando la información contenida en este repositorio de GitHub e interactuar con ella mediante la computadora donde estás leyendo ésto.
Una vez creada, podras escribir (texto y ecuaciones) y programar en esa máquina virtual de forma interactiva.
Si solo quieres ver el notebook y no usarlo interactivamente, da click en el nombre del notebook arriba. 
GitHub tiene la habilidad de mostrar la imagen estática del notebook en el formato correcto.

**Sesión 1**. *Programación (Jupyter, Markdown y Julia), Sistemas dinámicos y Mecanismos de reacción.*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_1.ipynb)

**Sesión 2**. *Cinética enzimática (Michaelis-Menten y más).* 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_2.ipynb)

**Sesión 3**. *Enzimas en el contexto de la ecología y evolución de los organismos que las contienen.*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_3.ipynb)

**Sesión 4**. *Estimación de los parámetros cinéticos de Michaelis-Menten (V_max y K_m) a partir de datos experimentales.*

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/romanzapien/enzimath/HEAD?urlpath=modelado_sesion_4.ipynb)

Si te interesa usar Julia en tu computadora personal, puedes descargar Julia de aquí [https://julialang.org/install/](https://julialang.org/install/).
Luego, hay que instalar los paquetes que usan los notebooks (e.g. `Catalyst`, `Plots`, etc).
Hay dos posibilidades, 
1. Instalar cualquier versión de esos paquetes, siguiendo este tutorial, [https://docs.julialang.org/en/v1/stdlib/Pkg/](https://docs.julialang.org/en/v1/stdlib/Pkg/), o
2. instalar las versiones precisas de los paquetes que usan los notebooks de arriba.
Para ello requerirás descargar el archivo `Project.toml` que incluye las versiones precisas de los paquetes.
Cuando se instalan versiones específicas es recomendable crear un "Environment" (Ambiente de Programación en español) en donde debes colocar el archivo `Project.toml` y seguir los pasos indicados en la sección *Creating your own environments* de [https://pkgdocs.julialang.org/v1/environments/#Creating-your-own-environments](https://pkgdocs.julialang.org/v1/environments/#Creating-your-own-environments).

La diferencia es que solo el método 2 puede garantizar que si se corre el mismo notebook en dos computadoras distintas se obtenga el mismo resultado.
