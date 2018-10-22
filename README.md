# ENS-meetup-Ethereum-sevilla
Repositorio para el workshop del [meetup de Ethereum Sevilla](https://secure.meetup.com/es/register/?ctx=ref) sobre [ENS](https://ens.domains/), y como tokenizar nuestro dominio con [ENS Nifty](https://ensnifty.com/), asi podemos intercambiar el dominio o delegarlo en otra wallet.


Para registrar nuestro dominio en [ENS](https://ens.domains/) vamos a usar [MyCrypto](https://mycrypto.com/). Para ello nos vamos a su página o usamos su aplicación, yo he decidido usar la aplicación que podemos descargar desde su [github](https://github.com/MyCryptoHQ/MyCrypto/releases). A día de hoy es la versión 1.4.0, uso Linux, así que me descargo el [paquete](https://github.com/MyCryptoHQ/MyCrypto/releases/download/1.4.0/linux-x86-64_1.4.0_MyCrypto.AppImage) para Linux de 64Bits.
 Una vez descargado en el equipo procedemos a la instalación, es un programa con extensión “.Appimage” que no se instala, sino que se ejecuta, por ello necesitaremos darle permisos, en la terminal nos situamos en la carpeta que se ha descargado y escribimos:
 ```
 $ chmod a+x linux-x86-64_1.4.0_MyCrypto.AppImage
 ```
    ![ens1.png](/images/ens1.png)

Y lo ejecutamos con (posteriormente ya podemos abrirlo haciendo clic en el icono) :
```
$ ./linux-x86-64_1.4.0_MyCrypto.AppImage
```
    ##ens2.png

Una vez abierto ya podemos ver la aplicación de MyCrypto abierta vamos a proceder a crear una nueva wallet para usarla con ENS. Para ello hacemos clic en “Create New Wallet”y seleccionamos la opción del centro “Create New Wallet”, para este caso voy a usar la opción de “Keystore File” 
    ##ens3.png
    ##ens4.png

Introducimos una contraseña que sea segura y hacemos clic en “Create New Wallet”
    ##ens5.png

Descargamos el archivo en “Download Keystore File” y continuamos, en la siguiente pantalla nos saldrá información sobre nuestra wallet, como la clave privada, la imagen para el “Paper Wallet” por si queremos descargarla y tenerlo apuntado en un papel.
    ##ens6.png

Una vez creada la wallet y con los datos guardados vamos a proceder a usarla, para ello nos vamos a la página principal de la aplicación de MyCrypto (“View & Send”) y seleccionamos la opción “keystore File”.
    ##ens7.png

Vamos a comprobar que la dirección de ENS que queremos esté disponible, para ello en la aplicación de MyCrypto seleccionamos “ENS” e introducimos el dominio en el cual estamos interesados, y hacemos clic en “Check Availability”.
    ##ens8.png

Para este ejemplo comprobamos que “colmenacowork.eth” esté disponible, así que hacemos clic en “Open an auction on MyCrypto v3!” que nos llevará a la página de MyCrypto. Repetimos los pasos de introducir el nombre y comprobar que esté libre. Más abajo podemos ver las opciones para acceder a nuestra wallet. Como en pasos anteriores, seleccionamos la opción que deseemos y desbloqueamos nuestra cartera.
    ##ens9.png

Una vez que hemos seguido estos pasos nos saldrán varios datos que podemos modificar, yo los voy a dejar todos como están pero podemos modificarlos si lo deseamos y después hacemos clic en “Start the Auction”.
    ##ens10.png

Podemos ver que la siguiente imagen nos da información importante, como el día  que debemos revelar la oferta, el día que finaliza la subasta y más información. Hacemos clic en “Yes, I am sure! Make transaction”.
    ##ens11.png

Comprobamos en un explorador de bloques que nuestra transacción se ha realizado correctamente sin ningún error.
    #ens12.png


Después, debemos esperar el tiempo mínimo para revelar nuestra subasta. Una vez que ha pasado el tiempo necesario (3 días) podemos revelar nuestra oferta, para ello abrimos la pagina de MyCrypto, hacemos clic en “TOOLS” > “ENS Domains”, introducimos nuestro dominio y nos redirige a la página legacy de MyCrypto y desbloqueamos nuestra wallet. 
Una vez desbloqueada debemos introducir en el espacio “Long string of text you copied” el texto copiado y hacemos clic en “Reveal your Bid” 
    ##ens13.png

Cuando hayan pasado los días necesarios para la finalización de nuestro dominio podemos entrar en [MyCrypto](https://mycrypto.com/ens) introducir nuestro dominio y veremos que ya es nuestro.
    ##ens14.png
