# rest-album
Consumiendo un web services de JSON Holder
# Descripción del proyecto

#Consumir un web services co n jsholder utilizando, http en conjunto
  con los servicios del album y despliegue de la lista y detalle de 
  la lista. 

#Creación de las paginas
    ionic g page pages/albums
    ionic g page pages/album

#Creación del servicio
    ionic g service services/album


#Plugin para el funcionamiento del HTTP 
    ionic cordova plugin add cordova-plugin-advanced-http
    npm install @ionic-native/http

#Pagina donde se consume el servicio

https://jsonplaceholder.typicode.com/
