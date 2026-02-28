# Tarea2-Hacking
correspondiente al modulo de Hacking Etico
ACTIVIDADES REALIZADAS:
1. PORT SCANNER: Escanea puerto objetivo del 1 al 200 en un ip objetivo para detectar cuales estan abiertos.
2. BANNER GRABER: Captura informacion del servicio que corre en cada puerto.
3. HERRAMIENTA COMBINADA: Identifica servicios vulnerables y versiones de software en sistemas objetivos.
PROCESO DE ESCANEO:
El script itera por cada puerto, intenta conectarse, usando sockets TCP, y si tiene exito solicita el banner del servicio.
Timeout 2 segundos evita bloqueos en puertos sin respuesta.
La practica se realiza con la direccion IP PUBLICA.
COMANDOS A UTILIZAR EN TERMINAL:
1. python port_scanner.py
2. python 'Banner Grabber.py'
3. python 'Port Scanner-Banner Grabber.py'


