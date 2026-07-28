# Laboratorio 8 — Switching, VLAN, Ethernet y WiFi

Trabajo de **Juan Esteban Ortiz Pastrana** y **Santiago Alberto Naranjo Abril**, presentado en la Escuela Colombiana de Ingeniería Julio Garavito el 9 de diciembre de 2023.

## Descripción

El laboratorio explora redes Ethernet y WiFi, el funcionamiento de switches de capa 2 y 3 y su configuración práctica mediante equipos físicos, Packet Tracer, Wireshark y una interfaz de línea de comandos.

## Temas abordados

- Diferencias entre switches de capa 2 y capa 3.
- Redes Ethernet, WiFi y LAN.
- VLAN y segmentación lógica.
- Spanning Tree Protocol en redes con varios switches.
- Configuración básica de switches.
- Captura y análisis de solicitudes ICMP con Wireshark.
- Configuración de una red inalámbrica y asignación mediante DHCP.
- Servidor web dinámico con DNS, Apache y PHP.

## Desarrollo

Se configuraron switches y se verificó la conectividad mediante `ping`. En topologías más grandes se observó el uso de STP para detectar bucles y el comportamiento de switches y hubs durante el envío de paquetes.

También se crearon VLAN y se comprobó la comunicación entre dispositivos de la misma red virtual. La práctica WiFi incluyó el nombre de la red, contraseña, direccionamiento, DHCP y pruebas de conectividad. Finalmente se documentó una calculadora de notas en PHP alojada mediante Apache.

## Conclusiones

Los switches de capa 2 trabajan con direcciones MAC y VLAN, mientras que los de capa 3 agregan capacidades de enrutamiento. Ambos cumplen una función importante en la comunicación eficiente de una infraestructura de red.

> Este README fue elaborado exclusivamente a partir del informe `Lab 8.docx`.
