# Google Gruyere

1. Vamos a registrarnos en Google Gruyere.

   Lo primero que vemos es que se muestran en claro nuestro usuario y contraseña, lo cual representa una gran vulnerabilidad.

   ![Registro en Google Gruyere](image.png)

   Ahora vamos a subir un archivo a la página. Si fuese una página normal, no permitiría la ejecución del código de nuestro script y solo lo almacenaría, pero en este caso, sí permite ejecutarlo.

   Copiamos la dirección donde se ha almacenado nuestro archivo.

    ![alt text](image-2.png)

   Como podemos ver, se está ejecutando el código en la página.

    ![alt text](image-3.png)
    ![alt text](image-4.png)

   Ahora vamos a inyectar en el snippet un script que se ejecute al pasar el ratón por encima del texto y muestre una ventana emergente.

   ![alt text](image-5.png)

   Aquí podemos ver cómo aparece la pestaña emergente.

   ![alt text](image-6.png)

   Extraemos la cookie.

   ![alt text](image-7.png)
   ![alt text](image-8.png)

   Ahora lo que vamos a hacer es que, al pasar el ratón por encima del texto, se envíe mi cookie de usuario al backend (a mi servidor).

   ![alt text](image-9.png)

   Comprobamos cómo ha llegado la cookie.

   ![Comprobación de cookie](image-11.png)

   Ahora he iniciado sesión con otro usuario llamado Pepe.

   ![Inicio de sesión con Pepe](image-12.png)

   Desde la cuenta de Pepe, abro la terminal, voy a almacenamiento y modifico la cookie.

   ![Modificación de cookie](image-13.png)

   Ahora modificaré la cookie de Pepe y colocaré la cookie de "hola", que es la que he enviado al servidor.

   ![Reemplazo de cookie](image-14.png)

   Y al presionar Enter, ya me indica que soy "hola".
