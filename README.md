# Hell Unleashed - Doom 3 Mod

**Hell Unleashed** es un mod de horror y supervivencia para Doom 3 que intensifica la experiencia de juego original, acercándose más a la intención de supervivencia que a la acción rápida de las primeras dos entregas. Sumergirá al **marine** en una atmósfera mucho más oscura y aterradora. Este mod ha sido diseñado para funcionar con el _source port_ **Dhewm 3** y utiliza la capa **Redux** como selector de interfaz. El mod está diseñado para funcionar con la versión de lanzamiento original del año 2004 y no con la relanzamiento de 2012, la BFG Edition. Esto se debe a que el Doom 3 original fue el último videojuego de ID Software en hacer su código abierto, lo que permite su funcionamiento con el _source port_ de la comunidad **Dhewm 3** para ejecutarlo con modificaciones. A diferencia de la BFG Edition, que no está diseñada para ser de código abierto.

**<a href="https://roberrtoia.github.io/Hell-Unleashed/" target="_blank">Weapon Showcase</a>**
Click [here](https://www.geeksforgeeks.org/){:target="_blank"} 
to visit GeeksForGeeks website.

### Características Principales

-   **Atmosfera Intensificada:** Este mod transforma Doom 3 en una experiencia de horror más extrema, con armas, un sistema de combate y enemigos reajustados para un gameplay más asfixiante.
    
-   **Compatibilidad con Dhewm 3:** **Hell Unleashed** ha sido desarrollado para ser jugado con el _source port_ Dhewm 3, lo que permite ejecutar mods externos simultáneamente.
    
-   **Redux:** La capa Redux proporciona efectos y texturas actualizados a los estándares actuales, ofreciendo mejores efectos visuales y una proporción de 16:9 (el juego original se ejecutaba en un aspecto de 4:3). El mod se ejecuta seleccionando Redux en la pantalla de inicio. Aunque es posible ejecutarlo directamente con Dhewm 3, perderías las características de la capa Redux.


## Requisitos del Sistema

-   **Sistema Operativo:** Windows XP, Vista, 8, 8.1 sin Redux. Windows 10 y 11 con Redux
-   **Doom 3:** Versión 1.3 o superior [Doom 3 Steam](https://store.steampowered.com/app/208200/DOOM_3/) 
-   **Dhewm 3:** Version 1.5.1 o superior [https://dhewm3.org](#)
-   **Redux:** [https://www.moddb.com/mods/doom-3-redux](#)


## Instalación

### 1. Instalar Dhewm 3

1.  Descarga la versión más reciente de **Dhewm 3** desde su repositorio oficial: [https://github.com/dhewm/dhewm3/releases/](#).
2.  Extrae los archivos en una carpeta de tu elección.
3.  Copia los archivos de Doom 3 desde la carpeta `base` (es decir, los archivos `pak000.pk4` a `pak008.pk4`) al directorio `base` de **Dhewm 3**.
4.  Extrae el archivo del parche en la carpeta `base` de **Dhewm 3**.
5.  Si deseas que Steam registre tus horas de juego y desbloquee logros, realiza este proceso en el directorio de instalación de Doom 3 de Steam.


### 2. Configurar Redux

1.  Descarga la **Redux** desde [https://www.moddb.com/mods/doom-3-redux](#).
2.  Extrae los archivos y coloca la carpeta de Redux en el directorio raíz de **Dhewm 3**.
3.  Para una guía más detallada, puedes ver el siguiente tutorial: https://www.youtube.com/watch?v=VSu2x41rHTQ&t=192s.


### 3. Instalar Hell Unleashed

1.  Descarga el mod **Hell Unleashed** desde el enlace de [Google Drive](https://drive.google.com/drive/folders/1SW7ppMkqu_keK48sNbnJqUiVwNlcCPJ6?usp=sharing) (los archivos son demasiado pesados para alojarlos en un repositorio de archivos como github).
2.  Extrae el contenido en la carpeta dentro del directorio de **Dhewm 3**.
3.  Inicia **Dhewm 3** y selecciona **Redux** desde el menú de selección de mods.
4. En la carpeta `optional`, puedes colocar el archivo `zzzzzz_double_barrel_shotgun.pk4` en la carpeta `base` de **Dhewm 3** para acceder a la escopeta de doble cañón en los niveles `admin`, `delta4`, `delta5` y `hell1`. Aún está en una fase muy temprana de desarrollo. Arrastra consigo una versión antigua del HUD que no está en HD y solo permite seleccionar el arma con la rueda del ratón. Además, puede presentar algunos problemas de conteo de munición al llegar a 0 si aún hay munición en el cargador de la escopeta estándar.


## Características Detalladas

### Enemigos

Enemigos rebalanceados para una experiencia de supervivencia. Se ha eliminado el efecto de `sacudida` al ser atacado y el daño ha sido aumentado para una mejor legibilidad del combate. El demonio `imp` ahora tiene un ataque doble. En general, los enemigos hacen más daño pero caen más rapido.

### Armas y Equipamiento

Re-balanceo de daño, munición, cargadores y estética de las armas. Ahora se cuenta con el clic izquierdo del ratón para apuntar, mientras que normalmente se disparará desde la cadera. Si se dispara desde la cadera, ahora existirá una dispersión, mientras que si se apunta, se reduce a casi 0. Ahora se incentiva más la exploración en los escenarios. Todas las armas tienen nuevos sonidos.

1.  Pistola: Ahora usa 7 balas por cargador, con un total en el inventario de 28 balas, más las que se encuentran en el arma, sumando un total de 35 balas. El daño se ha incrementado significativamente, pero con mucha menos munición. Ahora se comporta como una magnum. La munición pequeña otorga 3 balas, y la munición grande otorga 5 balas.

2.  Escopeta: Ahora usa 5 balas por cartuchos, con un total en el inventario de 25 cartuchos, más los que se encuentran en el arma, sumando un total de 30. Ahora es una escopeta verdaderamente funcional a corta y media distancia, con el daño aumentado en un 1.9x y una dispersión reducida en un 80%. La munición es ahora mucho más escasa para compensar su enorme efectividad. La munición pequeña otorga 1 cartucho y la munición grande otorga 3 cartuchos.

3.  Ametralladora: 30 balas por cargador, con munición pequeña de 15 balas y munición grande de 20 balas, respectivamente. Daño aumentado en un 1.25x.

4. Lanzacohetes: Ahora cuenta con 4 misiles por cargador, más 20 en el inventario. Daño aumentado en un 2x. La munición pequeña otorga 1 misil y la munición grande otorga 2 misiles.

5. Cañón de cadena: Ronda de 60 balas en el arma, más 160 en el inventario. Daño reducido a 0.75x y velocidad de disparo aumentada a 2x.

6. Granada: El número de granadas disponibles se ha reducido a 10. El rango de explosión ha sido aumentado a 2x.

7. Fusil de plasma. Daño aumentado en un 1.65x. Cadencia reducida a 0.8x. Cargador de 35 proyectiles, con un inventario de 135 proyectiles. El cargador pequeño contiene 10 proyectiles, y el cargador grande 15 proyectiles.

8. BFG: 4 cargas en el arma, más 16 en el inventario. Únicamente se ha modificado el sonido. El cargador pequeño otorga 1 proyectil, y el cargador grande 2 proyectiles.

9. Cubo de las almas: Ahora se recarga con 3 enemigos en lugar de 5.


### Mejoras gráficas

Texturas mejoradas con IA:

![Alt Text](https://github.com/RoberrtoIA/Hell-Unleashed/blob/main/Doom%203%20comparasion%201.gif)

![Alt Text](https://github.com/RoberrtoIA/Hell-Unleashed/blob/main/Doom%203%20comparasion%202.gif)
