# OpenMediaVault

### Activamos SMB
Lo utilizamos para que los equipos Windows puedan detectar las carpetas compartidas

![image](https://user-images.githubusercontent.com/14905801/160881939-8a8f7aed-f6f8-4fa2-bb44-9cad62741318.png)

Nos vamos al menu -> Servicios -> SMB -> Opciones y habilitamos el servicio


#### Cambio de contraseña de administrador

Nos vamos a opciones generales , contraseña de administrador e ingresamos la nueva contraseña:

![image](https://user-images.githubusercontent.com/14905801/155128757-bb521466-2b45-4850-912d-b99f0ef7371b.png)


#### Configuración de discos 

Una vez ingresado en nuestro navegador y accedido al servidor , seleccionamos discos en la parte izquierda para configurar los discos duros que podemos utilizar: 

![image](https://user-images.githubusercontent.com/14905801/155126870-9451e155-0b36-4b84-bc63-c551c7a07c3b.png)

Ahora nos vamos a Sistema de Archivos y pulsamos en añadir y seleccionamos el formato para inicializar los discos y el disco que queramos inicializar

![image](https://user-images.githubusercontent.com/14905801/155285951-1865d0e5-78e6-44ff-9273-7091a3f016e0.png)

Otra cosa que podemos apreciar aquí son las cuotas que se le pueden poner a usuario/s o grupo/s como podemos ver en la siguiente imagen , limitando la cantidad de datos que pueden meter en el disco.

![image](https://user-images.githubusercontent.com/14905801/155287392-071c62c6-f853-4133-b09d-1f7b8d19ad3c.png)


Y ahora nos vamos a Carpeta compartida y pulsamos en añadir y creamos nuestra carpeta o sistema de carpetas:

![image](https://user-images.githubusercontent.com/14905801/155286444-451a0006-443a-43df-808b-336c249fc8c3.png)

Tendremos una serie de permisos para cada usuario/grupo que depende de cada carpeta/s variarán según lo que deseemos hacer.

#### Configuración de perfil de usuario

Nos vamos a la opción " Usuario " . Seleccionamos la opción " Añadir " y rellenamos los datos.

En este apartado podemos agregar y eliminar perfiles de acceso al server NAS , podemos modificar los permisos de acceso de estos perfiles. Despues de ingresar un usuario , lo seleccionamos y pulsamos en " Modificar acceso ". Podremos otogar o revocar permisos a los usuarios para que puedan moficar el contenido almacenado , permisos de solo lectura o ningun permiso.


#### Configuración certificados SSL

Ya con acceso al servidor seguimos la siguiente ruta: "Sistema" -> "Opciones generales" -> "Conexión segura" 

Para utilizar la conexión segura necesitas un certificado , para crear este certificado hay que entrar en "Sistema" -> "Certificados" y haz click sobre SSL , luego pulsa "Añadir" y "Guardar" tras ingresar los datos. Hay que habilitar el certificado en los ajustes generales y aplicar cambios.

![image](https://user-images.githubusercontent.com/14905801/155127858-841c0ed5-a90f-4aaa-91a4-6f6d3944fe6d.png)

Nos dirigimos a la primera ruta comentada de este apartado y habilitamos el SSL , seleccionando el certificado creado en el paso anterior:

![image](https://user-images.githubusercontent.com/14905801/155128082-b2ac03ea-0ad6-4cc0-b07e-fbe6e4b5f27d.png)
