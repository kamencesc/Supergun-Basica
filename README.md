# Supergun-Basica
Diseño de una Supergun básica.

## Que es un Supergun?
Un Supergun nos permite conectar las antiguas placas de máquinas recreativas a un sistema adaptado, como puede ser a una TV, un monitor LCD, usando Gamepads de consolas, etc...

## Que hace este Supergun?
Tengo otro repositorio en el que intento crear una supergun lo mas completa posible, pero todo empieza por una base y este reprositorio es ela base del otro, por lo tanto tiene unas prestaciones muy básicas, como su propio nombre indica.

Dos puertos para joysticks arcade de 6 botones, 4 direcciones, Start y Select.

Entrada de 6 pins para conecta un Kick Harness.

Botón para seleccionar si jugar con el botón 6 del Kick Harness o de la placa arcade (ej. Bluelf)

Cambio de botones via hardware, nos permite poder cambiar la entre dos distribuciones de botones en el caso de usar un CPO del tipo 6 botones como los de Capcom. Mediante este cambio podemos asignar los 6 botones para usar un juego de lucha de Capcom (modo normal) o bien usar los dos primeros botones de la izquierda de las dos hileras, para juegos de lucha de NeoGeo de 4 botones.

Salida Jack de 3,5" con selector para audio MONO o STEREO

Salida de video mediante terminales de tornillo, directa del connector JAMMA para su posprocesado externo (ej. usando una GBS8200 y adaptar video de CGA a VGA)

Entrada de corriente mediante terminales de tornillo, +5V +12V -5V y GND. Los -5V no suelen usarse pero lo dejamos por si alguna placa lo requiere.

La placa integra un connector para Kick Harness de CPS2 y así no tener que ir haciendo bricolaje. Este connector tiene que ir arrimado a la derecha del Kick Harness en el modulo CPS2.

# Agradecimientos
En este proyecto se ha usado el conector Jamma disponible en **Shinichi-Ohki** y disponible en su GitHub: https://github.com/Shinichi-Ohki/JAMMA_connector_for_eagle

Teneis un fork de su proyecto en mi github en el que he integrado conectores inversos (los que usa este supergun) y he suprimido el texto (que ademas tenia en la misma cara y lo hacía inteligible): https://github.com/kamencesc/JAMMA_connector_for_eagle

Los "pañeros" de _Crazy Lab_ por aguantar mis preguntas tontas...

**UNTESTED**
