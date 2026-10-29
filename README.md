Modificacion de Pacman.py
Master: Diego Lemus Mejía, A01665486
Usuario de Git: a01665486-debug
Fork: Yerik Escobar Asprón, A01829079
Usuario de Git: Yeaspron

Este repositorio contiene una adaptación del videojuego Pacman de Free Python Games, desarrollado en Python con Turtle. El objetivo es mejorar el comportamiento de los fantasmas, modificar el tablero y aumentar la velocidad de los fantasmas mediante trabajo colaborativo con Git y GitHub.
Fuente original: Pacman de Grant Jenks.

Reparto de funcionalidades:

Diego:  fantasmas más inteligentes(pendiente)
	feat/fantasmas-inteligentes(pendiente)	
	feat: orienta fantasmas hacia Pacman en los cruces(pendiente)
Yerik:  Modificar el tablero(pendiente
	feat/tableo	feat: modifica distribucion del tablero
Yerik	Aumentar la velocidad de los fantasmas	feat/velocidad-fantasmas	feat: aumenta velocidad de fantasmas con dos subpasos:
El código inicial se obtiene con python -m freegames copy pacman y se conserva en el primer commit, antes de realizar modificaciones.

Requisitos
- Python 3, Git y una cuenta de GitHub.
- Turtle y Tkinter disponibles en la instalación de Python.
- En Windows: Ubuntu en WSL 2 con soporte para aplicaciones gráficas.

git clone https://github.com/a01665486-debug/pacman-equipo.git
cd pacman-equipo
python pacman.py

Controles:

   |Tecla|             	           |Acción|
Flecha derecha  	Mover a Pacman hacia la derecha
Flecha izquierda	Mover a Pacman hacia la izquierda
Flecha arriba   	Mover a Pacman hacia arriba
Flecha abajo	        Mover a Pacman hacia abajo

