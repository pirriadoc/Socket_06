# Socket_06
6. Desarrolla un agente de usuario de correo con las siguientes características:
a) Debe proporcionar una interfaz gráfica al emisor, con campos para el servidor de correo
local, la dirección de correo electrónico del emisor, la dirección de correo electrónico del
receptor, el asunto del mensaje y el propio mensaje.
b) Debe establecer una conexión TCP entre el cliente de correo y el servidor de correo
local, enviar comandos SMTP al servidor de correo local, y recibir y procesar los
comandos SMTP procedentes del servidor de correo local.
La interfaz será similar a la mostrada en la captura de pantalla. El agente de usuario deberá
enviar un mensaje de correo electrónico como máximo a un destinatario cada vez. Además,
el agente de usuario supondrá que la parte del dominio de la dirección de correo electrónico
del destinatario es el nombre canónico del servidor SMTP del destinatario (el agente de
usuario no realizará una búsqueda DNS para obtener un registro MX, por lo que el emisor
debe suministrar el nombre real del servidor de correo)
