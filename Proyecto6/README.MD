# Proyecto 6  
Programas de bajo nivel escritos en maquinas de lenguaje simbólicas son llamadas programas de ensamblador. Los programadores rara vez escriben programas directamente en lenguaje de maquina. Más bien, los programadores que desarrollan programas de alto rendimiento inspeccionan el codigo de ensamble generado por los compiladores. Se hace para entender su codigo de alto nivel que es desplegado en el hardware y como ese código puede ser optimizado para ganar más rendimiento. Uno de los involucrados en este programa que se encarga de traducir codigo escrito en lenguaje de maquina simbolico a codigo escrito en lenguaje binario de maquina. Este programa es llamado un ensamblador 

<h3>Objetivos </h3>
Desarrollar un ensamblador que traduzca programas escritos en el lenguaje ensamblador Hack a Hack.
código binario. Esta versión del ensamblador asume que el código ensamblador fuente es válido. Error
La verificación, los informes y el manejo se pueden agregar a versiones posteriores del ensamblador, pero no son parte
de este proyecto.

<h3>Recursos</h3>
La principal herramienta necesaria para completar este proyecto es el lenguaje de programación en el que
implementar su ensamblador, siguiendo las especificaciones y APIs descritas en la conferencia correspondiente
y el capítulo 6 del libro. Además, necesitará el ensamblador suministrado para comparar el código binario.
código generado por su ensamblador al código generado por el ensamblador suministrado. Y si tu
desea ejecutar el código traducido e inspeccionar su comportamiento, puede hacerlo usando la CPU
emulador.

<h3>Programas Test</h3>

<ul>
  <li>Add.asm: Adds the constants 2 and 3, and puts the result in R0.</li>
  <li>Max.asm: Computes max(R0, R1) and puts the result in R2.</li>
 <li> Rect.asm: Draws a rectangle at the top left corner of the screen. The rectangle is 16 pixels wide,
  and R0 pixels high. Before running this program, put a non-negative value in R0.</li>
  <li>Pong.asm: A classical single-player arcade game. A ball bounces repeatedly off the screen’s "walls."
  The player attempts to hit the ball with a paddle, by pressing the left and right arrow keys. For
  every successful hit, the player gains a point and the paddle shrinks a little, to make the game more
  challenging. If the player misses the ball, the game is over. To quit the game, press ESC. Note: The
  Pong program was developed using tools presented in Part II of the course and the book. In
  particular, the game software was written in the high-level Jack language, and translated into the
  given Pong.asm file by the Jack compiler. Although the high-level Pong program is only about 300
  lines of code, the executable Pong application is about 20,000 lines of binary code, most of which
  being the Jack operating system. Before running the code, select ‘No animation’ from the
  ‘Animation’ menu (meaning, no code highlighting). You can control the code’s execution speed
  using the speed slider. The game will start after a few seconds, during which the OS initializes.</li>
</ul>
