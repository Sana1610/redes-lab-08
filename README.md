# Laboratorio 8 — Switching, VLAN, Ethernet y WiFi

**Autores:** Juan Esteban Ortiz Pastrana y Santiago Alberto Naranjo Abril  
**Institución:** Escuela Colombiana de Ingeniería Julio Garavito  
**Grupo:** 2  
**Fecha:** 9 de diciembre de 2023

## Introducción

El laboratorio estudia redes Ethernet y WiFi, switches de capa 2 y 3 y su configuración mediante equipos físicos, Packet Tracer, Wireshark y una interfaz de línea de comandos.

## Fundamentos

- Un **switch de capa 2** comunica dispositivos de una LAN mediante direcciones MAC y permite asignar VLAN a sus puertos.
- Un **switch de capa 3** agrega enrutamiento mediante direcciones IP y control de subredes.
- **Ethernet** define la transmisión de datos en redes cableadas.
- **WiFi** conecta dispositivos mediante radiofrecuencia.
- Una **VLAN** segmenta lógicamente una red física para aplicar políticas y reducir tráfico.

## Montajes

### Configuración básica

Se conectan dos equipos a un switch y se comprueba la comunicación mediante `ping`. Wireshark permite revisar las direcciones IP y MAC, la solicitud ICMP, el control de errores y el checksum.

### Redes de switches

En una topología más grande se observa el uso de STP para detectar bucles y bloquear lógicamente un enlace. En modo simulación se analiza el recorrido de los paquetes y el comportamiento de un hub, que replica el tráfico como un pequeño broadcast.

### VLAN

Se crean redes virtuales, se asignan puertos y se verifica la comunicación mediante `ping`. Wireshark permite identificar la VLAN asociada al tráfico.

### WiFi

Se configura el router desde `192.168.0.1`, definiendo nombre de red, contraseña, dirección, máscara y rango DHCP. Las pruebas incluyen intensidad de señal, canal, conectividad a Internet y acceso después de ocultar la red.

### Servidor web dinámico

Se reutiliza la configuración DNS del laboratorio 3, se instala Apache en Solaris y se aloja una calculadora de notas desarrollada en PHP.

## Conclusiones

El informe concluye que los switches son esenciales para mantener un flujo de datos seguro y eficiente. La capa 2 trabaja con direcciones MAC y comunicación dentro de una LAN; la capa 3 incorpora direccionamiento lógico, control de subredes y enrutamiento estático o dinámico.

## Contenido del repositorio

- Informe completo en DOCX y PDF.
- Topologías de LAN, WiFi y redes de switches desarrolladas por Santiago Naranjo.
