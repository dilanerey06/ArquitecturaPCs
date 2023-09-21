# Proyecto 2
<img src="/img/alu.jpg"  alt="alu"/>
En este proyecto se contruirá una parte importante de la unidad central de procesamiento(CPU), la ALU o unidad aritmetica lógica. Se contrunstruirá gradualmente un conjunto de chips que comprenden la parte de suma artmética culminando con la construcción de la ALU.<br/>
Se contruirán los siguientes chips: 
<ul>
  <li>HalfAdder</li>
  <li>FullAdder</li>
  <li>Add16</li>
  <li>Inc16</li>
  <li>ALU</li> 
</ul>

Los chips que se pueden usar son los ya hechos en el proyecto 1 y los chips que se van contruyendo en este. 
<h3>Plan de implementación</h3>
Hack ALU calcula un valor de 16 bits denominado. Además, calcula dos “valores de estado” de 1 bit.
salidas” llamadas zr y ng. Se sugiere contruir la ALU en dos partes, Primero, implemente una ALU básica
eso se calcula, ignorando las salidas zr y ng. Luego implemente una versión final que calcule
out así como zr y ng.
<h3>Tips</h3>
Para el desarrollo del proyecto se utiliza el software de Nand to Tetris que se descarga desde la página oficial, se extrae en una carpeta y se accede a nand2tetris/projects/02 donde se encuentran todos los archivos necesarios para el desarrollo del proyecto.
las compuertas pueden ser implementadas en más de una forma, pero siempre hay que buscar la construcción más sencilla y con menos partes posibles.
