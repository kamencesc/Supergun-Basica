# Scart Adapter (jamma rgb2scart)
Con este adaptador tendremos señal de salida en SCART lista para connectar a una TV (no todas son compatibles).

Solo tenemos que llevar los siguientes señales

* R G B
* Sync
* 12V
* Audio R y L (con opción de usar un cable jack-jack, ideal por si usamos placas con salida de audio estereo directo como puede ser CPS2 o algunas MVS)

En la última versión disponible se ha añadido un LM1881 (AKA Sync Stripper) con montaje completamente opcional. El LM1881 usará el canal GREEN (sync on green) para generar una señal de sync mas limpia.

Para que el circuito funcioné como tal deberemos tener los jumpers J1 en posición 1-2 (o un switch si lo prefieres), los componentes son LM1881 en formato DIP8, dos condensadores de 0.1pF, una resistencia de 680k y por seguridad se ha añadido un REG1117 para usar 5V en el LM1881 (aunque tiene una tolerancia de 5-12V)

**UNTESTED**
