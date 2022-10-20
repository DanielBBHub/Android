# Android  
En este repositorio se encuentra un archivo comprimido rar conteniendo el codigo que   
compone la aplicación movil desarrollada para el Sprint 0 para el proyecto de Biometria.    

Entre estos archivos encontramos los siguientes, que brindan de funcionalidad la app:  
  -Logica: en este archivo se encuentran las funciones que realizaran las tareas de  
  peticiones al servidor REST que hay montado. Se recibira un body con la información  
  que se desee enviar y se configurará una petición HTTP para consultar y modificar  
  la base de datos  
  
  -MainActivity: en este archivo se encuentra la funcionalidad de la tecnología  
  bluetooth, con la que captaremos los paquetes de información enviados por el  
  microcontrolador  
  
  -PeticionarioREST: en este archivo se encuentra la conexión y envio de las peticiones  
  creadas en la Logica. Este se encarga de lidiar con las respuestas del servidor, asi como  
  de errores que puedan surguir en la ejecución de este codigo.  
  
  -TramaIBeacon: en este archivo se encuentra el codigo con el que obtener la información de  
  los paquetes recibido. Se basa en unas funciones get() con las que devolver todas las variables  
  que nos sean de ayuda, ademas de un constructor en el que se discierne cada valor y se asocia  
  a una variable representativa.  
  
  -Utilidades: en este archivo se encuentran funciones con las que transformar los tipos de los valores  
  de entrada. Se pueden manejar enteros, cadenas de caracteres y cadenas de caracteres en hexadecimal,  
  bytes y UUID con este programa  
  
