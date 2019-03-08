# Software Requirements Specification

1. Introducción.	<br/>
  1.1 Objetivo.	<br/>
  1.2 Scope of Project.	<br/>
  1.3 Referencias. 	<br/>
  1.5 Visión general del documento.	<br/>
2. Descripción del diseño.	<br/>
  2.1 Tecnología y entorno de desarrollo. <br/>
  2.2 Requisitos funcionales.	<br/>
  2.3 Requisitos no funcionales.	<br/>
3. Modelo vista-controlador.	<br/>
  4. Arquitectura del sistema.	<br/>
  4.1 Componentes del juego.	<br/>
  4.2 Arquitectura del juego. 	<br/>
5. Referencias.	<br/>


1. Introducción. <br/>

La documentación de este proyecto incluye cómo usar el proyecto y lo necesario para entender el desarrollo del mismo.

1.1. Objetivo. <br/>

Este documento constará de la información y los procedimientos necesarios a seguir para desarrollar el famoso videojuego retro Snake (de un solo jugador).
El jugador será una serpiente cuyo objetivo es sobrevivir comiendo manzanas sin chocarse con las paredes o comerse su propia cola, ya que esto provocará que muera y por lo tanto, se reinicie el juego. 

La serpiente estará compuesta por la cabeza y el cuerpo; en el momento que la serpiente se encuentre con una fruta y la “coma", este crecerá y el jugador ganará x puntos. Para llevar esto a cabo tendremos que saber cuándo la serpiente ha comido una fruta.
La manera de saber esto consiste en que en el momento que la cabeza esté en la misma posición (x,y) que la fruta, consideraremos que la serpiente la ha comido. En este instante, la fruta desaparecerá, la serpiente crecerá y aparecerá una nueva fruta en una posición aleatoria del mapa.
Además, el movimiento de la serpiente se basa en lo que el usuario decide, es decir, la serpiente se moverá en una dirección dada y cada dirección nueva hará que la cabeza gire seguida del cuerpo.



1.2. Scope of Project.<br/>

El trabajo principal es escribir un juego de serpiente usando la programación de java. Este juego generará diversos problemas relacionados con las matemáticas. El jugador tiene que responder las preguntas controlando una serpiente con las teclas del teclado para comer la manzana de respuesta. Cada manzana de respuesta correcta que se come prolonga la vida de la serpiente.

1.3. Referencias. <br/>

1.5. Visión general del documento. <br/>

2. Descripción del diseño.<br/>

2.1. Tecnología y entorno de desarrollo. <br/>
El desarrollo del proyecto se ha llevado a cabo en Netbeans IDE 8.2 utilizando el lenguaje de programación orientado a objetos Java, haciendo uso de clases y objetos.

2.2. Requisitos funcionales. <br/>

	1. El videojuego tendrá un menú que incluirá distintas opciones, entre las cuales están: el comenzar una partida, seleccionar el nivel de dificultad, las instrucciones y por último, la posibilidad de salir del juego.
	2. Al pulsar la tecla “Enter” en el menú el juego iniciará automáticamente.
	3. El jugador podrá controlar la dirección de la serpiente con las teclas “A”,”S”,”D” y ”W”. De manera intuitiva la tecla A será para la izquierda, la S para abajo, la D para la derecha y por último, la D hacia arriba. (o con las teclas de dirección del teclado)
	4. Existirá la posibilidad de parar el juego y ver el menú al pulsar la tecla “ESC”. La única diferencia al menú principal es que este tendrá la posibilidad de reanudar el juego. y no tendrá la posibilidad de cambiar la dificultad.
	5. El juego tendrá sonido, el cual podrá ser muteado gracias a un icono en la esquina superior derecha.
	6. El juego contará con varios niveles, los cuales se irán superando al llegar a la puntuación necesaria.
	7. Cada dos niveles la velocidad de la serpiente incrementará. ¿bonus?
	8. Se generará una fruta en una posición aleatoria del mapa.
	9. Habrá varios tipos de fruta, no solo una.
	10. Acerca del movimiento de la serpiente tendremos varios requisitos funcionales: 
		1. La serpiente debe poder moverse por toda la pantalla.
		2. No existen las vidas, por lo que en cuanto la serpiente se choque con un obstáculo o consigo misma, eljuego termina y se mostrará en la pantalla “Game Over”. 
		3. Cada vez que la serpiente coma una fruta crecerá haciéndose más larga e incrementando la posibilidad de que se choque consigo misma.
		4.La serpiente estará en constante movimiento.

2.3. Requisitos no funcionales. <br/>

	1. El protagonista del videojuego será una serpiente.
	2. Este sistema debería proporcionar la capacidad de operar en un compilador de java junto con la seguridad.
	3. La interfaz fácil de usar y la respuesta rápida.
	4. 
