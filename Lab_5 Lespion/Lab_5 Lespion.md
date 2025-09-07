## Caso Lespion

>Un cliente cuya red ha sido comprometida y desconectada le ha encargado investigar el incidente y determinar la identidad del atacante.
>Los responsables de la respuesta ante incidentes y los investigadores forenses digitales se encuentran actualmente en el lugar y han llevado a cabo una investigación preliminar. Sus conclusiones indican que el ataque se originó en una sola cuenta de usuario, probablemente de alguien interno. Investigue el incidente, encuentre el responsable interno y descubrta las acciones del ataque.


### Q1/ Archivo -> Github.txt: ¿Qué clave API añadió el informante a sus repositorios de GitHub?

>Para encontrar la clave API del informate primero debemos acceder a su github, que nos proporcionan su link en los archivos de la investigación, una vez ahí abrimos el repositorio Project-Built---Custom-Login-page, y dentro de este está el archivo Login Page.js donde encontraremos de primero la API Key.

![Captura1](Captura1.png)

### Q2/ Archivo -> Github.txt: ¿Qué contraseña en texto plano añadió el empleado a sus repositorios de GitHub?

>Para encontrar la contraseña debemos estar ubicados en el archivo Page.js ubicado Project-Built---Custom-Login-page.

![Captura2](Captura2.png)

>Pero como vemos hay un problema la contraseña no está en texto plano sino que está codificada en Base64 por lo que vamos a usar la herramienta CyberChef para que nos ayude en decodificar y conseguir el texto plano de la contraseña.

![Captura3](Captura3.png)

### Q3/