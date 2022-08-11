# TeamWorkRedes-Jaimito
reto: navegación por pagina web "Cisco.com", desde un dispositivo utilizando una red y comunicación de datos.

Integrantes: 
- Vargas Wilches Nicolas - nicolasvawi@unisabana.edu.co - ID:0000246918.
- Perez Gonzalez Cesar Augusto - cesarpego@unisabana.edu.co - ID:0000249511.
- Juan Esteban Pinilla Pinilla - juanpinpin@unisabana.edu.co - ID:0000244051.

Solución:
Para darle solución al problema, lo que hicimos fue que principalmente Jaimito y sus familiares tuvieran un facil acceso a la red, para luego proceder con el 

Video:
- lo puedes encontrar en este mismo repositorio, o tambien lo puedes ver en el siguiente enlace:https://drive.google.com/file/d/1DSGAek4KjNtAD61y8eIlomC9ia0nUAhG/view?usp=sharing.

Elementos de red:
- (1) Servidor: Es donde esta alojada la pagina web "Cisco.com".
- (1) Nube: Es la que nos provee el internet:
- (1) Modem: Encargado de enviar la señal al resto de dispositivos.
- (2) Switch: Encargados de unir o conectar dispositivos en red.
- (3) PC, (2) Laptop, (1) Smartphone: Son desde donde Jaimito y sus familiares se conecta a la pagina de "Cisco.com".
- (1) AP: Este punto de acceso, permite la interconectividad de los dispositivos conectados a ella atravez señales electromagneticas.

Configuraciones:

Configuración del servidor:
- DHCP su IP Adress es (192.168.0.2) para que los demas dispositivos se puedan conectar automaticamente.
- DNS agregamos la URL de la pagina de "Cisco.com", para que se facilite la busqueda de la pagina, esto se hace ya que si ellos no ponen esta URL, tendrian que poner la dirección IP de la pagina, lo cual para Jaimito y sus familiares se les dificultaria encontrarla.
- HTTP activamos su funcionamiento para que el DNS funcione y que solo sea poner la URL para encontrar la pagina.
_________

Configuración de todos los dispositivos:
- DHCP por defecto esta en statico, pero lo cambiamos a este modo de DHCP para que se conecte automaticamente con el servidor.
- Los dispositivos conectados al AP, deben colocar el nombre(SSID) y contraseña de la red.
- Las laptop, requieren un cambio físico el cual es el cambio de tarjeta a una de wifi(WPC300N).
_________

Configuración del AP:
- SSID que es el nombre de la red.
- WPA-PSK, que tiene una contraseña.
_________

Tipos de redes utilizados:
- WLAN: Red de área local inalámbrica.
- LAN: Red de área local.
- Pan: Red de área personal.
_________

Topologías / Modelos utilizados:
- Árbol.
_________

Arquitecturas / Protocolos utilizados:
- Protocolo TCP / IP: capas como Aplicación, transporte, internet, interfaz de red.
_________

Servicios incorporados:
- Un servicio que hicimos fue el de gestionar las direcciones IP y otros parámetros de configuración como el DNS y el HTTP.
- Se Utilizarón dispositivos para pedir y aceptar información de forma TCP/IP al servidor en forma DHCP.
_________

Conclusiones:
- Podemos 

desafíos encontrados.

referencias.
