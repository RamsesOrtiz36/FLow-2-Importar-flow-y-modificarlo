# Ejercicicio2

## Instrucciones
+ Iniciar servicio de Node red desde terminal de comandos usando el comando:

      node-red

Se va quedar ejecutandose en terminal, no se vera el prompt 

+ En navegador colocar 

      localhost:1880    

![](https://github.com/RamsesOrtiz36/FLow-2-Importar-flow-y-modificarlo/blob/main/Imagenes%20Flow2/Acceso%20a%20Node-red.png)

+ Importar el codigo de flow1
  + Ir al boton "hamburguesa" (icono con tres lineas horizontales apiladas una sobre otra)
  + Escoger "Import" para hacer una copia.
  + Buscar el archivo en las carpetas y seleccionarlo.
 ![](https://github.com/RamsesOrtiz36/FLow-2-Importar-flow-y-modificarlo/blob/main/Imagenes%20Flow2/Node-red%20import.png)
 
 
+ Doble clic en el nombre de la pestaña Flow1 para cambiar el nombre
+ El boton Deploy se usa parra ejecutar el flow
+ Instalar nodo de dash board
  + En boton hamburguesa buscar **Manage palette** 
  + Pestalla **install**
  + Poner en search module: **node-red-dashboard**

![](https://github.com/RamsesOrtiz36/FLow-2-Importar-flow-y-modificarlo/blob/main/Imagenes%20Flow2/Node-red%20instalar%20nodos%20extra.png)

+ Del lado izquierdo de la ventana aparecen los nodos que se pueden usar.  

+ Colocamos un nodo de la seccion de nodos dashboard "text".
+ Ir a la parte derecha de la ventana visualización de valores, buscamos la pestaña de dashboard.
![](https://github.com/RamsesOrtiz36/FLow-2-Importar-flow-y-modificarlo/blob/main/Imagenes%20Flow2/node-red%20Dahsboard%20flow2.png)

+ Asignamos el nodo text a una "pantalla" en la que se va a ver y tambien a una seccion o "Tab" grupo de elementos que se vana  ver en la pantalla.
+ Deploy 
+ Construimos la pantalla en una nueva pestaña del navegador con el icono de un cuadrado con una flecha saliente.

![](https://github.com/RamsesOrtiz36/FLow-2-Importar-flow-y-modificarlo/blob/main/Imagenes%20Flow2/Node-red%20Dashboard%20layout.png)

## Notas extra
En caso de que no se puedan instalar los nodos dashboard:
1. Cerrar nodeRed con el comando 
	**Ctrl + C**
2. Actualizar el sistema
  	  
        sudo apt update
      
    	  sudo apt upgrade

3.Instalar los build Essentials
  	  
       sudo apt-get install -y build-essential


Repositorio del jueves 26 clonar
Modificación del archivo README jueves 26 May
Modificación del archivo desde Visual Studio Code para ver el cambio en Github Desktop
