# sesion-09a

Apuntes de clase online — Diseño PCB en KiCad

Recordatorios:

+ Alt + 3: abrir visor 3D.
+ La capa Edge.Cuts: contorno de la PCB.
+ Se utilizarán 7 capas:
+ 1 capa de contorno: Edge.Cuts
+ 2 capas de cobre: F.Cu (frontal) y B.Cu (trasera)
+ 2 capas de silkscreen
+ 2 capas de mask
+ La parte frontal de la PCB se enfoca más en la estética, mientras que la parte trasera se relaciona más con el funcionamiento.
+ Click derecho → alinear.
+ El terminal block se utiliza para conectar la batería a la PCB.

+ Terminal block:   es un componente modular con un marco aislado que une de forma segura y ordenada dos o más cables eléctricos. Se utilizan para fijar, conectar y distribuir conductores en tableros eléctricos y dispositivos industriales. 

## Contorno PCB

La clase comenzó con la creación del contorno de la PCB. Esto se realiza en la capa Edge.Cuts, utilizando la herramienta de rectángulo. Luego, se hace doble click sobre el rectángulo para ajustar sus dimensiones y redondear las esquinas.
El siguiente paso fue acomodar los componentes dentro del contorno creado. La idea de esta etapa es ordenar los componentes de manera estética y funcional, por lo que se recomienda ir revisando constantemente el visor 3D para observar cómo se verá la PCB físicamente.

![pcb](./imagenes/pcb.jpg)

## Pistas 

Después comenzamos a trabajar con las pistas, que son líneas de cobre dentro de la PCB y funcionan como “cables planos”. Estas se trabajan principalmente en la capa F.Cu, que corresponde a la parte frontal, mientras que B.Cu corresponde a la parte trasera de la PCB.


![route](./imagenes/route.jpg)

![pistas](./imagenes/pistas.jpg)

Se recomienda trabajar con dos medidas de pistas:

- 0.4 mm
- 0.8 mm

Para enrutar pistas se utiliza la herramienta de trazado de pistas, donde también se puede configurar el grosor.
Primero aprendimos a realizar las conexiones positivas utilizando pistas de 0.8 mm. Luego, usamos pistas de 0.4 mm para las conexiones entre componentes.
Cuando las conexiones se cruzan, las pistas no pueden pasar una encima de otra en la misma capa. Para solucionar esto, se puede cambiar a la capa trasera de la PCB o también utilizando una vía.

Una vía es una conexión que une la capa frontal (F.Cu) con la capa trasera (B.Cu). Mientras se está trazando una pista, si esta se cruza con otra, se puede crear una vía para continuar el recorrido por la parte trasera y así evitar cruces. Con la tecla V se puede cambiar entre la capa frontal y la trasera durante el trazado.
Si hacemos click en una vía, también es posible modificar su tamaño. 

## Flusser, capítulo 1 

Vilém Flusser fue un filósofo y escritor checo-brasileño que trabajó temas relacionados con la comunicación, las imágenes y la tecnología. En sus textos reflexiona sobre cómo los medios técnicos cambian nuestra manera de pensar y de relacionarnos con la realidad.

En este capítulo se habla de cómo las imágenes, la escritura y la tecnología cambian la forma en que entendemos el mundo. Vilém Flusser parte hablando de la fotografía, pero en realidad se refiere a algo mucho más grande, que es cómo los medios técnicos como las cámaras, el cine, el video o las computadoras terminan influyendo en nuestra forma de pensar y también de vivir.

Habla de las “imágenes técnicas”, que serían imágenes hechas mediante aparatos tecnológicos y no solamente por la mano humana, como pasa con una pintura o un dibujo. Entonces la cámara no sería algo totalmente neutral, porque igual condiciona lo que podemos hacer y cómo vemos las cosas.

Flusser diferencia dos formas de pensamiento:

+ el pensamiento mágico: relacionado con las imágenes
+ el pensamiento histórico o lineal: relacionado con la escritura

Me deja pensando esto, porque hoy estamos rodeados de imágenes y tecnologías que influyen mucho en cómo mostramos nuestra vida y en cómo vemos la realidad. Pero igual me surge una duda, porque la fotografía para mí es importante y tiene un valor más personal, ya que me ayuda a guardar recuerdos y a mantener parte de mi historia. Siento que ahí la imagen no reemplaza la realidad, sino que la acompaña. Aunque ahora, con las redes sociales, a veces esas imágenes también se usan más para mostrar o “publicar” la vida que para recordarla realmente y me hace preguntarme si la fotografía realmente captura el momento tal como es, o si termina mostrando más lo que queremos aparentar. 
