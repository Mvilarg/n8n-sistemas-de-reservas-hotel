# Casa Jacaranda, sistema de reservas de un hotel boutique

## Descripcion:


- El sistema comienza en cuanto recibe una nueva linea en el archivo de google sheet en la hoja de Respuesta de formularios 

- Los datos los procesa el motor de IA para verificar disponibilidad de la habitacion, numero de ocupantes y peticiones especiales

- Ingresa estos datos a la hoja de reservas y crea el formato del mensaje que sera enviado posteriormente al usuario con la informacion si la habitacion fue reservada


## Modelo de IA utilizado

>*Gemini-3.5-flash-lite* 

## Decisiones tomadas

* Para comenzar con el trigger se tomo la decision de utilizar una hoja de google shet en donde se almacenen los datos del formulario y el momento en que se ingrese una nueva linea comience el ciclo 

* El motor de IA es el encargado de realizar el mensaje y de agregar los datos del cliente a la hoja de reservas

## Enlaces

>Formulario: https://docs.google.com/forms/d/e/1FAIpQLSfVOWHeZCx9BvSpuHBcprs1Xctm0cc-5-5q7dFn65hXzFINhg/viewform?usp=sharing&ouid=104163190544676275286

>Hoja de calculo: https://docs.google.com/spreadsheets/d/13BcWaLBIQUcUCHyMYlmApPCMmkXr_yielXm9IybE4jk/edit?usp=sharing

