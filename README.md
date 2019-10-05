# Cisco3905-SIP

Paso 1:

Configura una nueva extension para el telefono en tu pizarra preferida.

Paso 2:

Configurar el archivo SEP[MAC].cnf.xml con los datos requeridos obtenidos desde tu pizarra preferida.

Nota: Recuerda remplazar [MAC] por la MAC de tu telefono.

Paso 3:

Copia los archivos dialplan.xml y SEP[MAC].cnf.xml en un servidor TFTP.

Opcionalmente si deseas puedes actualizar el firware de tu telefono agregando los archivos que se encuentran en la carpeta Firmware 9.4.1 en la carpeta raiz de tu servidor TFTP junto con los otros dos archivos antes mencionados.

Paso 4:

Configura la red en tu telefono y habilita TFTP para cargar los archivos del paso 3.

Nota: Si actualizaste el firmware es necesario habilitar el modo DHCP de tu telefono para poder activar el servidor TFTP.

Paso 5: Tu telefono Cisco3905 se encuentra listo para ser utilizado en tu pizarra preferida.

