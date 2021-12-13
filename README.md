# TVDigitalChile01
Archivos necesarios para visualizar TV Digital ISDB-T en Linux (Con un sintonizador compatible)
 
En el caso de querer generar un nuevo playlist (Este fue generado en la region metropolitana)

Instalar la utilidad para sintonizar TV Digital

sudo apt install dvb-apps

Instalar el reproductor VLC

sudo apt install vlc
 
Descargar el archivo "tables" que comparto aca.
Fue copiado de https://www.linuxtv.org/wiki/index.php/ISDB-T_Frequency_Table

Ejecutar

scan tables > channels.conf
Al terminar el escaneo, con el archivo generado "channels.conf" ejecutamos VLC

vlc channels.conf

Guardar la playlist generada.
Nota, la playlist generada, al guardarla, no almacena los nombres de los canales, debes editarla y guardar los cambios para cada canal.

Voilà

