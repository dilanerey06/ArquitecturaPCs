# Proyecto 5
En este proyecto integrarás los dispositivos ALU y RAM integrados en los proyectos 2 y 3 en una computadora.
Sistema capaz de ejecutar programas escritos en el lenguaje de máquina introducido en el proyecto 4.

<h3>Objetivo</h3>
Construye los siguientes chips: Memory,Cpu,Computer.
<br>Los bloques de construcción que puedes usar son los chips enumerados en proyectos anteriores y los chips enumerados en
este proyecto.
<br>

<h3>Chips</h3>
<ul>
  
  <li>Memory: Las tres partes principales del chip son RAM16K, pantalla y teclado. La pantalla
  y el teclado están disponibles como chips integrados. Aunque el chip RAM16K se construyó en el proyecto 3,
  Recomendamos utilizar su versión incorporada.</li>
  
  <li>CPU: La Unidad Central de Procesamiento se puede construir a partir de la ALU incorporada en el proyecto 2, el Registro y la PC.
  chips construidos en el proyecto 3 y puertas lógicas construidas en el proyecto 1. Sin embargo, como de costumbre, usaremos sus componentes integrados.
  versiones. En particular, utilice los chips ARegister, DRegister y PC integrados. Estos chips incorporados tienen
  exactamente la misma funcionalidad que los chips de registro y de PC integrados en el proyecto 3, pero son necesarios
  para ser consistente con los scripts de prueba del proyecto.</li>
  
   <li>Instruction Memory: utilice el chip ROM32K integrado. Este chip es esencialmente el mismo que la RAM.
  chips construidos en el proyecto 3, pero la versión incorporada tiene una interfaz que permite cargar un programa desde
  un archivo de texto en la memoria.</li>
  
  <li>Computer: Puede construirse a partir de tres partes de chip: CPU, memoria y ROM32K. Los dos primeros chips son
  construido en este proyecto. Este último chip está integrado.</li>
  
</ul>
