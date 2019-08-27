## Supergun con Scart
**UNTESTED**

Se ha realizado una versión del supergun con scart integrado. Este incluye todo lo del supergun básico ~~excepto que en vez de tener los terminales de RGB, disponemos de salida scart~~, seguimos disfrutando de salida jack 3.5" para el audio, si conectamos un jack, el audio del Scart queda deshabilitado.

Se han incluido Screw Terminals para dar salida a la señal directa del connector jamma, ademas de tener un selector de Sync, podemos seleccionar salida desde el potenciometro R10 o directo del jamma. En caso de usar los Screw Terminals y no se quiere instalar el scart, R5, R6, R7, R8 y R9 son completamente prescindibles.

~~Por espacio no se ha añadido un LM1881, sin prescindir de alguna otra opción no hay sitio en el diseño actual de la placa, se podria añadir a modo SMD pero lo que se pretende con esta placa es que sea de fácil montaje, con todos sus componentes DIP (con agujero).~~

Se ha añadido un LM1881 para Syn On Green en el scart, ademas hay un switch para seleccionar usar el LM1881 (CSYNC) o sync directo de jamma, esta última opción es para facilitar el uso con el OSSC.

Al igual que la versión básica se mantiene el Kick Harness para CPS2 (este Kick Harness es solo para los botones de patada y volumen, no para juegos de 4 Players), simplemente recortar las 2 placas adicionales, Soldar los pinheader correspondientes (hembra para la parte de CPS2 y la del supergun depende del usuario), soldar entre ellas los botones de patada del P1 y P2. La parte de CPS2 tiene para mapear botones de volumen (V- y V+).

Añadir que no todas las TVs pueden ser compatibles.
