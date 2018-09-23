# Taller1
TallerUno

Componentes:

PARA ECLIPSE

MAIN: Donde serán nombrados todas las clases siendo el main la clase principal que corre la aplicación.

Atributos del Main:

Logica log: inicializo la lógica

Metodos del Main: 

- Settings: Para tamaño de lienzo
- Setup: para llamar a la logica.
- draw: Para asignarle pintar la logica
- keyReleased: para soltar teclas

LOGICA: Se ejecutarán las diferentes clases

Atributos de Lógica:

ArrayList : lista de elementos recogibles.

Metodos de lógica:

pintar(): Pintar lo elementos
recoger(): recoge los elementos 

USUARIO: 

Atributos: 

posX: posición en X
posY: posición en Y
float: para la imagen
PImage[]: arreglo de la imagen
PApplet: para tener el core de processing

Metodos de usuario: 

pintar(): Pintar los elementos
mover(): para mover al jugador
animar(): para animar el gusano 


SERVIDOR

Atributos:

hilo: Thread 
mensajeRecibido 
String socket: intercambia los datos
ServerSocket: envia datos

Metodos:
run(): para correr el hilo

BALL

Metodos:

pintar(): pinta las bolas
mover(): aparecen randomicamente

-------------------------------------------

PARA ANDROID STUDIO

MainActivity

Atributos:


Metodos: 

onCreate (Bundle): Ejecuta la aplicacion
Botones () : void Con este metodo se detectan las acciones de los botones


Cliente

Cliente(PApplet, int, int) : void: Construcctor del cliente
run(): Recibe los datos enviados por parte del servidor
enviar() : Envia los datos obtenidos el servidor


Receptor
Receptor(Socket ) : void: Construcctor del receptor
run ( ): Recibe los datos enviados por parte del servidor
enviar () : void Envia los datos obtenidos por los botones al servidor


