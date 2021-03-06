# Blender

Blender es un software para modelado 3D, rigging, texturizado... gratuito y libre.

Permite, entre otras cosas, crear nuestros modelos para proyectos orientados en [Unity](https://unity3d.com/es/learn/tutorials). Para más referencias, libro ["Blender: Noob to Pro" en Wikibooks](https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro)... para futuras contribuciones.

Para consultar los modelos creados y otros experimentos, visita el repositorio [mastering3D](https://github.com/Beelzenef/mastering3D).

## _Shortcuts_ útiles

| Tecla o combinación de teclas | Descripción|
|------| :----|
| TAB | Entra o sale del modo edición (para entrar en Object Mode|
| Z | Activa o desactiva modo _wireframe_|
| G | Coge caras, aristas o vértices (dependiendo del modo en el que estés) |
| A | Toma o suelta todo el objeto, ideal para cuando estás moviendo vértices individuales y quieres deseleccionar los tomados |
| S | Reescala el elemento tomado |
| CTRL + R | Subdivide la superficie seleccionada, horizontal o verticalmente |
| CTRL + R (+ num) | Crea tantas subdivisiones como especifiques en el número |
| SHIFT + A| Añadir una nueva forma |
| X | Eliminar objeto/cara/vértice/arista |
| ALT + Right click | Seleccionar todos los vértices (en modo vértices) |
| SHIFT + D | Duplica objeto/cara/vértice/arista seleccionado|
| F12 | Renderizar|
| 0 (numpad)| Visión de cámara|

### Uniendo dos objetos con _merge_

Cuando ya hemos modelado dos objetos como por ejemplo base de la mano y dedo pulgar, es hora de unirlos. Para ello seleccionamos las dos caras que van a unirse para eliminarlas.

Podemos seleccionar entonces vértice contra vértice de cada objeto, si coinciden en número, para pulsar `ALT + M` y hacer `merge`. Debemos seleccionar la opción `All Center` para una unión óptima.

### Uniendo dos objetos con _bridges_

Cuando ya hemos modelado dos objetos, como un brazo y una mano completa, los vértices no coinciden en número. Una vez en una posición deacudada, con `ALT + Right click` seleccionaremos todos los vértices que van a estar unidos, en los dos objetos, tras haber eliminado las caras sobrantes. Pulsamos `Space` y buscaremos el término _bridge_, para encontrar `Bridge Edge Loops`.

Rota o reajusta la posición para una unión más coherente con el modelo.

## Exportando para Unity

Unity soporta de forma nativa muchos formatos para modelos creados en diverso software (Maya, Blender, SweetHome3D...), leyendo e incluyendo en sus proyectos esos ficheros. El problema reside en que, si por ejemplo añades un fichero _.blend_, abrir el proyecto en un equipo donde no está instalado Blender resulta en el fallo e inutilización del modelo.

Requerirá de instalación de  

## Ayuda en la red

| Acción  | Vídeos|
|------| :----|
| Aplicando colores y materiales | [Enlace](https://youtu.be/3R0842q6jfE)|
| Aplicando gravedad| [Enlace](https://youtu.be/rWbXfwTJQGA)|
| Creando edificios| [Enlace](https://youtu.be/APZ2kZ3OF1E)|
| Restando objetos| [Enlace](https://youtu.be/DO6pjh6nyJc)|
| Luces de colores | [Enlace](https://youtu.be/MIoDST2qR_c)|
| Aplicando texturas | [Enlace](https://youtu.be/MGIBLPIz4oM) |
| _Isometric level design_ | [Enlace](https://www.youtube.com/watch?v=DdSeJP8jd1Y)|
| _UV Mapping_ | [Enlace](https://youtu.be/obB9T3jXlak)|

### Orientados a Unity

| Acción  | Vídeos|
|------| :----|
| Exportando modelos a Unity | [Enlace](https://youtu.be/ch97U5H3mx4) |
| Cámara isométrica en Unity | [Enlace](https://youtu.be/euJmKya6ZZM)|

[UE4 _addon_](http://www.lluisgarcia.es/ue-tools-addon/), para exportar modelos a formato FBX e importarlos a Unity con colores incluidos (por probar, pensando en diseños isométricos).

#### Borrador

| Tecla o combinación de teclas | Descripción|
|------| :----|
|||
