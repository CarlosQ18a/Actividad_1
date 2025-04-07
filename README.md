# Practica servidor web
## 1. Titulo
Creación de un Proyecto Angular en Linux utilizando la terminal y Angular CLI
## 2. Tiempo de duración
1:30h aproximados para completar la práctica.
## 3. Fundamentos:

Angular es un marco web desarrollado por Google que le permite crear aplicaciones de páginas de clientes utilizando una arquitectura basada en Bot con la ayuda del lenguaje TypeScript. 
La instalación y el uso de Angular requiere Node.js y un entorno NPM (administrador de paquetes de nodo), que facilita la dependencia y la gestión de herramientas como una cli angular. 
En combinación con Linux, el sistema operativo más utilizado en entornos de desarrollo, puede automatizar tareas y organizar proyectos extremadamente eficientes. CD, Mkdir, entre otras cosas.
Durante esta práctica, examinará el proceso, instalará Node.js y la CLI angular, creando un proyecto de ángulo base, iniciando un servidor local y visualizando los resultados del navegador. 
De esta manera, la última aplicación se crea y se muestra desde cero.

## 4. Conocimientos previos.
   
Para llevar a cabo esta actividad, el aprendiz debe tener en mente los siguientes conceptos:
- Instrucciones elementales de Linux
- Uso de un buscador de internet
- Fundamentos básicos en HTML, CSS y JavaScript

## 5. Objetivos a alcanzar
- Instalar Angular CLI en un sistema Linux
- Iniciar un proyecto Angular desde la consola
- Correr la aplicación en un servidor local para desarrollo
- Conocer la organización del proyecto creado por Angular CLI
## 6. Equipo necesario:
  
- Computadora que tiene el sistema operativo Linux (Ubuntu, etc. )
- Terminal de Linux (Warp, GNOME Terminal, etc. )
- Acceso a internet
- Node. js 
- npm 
- Angular CLI 
- Navegador en la web 
- Visual Studio Code
## 7. Material de apoyo.
   
- Documentación oficial de Angular: https://angular.dev/installation
- Documentación de Node.js: https://nodejs.org/docs/latest/api/

## 8. Procedimiento

1.- Actualizar los paquetes del sistema

```
sudo apt update && sudo apt upgrade -y
```
2.- Instalar Node.js y npm
```
sudo apt install nodejs npm -y
```
3.-Verificar la instalación
```
node -v  
npm -v
```
4.- Instalar Angular CLI
```
npm install -g @angular/cli
```
5.-Crear el proyecto Angular
```
ng new mi-proyecto-angular
```
6.-Ingresar al directorio del proyecto
```
cd mi-proyecto-angular
```
7.-Ejecutar el servidor de desarrollo
```
ng serve
```

## 9. Resultados esperados:
    
El estudiante habrá creado y ejecutado exitosamente un proyecto Angular básico. 
El servidor local mostrará una aplicación Angular funcional, lo que confirma que las herramientas fueron correctamente instaladas y configuradas.
Se espera también que el estudiante explore archivos como angular.json, package.json y las carpetas src/ y app/.

## 10. Bibliografía
    
Angular. (n.d.). Angular Documentation. 
 https://angular.dev/installation
Node.js. (n.d.). Node.js Documentation.
https://nodejs.org/docs/latest/api/
Ubuntu. (n.d.). Command Line for Beginners. 
https://ubuntu.com/tutorials/command-line-for-beginners
Linuxize. (2021). How to Install Node.js on Ubuntu.
https://linuxize.com/post/how-to-install-node-js-on-ubuntu-20-04/
