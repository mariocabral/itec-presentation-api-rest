# Códigos de error


![](assets/warbvz1or1u6t30t5sy3.jpeg)


![](assets/statuscode.png)


# Códigos 2XX: Peticiones correctas

- **200 OK**: Respuesta estándar para peticiones correctas.
- **201 Created**: La petición ha sido completada y ha resultado en la creación de un nuevo recurso.


# Códigos 3XX: Redirecciones

El cliente tiene que tomar una acción adicional para completar la petición.


# Códigos 4XX: Errores del cliente

- **400 Bad Request**: El servidor no procesará la solicitud, porque no puede, o no debe, debido a algo que es percibido como un error del cliente (ej: solicitud malformada, sintaxis errónea, etc). La solicitud contiene sintaxis errónea y no debería repetirse.
- **401 Unauthorized4​**: Similar al 403 Forbidden, pero específicamente para su uso cuando la autentificación es posible pero ha fallado o aún no ha sido provista. Vea autenticación HTTP básica y Digest access authentication.
- **403 Forbidden**: La solicitud fue legal, pero el servidor rehúsa responderla dado que el cliente no tiene los privilegios para realizarla. En contraste a una respuesta 401 No autorizado, autenticarse previamente no va a cambiar la respuesta.
- **404 Not Found**: Recurso no encontrado. Se utiliza cuando el servidor web no encuentra la página o recurso solicitado.
- **405 Method Not Allowed**: Una petición fue hecha a una URI utilizando un método de solicitud no soportado por dicha URI; por ejemplo, cuando se utiliza GET en un formulario que requiere que los datos sean presentados vía POST, o utilizando PUT en un recurso de solo lectura.
- **409 Conflict**: Indica que la solicitud no pudo ser procesada debido a un conflicto con el estado actual del recurso que esta identifica.
- **413 Request Entity Too Large**: La petición del navegador es demasiado grande y por ese motivo el servidor no la procesa.2​
- **414 Request-URI Too Long**: La URI de la petición del navegador es demasiado grande y por ese motivo el servidor no la procesa (esta condición se produce en muy raras ocasiones y casi siempre porque el navegador envía como GET una petición que debería ser POST).2​
- **415 Unsupported Media Type**: La petición del navegador tiene un formato que no entiende el servidor y por eso no se procesa.2​



# Códigos 5XX: Errores de servidor

- **500 Internal Server Error**: Es un código comúnmente emitido por aplicaciones empotradas en servidores web, mismas que generan contenido dinámicamente, por ejemplo aplicaciones montadas en IIS o Tomcat, cuando se encuentran con situaciones de error ajenas a la naturaleza del servidor web.
- **501 Not Implemented**: El servidor no soporta alguna funcionalidad necesaria para responder a la solicitud del navegador (como por ejemplo el método utilizado para la petición).2​
- **502 Bad Gateway**: El servidor está actuando de proxy o gateway y ha recibido una respuesta inválida del otro servidor, por lo que no puede responder adecuadamente a la petición del navegador.2​
- **503 Service Unavailable**: El servidor no puede responder a la petición del navegador porque está congestionado o está realizando tareas de mantenimiento.2​
- **504 Gateway Timeout**: El servidor está actuando de proxy o gateway y no ha recibido a tiempo una respuesta del otro servidor, por lo que no puede responder adecuadamente a la petición del navegador.2​

