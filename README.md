# Novus Spem, prótesis en impresión 3D para extremidad superior y aplicación móvil de geolocalización. 
<p align="justify"> 
  Este documento presenta el diseño y construcción de un prototipo de prótesis de extremidad superior utilizando impresión en 3D, orientado al tiempo de elaboración, uso de materiales que facilite su fabricación y durabilidad, funcionalidad para las tareas de agarre y sujeción de objetos y, la incorporación de componentes computacionales adaptados para una experiencia de monitoreo georeferencial. Se considera la durabilidad de la prótesis ante el desgaste por el ambiente en espacios de temperaturas altas como factor relevante, incluye un revestimiento anti-ínflamable bajo estándares establecidos. Se desarrolla además un aplicativo móvil llamado 
  <a href="https://n9.cl/48g7">NOVUS SPEM</a> , como parte complementaria de la prótesis, para temas de seguridad del usuario, presentando su ubicación y posicionamiento mediante componentes en Arduino a bajo costo. Los resultados de la investigación sobre factores que mejoren la calidad de vida, aspectos funcionales y mejorar el aspecto físico: bienestar emocional y satisfacción del participante también son incluídas. Se pueden encontrar, la aplicación móvil y los resultados de este trabajo en: https://github.com/jchelac/NOVUS-SPEM. 
<a href="https://youtu.be/j3BNdaQn4N0"> AQUI TUTORIAL</a> 
</p>

# Estado del arte 
<p align="justify"> 
  En Ecuador el número de personas con discapacidad llegan a 1636800 de ellas el 46,62% tienen discapacidad fisica, sus  principales causas son por enfermedades adquiridas y problemas al nacer. Al menos quince mil habitantes requieren una protesis, los valores varian entre $7000 a $10000 estas protesis suelen ser  estéticas y poco funcionales, lo que ocasionan problemas psicológicos y sociales
</p>
<p align="center"> <img src="https://github.com/jchelac/NOVUS-SPEM/blob/master/DOC/ESTADISTICA%20DE%20PERSONAS%20CON%20DISCAPACIDAD.PNG"></p>

</p>

# Diseño del prototipo
<p align="center"> <img src="https://github.com/jchelac/NOVUS-SPEM/blob/master/DOC/8.PNG"></p>
</p>
<p align="justify"> En el proceso de construcción de la prótesis se realizó a medida del paciente según las necesidades funcionales. El prototipo base de este estudio es realizado por la comunidad de Thingiverse del proyecto Flexy Hand 2, sobre éste se realiza un diseño optimizado, para las necesidades de nuestro paciente. Se elabora un diseño de prótesis en 3D capaz de alojar componentes en Arduino que permita emitir una señal de geolocalización en tiempo real y permite obtener un reporte de ubicaciones del paciente, con ello es posible un monitoreo contínuo.</p>

# Ensamblaje
<p align="justify">
Para el ensamble de este prototipo vamos a utilizar la unión de los falanges proximal y distal que fueron creados con ninjaflex dichas uniones servirán para conectar la falange proximal, Falange media y la falange distal del índice. También hemos utilizado cordones no elásticos que son pasadas por el orificio,simulan los tendones de la mano, estos son los que nos permitirán cerrar los dedos para coger objetos. Para la unión de la palma con el antebrazo hemos utilizado tornillos, como también el acople del brazo.
  </p>
  </p>
  
  <p align="center"> <img src="https://github.com/jchelac/NOVUS-SPEM/blob/master/DOC/ENSAMBLE.PNG"></p>
  
  
  
# Aplicativo
<p align="justify"> La aplicación móvil fue desarrollada en Kodular para dispositivos Android, permite registrar a una persona por dispositivo GPS disponible, mediante el International Mobile Equipment Identity (IMEI), asociado a un correo electrónico. Para seguridad de la prótesis y del paciente, el aplicativo realiza la grabación de la información, en tiempo real y registra el recorrido
  </p>
  </p>
 <p align="center"> <img src="https://github.com/jchelac/NOVUS-SPEM/blob/master/DOC/APLICATIVO.jpg"></p>
 
# PRODUCTO FINAL 
<p align="center"> <img src="https://github.com/jchelac/NOVUS-SPEM/blob/master/DOC/GITHUB.png"></p>

