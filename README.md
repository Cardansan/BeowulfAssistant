# BeowulfAssistant
Repositorio para hacer mi propio asistente de voz.
Ligeramente basado en [este tutorial por 
Sid's E Classroom](https://www.youtube.com/watch?v=mETxgn0vH2I).

-Comando que sirvió para instalar **pip**: 'sudo apt install python-pip'

-No viene en la documentación de Snowboy, pero es necesario instalar esto también: 'sudo apt-get install libatlas-base-dev'

-Para probar el micrófono, graba tres segundos y los reproduce en automático: 'arecord -D plughw:1,0 -V mono -d 3 test.wav && aplay test.wav'

## Enlaces Relevantes
- [Documentación oficial de Snowboy](http://docs.kitt.ai/snowboy/#introduction)
- [Aquí entrenas tu modelo personal de wakeword de Snowboy](https://snowboy.kitt.ai/)
- [Prueba de audio de salida para Raspberry Pi](https://www.tinkerboy.xyz/raspberry-pi-test-sound-output/)
- [Configurar ganancia del micrófono USB](https://learn.adafruit.com/usb-audio-cards-with-a-raspberry-pi/setting-audio-levels)
- [Cómo conectarse a bocinas bluetooth](https://gist.github.com/actuino/9548329d1bba6663a63886067af5e4cb)
- [Switch audio HDMI/Bluetooth](https://www.raspberrypi.org/forums/viewtopic.php?t=173253)
- [Automatically connect trusted Bluetooth speaker](https://raspberrypi.stackexchange.com/questions/53408/automatically-connect-trusted-bluetooth-speaker)

## TODO:
Añadir los pasos y archivos que se editaron para mejorar la detección del comando.

