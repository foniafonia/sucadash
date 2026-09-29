# Sucá Dash

Juego 3D de vocabulario de Sucot inspirado en el mapa Block Dash / Laser Dash de Stumble Guys.

Desde la sucá del fondo llegan oleadas que barren una plataforma de neón:

- **Muro de palabras:** solo el bloque correcto se deja atravesar; los demás te empujan al vacío. Se alternan tres formas: dibujo de Sucot arriba y palabras en español; dibujo arriba y palabras en hebreo; palabra en hebreo arriba y dibujos en los bloques. Si fallas, el juego dice cuál era (en hebreo y en español).
- **Pinchos:** salen del suelo (un círculo rojo avisa antes) y algunas palabras incorrectas los llevan en la parte baja. Si los tocas te caes al suelo un momento.
- **Doble salto:** muro alto con bloques bajos delante. Se salta al bloque bajo y desde ahí al muro alto.
- **Escalera:** tres peldaños que se suben saltando.
- **Vallas:** tres barras bajas seguidas.
- **Pistones:** columnas que suben y bajan; se pasa por la que esté abajo.
- **Trampolín:** una cama elástica lanza por encima de un muro muy alto.
- **Láseres:** salen del fondo y vienen hacia ti. Los verdes van a ras de suelo y se saltan; los rosas son verticales y se esquivan.

- **Bordes:** los láseres verdes de los lados electrocutan. Tocarlos cuesta una vida.

El juego ocupa toda la pantalla y va en horizontal: el botón JUGAR activa la pantalla completa, y en un móvil en vertical la imagen se gira sola. Dentro de la sucá hay una mesa de fiesta (jalot, copa de kidush, vino, velas, frutero) y en el cielo luna llena.

Los personajes son cabezones de dibujo animado con contorno (ojos con brillo, mejillas, manos y zapatos) y llevan kipá, talit katán con tsitsit, talit gadol con atará, tefilín, peot, sombrero negro o barba; hay también dos niñas.

Todos los jugadores tienen dos vidas; quien las pierde queda eliminado y, si quedas el último, sale «¡GANASTE!». Si te eliminan, la cámara sigue a los que quedan. A partir de la oleada 4 los láseres pueden llegar a la vez que los bloques.

- **Doble salto y salvadas:** se puede saltar otra vez en el aire. Si un muro te empuja al borde, saltas dos veces y te subes encima.
- **Cajas misteriosas y botellas:** dan un poder al azar: escudo (protege y te rescata de una caída), rayo (electrocuta al jugador más cercano), puño (lanza al de delante) o turbo. Los bots también las usan.
- **Cámara:** tres vistas (cerca, lejos, desde arriba), entrada de cine al empezar.
- **Emotes:** bocadillos como «¡Jag Saméaj!» o «GG» con saludo.

Contador de oleadas y pantalla final con el tiempo. Una barrera invisible al fondo, junto a la sucá, empuja hacia atrás a quien intente esconderse allí.

Vocabulario: lulav (לוּלָב), etrog (אֶתְרוֹג), sucá (סֻכָּה), palmera (דֶּקֶל), granada (רִמּוֹן), uvas (עֲנָבִים), estrella (כּוֹכָב), luna (יָרֵחַ), Torá (תּוֹרָה), farol (פָּנָס).

## Cómo abrirlo

Abre `index.html` en un navegador actual (Chrome, Safari o Edge). Necesita conexión la primera vez para cargar Three.js (cdnjs) y las fuentes. La demo juega sola hasta que tocas un control.

Controles: joystick en pantalla o flechas/WASD para moverse; botón B o espacio para saltar (dos veces para doble salto); USAR o E para el poder; C cambia la cámara; T hace un emote.

## Stack

Un solo archivo HTML. Three.js r128 desde cdnjs, fuentes Lilita One y Rubik (hebreo) desde Google Fonts; gráficos, iconos y física escritos a mano. No guarda datos.

## Pendiente

Pantalla de inicio y elección de personaje, niveles de dificultad (distractores de otra categoría → misma categoría → palabras que suenan parecido), música y voz opcional, más vocabulario.

No se ha localizado el motor «codecar» mencionado en otro hilo; este usa un motor propio.

## Tienda, skins y pase de batalla

Al terminar cada partida se ganan monedas y XP según los aciertos y la oleada alcanzada. Con las monedas se compran skins (cambian el color de la camisa y el pantalón) en la Tienda, accesible desde la pantalla de inicio y desde la de «¡Eliminado!». El XP sube el Pase de Batalla (10 niveles); en el nivel 5 y el 10 se desbloquea una skin especial gratis. Todo se guarda en `localStorage` del navegador: es una economía del propio juego, sin pagos ni conexión a ninguna tienda real.
