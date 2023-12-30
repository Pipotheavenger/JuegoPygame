# JuegoPygame
Este proyecto se realiza como parte de la Prueba de clasificacion para orientar y ser tutor de clases python. En ideas generales  el juego está escrito en un lenguaje de programación Python , donde la libreria raiz es pygame.Este proyecto ha sido creado basado en un proyecto guía Open-source de pokemon verde-esmeralda dispuesto en github.
## Descripcion
El juego trata de emular de manera muy sencilla uno de los juegos de Nintendo mas jugados en la historia ; pokemon rojo fuego. El juego cumple con los requisitos propuestos por el entrevistador debido a que:
## 1. Su proyecto debe incluir funciones personalizadas. La creación de clases es opcional :
El proyecto cuenta con funciones personalizadas que le permiten al usuario elegir el personaje con el que quiere jugar , basada en esta decision se desbloquean dibujos , elementos de interaccion y movimientos caracteristicos que aportan una mejor jugabilidad, se crearon varias clases ; Pokemon y movimientos con sus respectivos atributos
## 2. El juego debe contar con varias funciones, menús y enemigos : 
La interfaz del juego le permite al usuario elegir un pokemon dentro de los 6 disponibles, existe el menú que le da la posibilidad de curar su pokemon o combatir, desbloqueando una gama "real" apegada a la serie de pokemon de ataques caracteristicos de ese pokemon que puede usar. En cuanto a los enemigos , el juego escoge un rival aleatorio y ataca con uno de sus ataques caracteristicos de manera automatica , creando mas de 24 posibilidades de enfrentamientos enemigos, hablando de las funciones , el jugo tiene en cuenta la logica pokemon implementada en la serie , pues segun los ataques y los pokemon , se calculan los golpes caracteristicos y criticos , asi como los que no influyen, esto dentro del codigo son funciones personalizadas basadas en un api de pokemon. 
## Instalación
Es de resaltar que se debe contar con **acceso a internet** estable para la consulta de la API de pokemon de la siguiente url : */ 'https://pokeapi.co/api/v2' /* donde dispone de toda la información de cada pokemon y su posible relación con los otros a los que se enfrenta, Se debe tener una version instalada de **Python 3.8** o superior. 
-- Las librerias necesarias para ejecutar el código de python deben ser las siguientes:

```bash
pip install pygame
pip install requests
```
Se debe tener en cuenta que tambien se usan las librerias **io** time, math ,random y urllib, pero estas vienen por defecto en las bibliotecas standart de python >> 3.8. 
## USO
Para ejecutar el juego se debe asegurar de contar con un entorno virtual con todas las dependencias indicadas previamente, luego es posible ejecutar el script llamado **Juego.py** situado en este repositorio usando python >>3.8. Se abrirá una interfaz para elegir el pokemon con el cual el usuario quiere competir. De manera subsecuente , el rival (CPU) escogerá otro pokemon y se podrpá combatir o usar pociones para curar nuestro pokemon, los movimientos de ataque son los reales propuestos por la serie y funcionarán bajo mecánicas similares. El objetivo será derrotar al oponente antes de que se debilite nuestro Pokemon y es posible iniciar un nuevo combate con otro pokemon. Esperamos que se fivierta con este pequeño Juego y saque sus dotes de maestro Pokemon :smirk_cat::fire:

##Troubleshooting:
Algunos problemas comunes por lo que puede no correr muy bien el script :
- Conexión inestable a internet
- Falta de librerias o dependencias


