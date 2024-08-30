# bspwm

<b>bspwm</b> es un gestor ventanas (Window Manager) que se encarga de gestionar, siendo redundantes, las diferentes ventanas que van a ser visibles por el usuario cuando pase la ventana de logeo.
Permite customizar desde las aplicaciones que se van a arrancar al iniciar sesión en el sistema, hasta tener diferentes escritorios dentro de una misma pantalla.<br>
Es bastante personalizable y viene sin prácticamente nada, lo que permite que se puedan empezar a añadir fácilmente otros programas de terceros (feh, polybar, entre otros) para personalizar al detalle el entorno de linux.
<br><br>
Este es un archivo personalizado que tiene la configuración que he considerado relevante por el momento y que voy a usar en mi entorno.
Para poner bspwm operativo, hay que poner el fichero <b>bspwmrc</b> en ~/.config/bspwm/ y cambiar el "método de logeo" para que utilice bspwm.
Es recomendable que si es la primera vez que utilizas bspwm, añadas el siguiente comando al final del todo del bspwmrc: <b>/bin/bash</b><br><br>
Esto ejecutará una terminal al abrir bspwm por primera vez y te permitirá retocar cosas sin tener que instalar programas de terceros para abrir una terminal.
También, para que bspwm sea funcional, es imprescindible tener el fichero sxhkd, ya que éste es el que gestiona todo lo relacionado con los atajos de teclado para moverse por el sistema.
