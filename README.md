=============================
 INSTALACIÓN Y CONFIGURACIÓN
=============================
¿Cómo ejecutar el programa?
Una vez descargado o clonado el proyecto se puede ejecutar el programa de dos
maneras diferentes.

1. Utilizando IDE
2. Utilizando la consola

-Utilizar un IDE:
1. Descomprimir el proyecto. (Hay que saber en qué ubicación lo estamos 
descomprimiendo para futuros pasos).
2. Abrir el IDE de tu elección (NetBeans, Eclipse, InteljiJ).
3. En caso de ser NetBeans, seleccionar la opción "Open Proyect..." del
menú "File". En caso de no encontrarse en NetBeans, seleccionar la opción
correspondiente a "Abrir proyecto".
4. Se abrirá una ventana en la que seleccionaremos nuestra carpeta. En este
punto, hay que buscar la ruta en que se descomprimió el proyecto, para poder
abrirlo. La carpeta debería aparecer con un ícono de una taza de café (ícono
de Java), esa es la que se seleccionará.
5. Ya con el proyecto abierto en NetBeans, se selecciona el botón con el ícono
de reproducción (Run) para correr el programa. Entonces se despliegará el 
resultado en la consola integrada de NetBeans.

-Utilizar la consola:
Para este procedimiento, es necesario contar con el archivo ejecutable .JAR, de
lo contrario no servirá.

1. Descomprimir el proyecto. (Hay que saber en qué ubicación lo estamos
descomprimiendo para futuros pasos).
2. Abrir la consola (Símbolo del sistema).
3. Dirigirnos a la ruta en que está el ejecutable (en la carpeta "dist" del
proyecto), por medio de comandos (cd <Tu ruta>/dist).
4. Escribir el siguiente comando: java -jar "Evidencia.jar". Esto nos permitirá
la correcta ejecución del programa, desde la consola.

==================
 USO DEL PROGRAMA
==================
Para usar el programa, hay que iniciar sesión con un usuario registrado en la base
de datos.

El usuario inicial o provisional, con el que se puede probar el funcionamiento es:
 *Usuario: testUser
 *Contraseña: passwordUser

Una vez iniciada sesión, para realizar las diferentes funciones hay que seguir las 
instrucciones del menú interactivo: 

1. Dar de alta paciente: registrar el paciente por medio de su ID, nombre y una
bereve descripción del problema que lo trajo. 
2. Mostar pacientes: lista todos los pacientes de la base de datos y sus atributos
3. Dar de alta doctor: registra el doctor mediante su ID, nombre y especialidad.
4. Mostrar doctores: lista todos los doctores en la base de datos y sus atributos.
5. Agendar cita: crea una lista con ID, fecha y hora.
6. Mostrar todas las citas: lista todas las citas con sus respectivos atributos.
7. Relacionar citas: toma los IDs de la cita, doctor y paciente como parámetros y
las relaciona en la base de datos.
8. Mostrar citas relacionadas: muestra todas las citas con su respectivo doctor, 
fecha y paciente.
9. (0)Salir: termina la ejecución del programa.


==========
 CRÉDITOS 
==========

Desarrollado por Jesús Guillermo Jiménez Delgado

==========
 LICENCIA 
========== 
Copyright 2020 Jesús Guillermo Jiménez Delgado

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
