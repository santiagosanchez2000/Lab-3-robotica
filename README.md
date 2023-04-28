# Lab-3-robotica
Desarrollo del laboratorio 3 de robótica, Introducción a ROS

## Sección A:
### Metodología y Resultados
Empleando como guía el artículo compartido (http://www.informit.com/blogs/blog.aspx?uk=The-10-Most-Important-Linux-Commands), comenzamos a explorar el uso del terminal en Linux, en este caso Ubuntu corriendo distintos comando en una variante del terminal instalada llamada Kitty:
1. `pwd`. Este comando sirve  para ver la ubicación donde nos encontramos ahora mismo en el sistema de archivos, tal como "/home/CamiloPC" o cualquier carpeta donde nos encontremos.
2. `ls`. Comando que nos permite ver el contenido en la ruta/carpeta actual o ruta que especifiquemos.
3. `cd`. Uno de los comandos más empleados. Permite moverse entre directorios/carpetas o a rutas que especifiquemos directamte. Se puede combinar con ".." para simplemente regresar al directorio anterior.
4. `touch`. Permite crear archivos, generalmente de texto, con el nombre que especifiquemos.
5. `rm`. Comando que elimina el archivo que deseemos de el directorio actual generalmente. Se puede combinar con más argumentos para eliminar directorios y otro tipo de archivos.
6. `mkdir`. Contrario al caso anterior, permite crear directorios/carpetas nuevas.
7. `rmdir`. Realiza la misma función de `rm` con argumentos adicionales para eliminar directorios directamente.
8. `mv`. Como se puede intuir, proviene del inglés "move" y permite mover archivos o directorios a la ubicación deseada.
9. `cp`. En lugar de mover archivos y/o directorios, los copia.
10. `man`. El comando más útil si se desea revisar información adicional de un comando, muestra el manual del comando que especifiquemos.
 
Aquí podemos ver el resultado de correr cada uno de estos comandos en orden:
![Screenshot from 2022-04-07 18-42-22](https://github.com/santiagosanchez2000/Lab-3-robotica/blob/main/imagen%20de%20comandos%201.png)

Y el manual de usuario resultante al llamar `man rm`:
![Screenshot from 2022-04-07 18-42-11](https://github.com/santiagosanchez2000/Lab-3-robotica/blob/main/imagen%20de%20comandos%202.png)

### Análisis
Como se puede observar, el terminal de comandos es una gran herramienta para moverse por el sistema de archivos del sistema, y así mismo generar los cambios y modificaciones necesarios de manera ágil. Adicionalemente hay que tener en cuenta el tema de permisos, para lo cual podemos usar el comando prefijo `sudo` y correr el comando que le sigue con permisos de administrador, permitiendo realizar acciones que no serían posibles de otra manera como la eliminación de archivos protegidos o la vista de ciertos archivos ocultos.
## Sección B:

## Sección C:

<p><strong>Explicaci&oacute;n c&oacute;digo usado.</strong></p>

<p><strong>Video de &nbsp;demostraci&oacute;n del laboratorio.</strong></p>
<p>En el siguiente video se realiza la demostraci&oacute;n de los movimientos que se lograron de la tortuga usando las teclas indicadas.</p>

https://github.com/santiagosanchez2000/Lab-3-robotica/blob/main/Video_imovimiento_tortuga.mkv

## Conclusiones:
- El terminal es una herramienta extremadamente útil para manejar el sistema de archivos, además de tener ciertas capacidades que no son posible de alcanzar mediante las alternativas con GUI.
- Matlab a su vez tiene una gran capacidad para automatizar procesos en ROS como la recolección de datos, realizar cálculos complejos, algoritmos de evasión de objetos y mucho más.
- Es posible obtener en Matlab toda la información que proporciona ROS en el terminal, de una manera más organizada al poder emplear todas las capcidades del software destinadas al manejo de datos.
- Se debe tener en cuenta el manejo de nodos, especialmente los maestro dentro de Matlab, pues no es posible correr más de una instancia del mismo, al igual que las relaciones de publicador/suscriptor entre ellos.
- Los servicios pueden resultar de gran utilidad para poder manipular parámetros que no serían accesibles de forma directa de otras maneras.
- Python es una excelente herramienta para manejar la interfaz humano máquina, además de todas las ventajas que nos ofrece este lenguaje como librerías, estructuras de datos, etc.
- Además permite ejectuar complejas rutinas de manera sencila en un solo comando del terminal con ROS configurado.
