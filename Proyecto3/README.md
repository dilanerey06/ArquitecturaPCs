# Proyecto 3
<img src="/img/ram.PNG" alt="ram"/>
En este proyecto se construye la memoria principal del computador, también llamada "Memoria de Acceso Aleatorio", o RAM. Consiste en una secuencia de registros y cada uno está diseñado para alamacenar valores de n-bits.
Se construirá gradualmente una unidad de RAM. Esto lleva dos problemas: (1) Usar compuertas lógicas para almacenar constantemente bits y (2) usar compuertas lógicas para localizar o encontrar el registro de memoria con el que se desea operar.<br/>

Se construirán los siguientes chips: 

<ul>
  <li>Bit</li>
  <li>Register</li>
  <li>RAM8</li>
  <li>RAM64</li>
  <li>RAM512</li>
  <li>RAM4K</li>
  <li>RAM16K</li>
  <li>PC</li>
</ul>
Los únicos chips que se pueden usar son los listados en los proyectos 1 y 2 y los chips que se van construyendo a medida de que se avanza en este proyecto.

<h3>Estructura de la carpeta del proyecto</h3>

Cuando se construyen los chips de RAM desde partes de más bajo nivel, se recomienda usar versiones ya creadas. De otra forma, el simulador recursivamente generará muchos objetos del software que residen en la memoria. Esto puede causar que el simulador vaya lento, o, peor, se quede sin memoria el computador local en el que se está ejecutando el simulador. Para evitar este problema, se dividieron los chips en dos subcarpetas. Esto está hecho con el propósito de que cuando se evalúe los chips de la ram almacenados en la carpeta "b", el simulador usará implementaciónes construidas internamente del chip RAM64, simplemente porque RAM64.hdl no se encuentra dentro de la carpeta "b".
