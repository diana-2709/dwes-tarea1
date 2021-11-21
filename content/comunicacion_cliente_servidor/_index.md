+++
chapter = true
pre = "<b>5. </b>"
title = "Comunicación cliente/servidor"
weight = 5
+++

# Comunicación cliente/servidor

Durante el proceso de carga de una página web ocurren diversas cosas.

Para entenderlas tenemos que tener claro que los dos elementos que hacen esto posible son un cliente (es el que solicita la información, un navegador) y un servidor (es el que devuelve la información).

En primer lugar, el cliente ha de conectarse al servidor DNS para así poder realizar las peticiones al lugar correcto. 

Una establecida la conexión, cliente y servidor pueden intercambiar información siguiendo el protocolo HTTP/HTTPS. Este protocolo constituye una serie de reglas que permite la transferencia de información en internet, siendo la diferencia entre usar HTTP o HTTPS la seguridad que aportan, ya que HTTPS al estar cifrado hace que la información que maneja un sitio web se encuentre protegida.

Siempre que las peticiones lanzadas sean aprobadas por el servidor, este devolverá el contenido correspondiente (dicho contenido estará compuesto generalmente por archivos html, css, y javascript, y diversos recursos como imágenes, PDFs, etc), y el cliente se encargará de interpretarlo y cargarlo.

Cuando estás peticiones no sean aprobadas, el servidor devolverá un error u otro en base a qué es lo que ha fallado. 
