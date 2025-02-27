# Asignación 01
Para realizar esta actividad se comenzó por  introducir los siguientes tres comandos para generar la estructura solicitada por el profesor desde el directorio ROS2Dev:
```shell
mkdir -p diego_ws/src/docs/asignaciones/
cd diego_ws/src/docs/asignaciones/
touch asignacion_01.md
```
***Estructura obtenida***
```text
 diego_ws/
    ├── src/
       ├── docs/
           ├── asignaciones/
               └── asignacion_01.md
    
```
Se porocedió a modificar el archivo  ~/.bash_aliases con el editor de texto vim para añadir la siguiente linea al final del documento:
```vim
alias srcmyws='source ~/ROS2Dev/diego_ws/install/setup.bash
```
Al guardar el alias y salir del documento reiniciamos la terminal y nos colocamos en el directorio diego_ws donde ejecutamos los siguientes dos comandos:
```shell
colcon build
srcmyws
```
Con lo anterior se generó el espacio de trabajo y se comprobó que el nuevo alias funciona correctamente.

Posteriormente se creó un repositorio vacío en GitHub y se siguieron las instrucciones para asignar el origen remoto en la ruta "~/ROS2Dev/diego_ws/src".

Por último se modificó este documento y posteriormente se utilizaron los siguientes tres comandos para subir nuestros documentos al repositorio: 
```shell
git add .
git commit -m "Added files from homework "Asignacion 01" "
git push
```
