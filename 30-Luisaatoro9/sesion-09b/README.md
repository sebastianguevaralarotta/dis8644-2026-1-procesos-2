# sesion-09b 15 de mayo

Componentes Propios y el Proyecto de Filtros 

### Correcciones: Lo que no hay que hacer

En la clase de hoy repasamos los errores típicos que nos pasaron a todos. Lo más importante, es que si cambio algo en el esquema (como el valor de una resistencia), la placa no se actualiza sola. Tengo que darle a "Actualizar placa desde esquema" o voy a terminar mandando a fabricar algo que no sirve.

También vimos lo de las islas de cobre. Cuando relleno con GND, a veces quedan pedazos de cobre sueltos por ahí. Si tienen una X, es que están mal porque no pueden disipar calor. Tienen que tener al menos 3 conexiones para estar bien.

Esto fue lo más pro de la clase. A veces el componente que necesitas no existe o las patitas están en otro orden.

* **Editor de Símbolos:** Aprendí que NUNCA hay que editar el original porque arruinas todos mis proyectos.
* **Hacer un Fork:** Básicamente es copiar un símbolo a mi propia biblioteca (.kicad_sym) y ahí sí, cambiarle lo que quiera con la tecla E o mover pines con la tecla M.
* **Tip:** Si veo un asterisco (*) arriba, tengo que guardar los cambios.

### Nuestra Solemne: El Grupo de Filtros 

Escogimos el tema de filtros, estuvimos investigando qué componentes nos sirven para procesar audio o señales. Para esto, no nos basta con el NE555, necesitamos Amplificadores Operacionales (Op-Amps).

### Propuestas de chips para nuestro circuito:

* **TL072:** Sería ideal para un filtro activo.
<img width="888" height="394" alt="image" src="https://github.com/user-attachments/assets/dceac75e-1769-4114-b234-ce965c1f19f8" />

* **LM358:** Muy común y barato, perfecto si queremos hacer algo más sencillo pero que funcione de una.
<img width="888" height="394" alt="image" src="https://github.com/user-attachments/assets/a4fdb2e8-a644-4028-931a-ba6baf637c77" />

Glosario rápido de lo que aprendí
1. DRC (Design Rule Checking): Es el "policía" del programa que me dice si las pistas están muy juntas o si algo va a explotar.
2. Gerber: Es el formato final. Es como el "PDF" de las placas, se lo mando a la fábrica y listo.

### Referencias

- [KiCad — editor de símbolos](https://docs.kicad.org/master/en/eeschema/eeschema.html#symbol-editor)
- [Tipos de interruptores — push vs switch](https://www.electronics-tutorials.ws/io/io_1.html)
- [3PDT switch — cómo funciona en pedales de guitarra](https://www.electrosmash.com/boss-ds1-analysis)
- [Huellas DIP en KiCad](https://docs.kicad.org/master/en/pcbnew/pcbnew.html)
