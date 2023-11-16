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
  <li>Add.asm: suma las constantes 2 y 3 y coloca el resultado en R0.</li>
  <li>Max.asm: Calcula max(R0, R1) y coloca el resultado en R2.</li>
 <li> Rect.asm: Dibuja un rectángulo en la esquina superior izquierda de la pantalla. El rectángulo tiene 16 píxeles de ancho,
  y R0 píxeles de alto. Antes de ejecutar este programa, ponga un valor no negativo en R0.</li>
  <li>Pong.asm: un clásico juego arcade para un jugador. Una pelota rebota repetidamente en las "paredes" de la pantalla.
  El jugador intenta golpear la pelota con una paleta presionando las teclas de flecha izquierda y derecha. Para
  Cada golpe exitoso, el jugador gana un punto y la paleta se encoge un poco, para hacer el juego más
  desafiante. Si el jugador falla el balón, el juego termina. Para salir del juego, presiona ESC. Nota la
  El programa Pong se desarrolló utilizando las herramientas presentadas en la Parte II del curso y en el libro. En
  En particular, el software del juego fue escrito en el lenguaje Jack de alto nivel y traducido al
  proporcionado el archivo Pong.asm por el compilador Jack. Aunque el programa Pong de alto nivel tiene sólo unos 300
  líneas de código, la aplicación Pong ejecutable tiene aproximadamente 20.000 líneas de código binario, la mayoría de las cuales
  siendo el sistema operativo Jack. Antes de ejecutar el código, seleccione "Sin animación" en el menú
  Menú 'Animación' (es decir, sin código resaltado). Puedes controlar la velocidad de ejecución del código.
  usando el control deslizante de velocidad. El juego comenzará después de unos segundos, durante los cuales el sistema operativo se inicializará.</li>
</ul>
