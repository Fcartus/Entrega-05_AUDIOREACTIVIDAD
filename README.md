# Entrega-05_AUDIOREACTIVIDAD
En este repositorio se podrá observar en detalle el paso a paso y el resultado de distintas iteraciones en distintos contextos, pruebas de sonido, maquinas con funciones MIDI, ondas, esferas, volumenes, colores, capas, entre otras.


La canción que se trabajo y uso como ejemplo del ejercicio fue: Disfruta - La Brigida Orquesta. Aunque originalmente esta canción no es de la brigida sigue siendo una buena version instrumental de orquesta de la canción original ( Cidtronyck - Disfruta (con Matiah Chinaski) ) que a mi parecer llega más y te hace conectar más con la letra por la sensacion auditiva que te generan los instrumentos en vivo.


      PROYECTO PRINCIPAL - ORQUESTA

De primero se manifesto y se siguio el proceso del armado de una orquesta, se ubicaron 11 personas (como los 11 participantes reales de la orquesta), donde se les designaban de igual manera a la realidad los instrumentos (Se utilizo una imagen referencial de un momento grabado en vivo), 4 trompetas; 3 saxos; 1 bateria; 1 tecladista; 1 vocalista y 1 bajo.

Se intervino una imagen con IA donde se describio el objetivo del armado y se boceteo con el fin de que se armara la Orquesta. (imagen referencial en carpeta....) se reemplazaron elementos y se agregaron tarimas para que le de ese aspecto de banda en vivo. 

Luego con herramientas de trazo en illustrator se hicieron capas por cada zona de instrumentos, por ejemplo a cada personaje se le estructuro una cabeza, brazos, torso, piernas, tarima y instrumento, para luego darle la orden de movimiento correspondiente a cada personaje. 

Para darle una fluidez constante tambien las capas separaban instrumentos según el sonido. Se trabajo con 5 pistas de Audio:
      1.  Trompetas altas
      2.  Trompetas bajas
      3.  Coros
      4.  Resto de la canción
      5. Cierre de canción
      
Entonces por ejemplo cuando la pista pase por la zona de una trompeta alta los dos personajes de atrás que simulan ser trompetas altas interactuan, luego cuando pasán a las bajas los otros  2 que les acompañan interactuan, en los coros el vocalista hace el gesto de estar cantando, y los demás personajes interactuan con la base de "resto de la canción" para que la bateria, saxofonistas, el bajista y el teclado no dejen de funcionar y asi genere el dinamismo visual que los caracteriza.

Ahora bien, la visualización final se trabajo con Claude, ¿Por qué no se trabajo con el Sketch.tools?, simplemente porque la plataforma no me permitio en reiteradas ocasiones trabajar bien con las distintas pistas, me presentaban errores y tenia que volver a hacer todo el proceso denuevo de configurarlas, como a su vez tampoco me dejaba guardar el trabajo realizado por exceso de memoria (tiene un tope de guardado de 50mb y solo las pistas pesaban al rededor de 35 mb cada una), entonces entorpecio bastante el trabajo de las pistas y se derivo a esta otra herramienta donde se conformo el HTML desde 0 y según el SVG que ya había realizado en Illustrator donde traían todas las capas que mencione anteriormente (en carpeta de proceso se ve el mockup y proceso de armado y dibujo digital).

Se le termino de agregar un sistema e iluminación que siguiera el ritmo y guiara la luz al sonido que suena en el momento, tambien se agrego un telón de fondo para darle profundidad y una tarima para que de la impresión de estar en altura. 

Además se termino de agregar un sistema para que existan distintas formas de exportado. 


      ITERACIONES

  
En las carpetas adjuntas se pueden apreciar distintos tipos de Iteraciones, todo este trabajo sobre la herramienta oficial de Sketch.Tools. Se pueden ver trabajos con uso de modelos de rhino convertidos en elementos interactivos como desprendimiento de esferasm cascadas, y pulsaciones de ondas, tambien hay un trabajo en especifico que se trata de la interacción a través de ondas sobre una malla de un contorno, donde se superpuso una imagen duplicada, dejando el contorno en la parte posterior de la imagen, utilizando iluminación y disntintos efectos que se ven en la web. 

iteraciones Realizadas: 
            1. Cilindros que desprenden esferas en forma de cascada en relación a pistas de audio individuales
            2. Una tela de araña expansiva que unia hilos en base al transcurso de la pista, utilizando coros como punto de expansión.
            3. Iteraciones de espectogramas con filtros de depth map y thermal, generando así volumenes sobre una malla interactiva.
            4. Iteraciones sobre una imagen de un rostro donde se dividen partes del cuerpo (casco superior, orejas y hombros) que son audioreactivos a los audios individuales que se están trabajando.
            5. Iteraciones de audio en su maximo peak de sonido, donde resaltan las trompetas altas en el espectograma.
            6. Intentos de modelo de esferas interactivas y a su vez se buscaba que interactuaran mediante un espacio parecido a un reloj de arena buscando generar una ilusión optica, tal como el efecto del tunel.
            7. Se intento trabajar como primera idea un rostro interactivo que funcionara con la webcam (este proceso no se pudo desarrollar debido a que la plataforma tiene limites de seguridad en relación a la 
               camára local


      Herramietas que se intentaron ocupar

Al no poseer un midi como tal se intento reemplazarlo por una mesa de dj TRAKTOR S8, donde se vinculaban las perillas como potenciometros de las distintas capas, para esto se tuvo que instalar distintos drivers y plugins para que la herramienta web reconociera la salida y entrada de audio como una pista nativa del computador. El objetivo se logro, pero al poseer tantas perillas y ser tan poca precisa debido a no poseer un cable midi se termino descartando, ya que no era del todo precisa. A su ves tambien se busco reemplazar un teclado MIDI desde un driver/plugin que imitaba la maquina, esta tambien termino fallando. 


      CARPETAS

OJO: Todos los resultados de iteraciones tuvieron que ser grabados con la grabación de pantalla, ya que la plataforma no dejaba respaldarlo por el peso del archivo final (Cuando se buscaba exportar eran un aproximado de 600 a 900 mb por video, a pesar de la espera nunca se terminaba exportando)

1. Proceso Fl: Está carpeta contiene todo el esquema musical, mostrando el paso a paso que se hizo para poder desarrollar y separar la pista (se separo con el programa FL estudio de manera manual). En esta carpeta se puede encontrar tambien cada pista de audio individual con las que se trabajo.
2. PROCESOS DE ITERACIÓN: En esta carpeta se pueden ver todos los procesos de iteracion que existieron antes de llegar a la orquesta en sí. Pruebas de contorno, formas, esacalabilidad constante, cascadas, esferas, elevaciones y entre otros parametros regulables directos desde el HTML
3. ITERACIONES Y RESULTADOS: Lo mismo que el punto anterior, pero esta vez visto en vivo.
4. ARMADO DE ORQUESTA: La carpeta más importante, esta carpeta contiene el proceso mediante screenshots y videos del paso a paso que se siguio para llegar a las formás finales. Tambien se agregan distintas versiones del HTML en cuestión.

  
        SUB-ELEMENTOS VITALES PARA LA CONSTRUCCIÓN

   Al momento de exportar el programa hay 2 documentos claves para la exportación de la letra. (Para lograr coonectar la letra con el video se extrajo un elemento que se saco desde las cookies del navegador web       de la plataforma spotify, se extrajo las letras del Karaoke que tiene integrada la plataforma).
   
      1. URL: Este archivo .py contiene un comando en especifico que detecta la url de la canción.
      2. Letra_sincronizada.lrc: Este archivo contiene el seteo de lo que es la letra, se le entrego como herramienta a Claude para que integrara de manera perfecta la letra con la canción (ocurrian muchos errores al momento de hacer este paso, ya que ninguna de las dos plataformas (sketch.tools y Claude) reconocía el momento instrumental de la canción.


                ¿Como se logro?

   Se creo un archivo .py con el nombre donde previamente se tenia que instalar el codigo en powershell: pip install syrics - Este te generaba una biblioteca que permitia guardar esta clase de archivos.
   Para identificar la herramienta se tuvo que indagar en la consola y rescatar un archivo de las cookies propias de spotify. Se tenia que buscar en elementos - Cookies - y buscar el archivo SP_DC que contenia      la url directa de la canción.
