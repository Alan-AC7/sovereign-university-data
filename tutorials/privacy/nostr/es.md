---
name: NOSTR

description: Descubre y comienza a usar NOSTR
---

# Cómo usar Nostr en 2023: Una guía para principiantes

Al final de esta guía, comprenderás qué es Nostr, habrás creado una cuenta y podrás utilizarla.

**Esta guía es gracias a FranklynHart en colaboracion con Agora256. Todos los creditos a el**

![Un nuevo retador ha llegado](assets/1.jpeg)

## ¿Qué es Nostr?

Nostr es un protocolo que tiene el poder de reemplazar a Twitter, Telegram y otras redes sociales. Es un protocolo abierto y simple que puede crear de una vez por todas una red social global resistente a la censura.

## ¿Cómo funciona?

Nostr se basa en tres componentes: pares de claves, clientes y relés.

Cada usuario tiene una o varias identidades, y cada identidad está determinada por un par de claves criptográficas.

Para acceder a la red, es necesario utilizar un software cliente y conectarse a los relés para recibir y emitir contenido.

![Sistema de claves](assets/2.jpeg)

## 1. Las claves criptográficas

A diferencia de Facebook o Twitter, donde el usuario debe proporcionar una dirección de correo electrónico y una gran cantidad de información a una empresa privada, Nostr funciona sin una autoridad central. El usuario genera un par de claves criptográficas, una clave secreta (también conocida como clave privada) y una clave pública.

La clave secreta, nsec, conocida solo por el usuario, se utiliza para autenticarse y publicar contenido.

La clave pública, npub, es un identificador único al que se adjunta todo el contenido publicado por un usuario. Tu clave pública es una especie de nombre de usuario que permite a otros usuarios encontrarte y suscribirse a tu feed de Nostr.

## 2. Los clientes

Los clientes son los software que permiten interactuar con Nostr. Los principales clientes son:

> iOS: damus
> Android: amethyst
> Web: iris.to; snort.social; astral.ninja

Los clientes permiten al usuario generar un nuevo par de claves (equivalente a crear una cuenta) o autenticarse con un par de claves existente.

## 3. Los relés

Los relés son servidores simples que puedes abandonar en cualquier momento si no te gusta el contenido que te envían. También puedes ejecutar tu propio relé si lo deseas.

> 💡 Consejo profesional: Los relés de pago suelen ser más eficientes para filtrar el spam y el contenido no deseado.

# Guía

Ahora que conoces lo suficiente sobre Nostr, puedes comenzar y crear tu primera identidad en este protocolo.

Para los fines de esta guía, utilizaremos iris.to (https://iris.to/) ya que este cliente web funciona en cualquier plataforma.

## Paso 1: Generación de claves

iris creará un juego de claves para ti sin que tengas que hacer nada más que ingresar un nombre (real o ficticio) para tu perfil. Luego haz clic en GO y ¡listo!

![Menú principal](assets/3.jpeg)

> ⚠️ ¡Atención! Deberás guardar un registro de tus claves si quieres poder acceder nuevamente a tu perfil una vez que cierres tu sesión. Te mostraré cómo hacerlo al final de esta guía.

## Paso 2: Publicar contenido

Para publicar contenido, simplemente escribe algunas palabras en el campo de publicación.

![Publicación](assets/4.jpeg)

¡Listo! Has publicado tu primer nota en Nostr.

![Publicación](assets/5.jpeg)

## Paso 3: Encontrar un amigo

Encuéntrame en Nostr y nunca más estarás solo. Me suscribiré a todos aquellos que se suscriban a mi feed. Para hacerlo, simplemente ingresa mi clave pública

npub1hartx53w6t3q5wv9xdqdwrk7h6r5866t8u775q0304zedpn5zgssasp7d3 en la barra de búsqueda.

![Mi perfil](assets/6.jpeg)

Haz clic en "seguir" y en unos días, también me suscribiré a tu feed. Seremos amigos. También me encantará leerte si quieres escribirme un mensaje.

Finalmente, asegúrate de suscribirte al feed de Agora256 para recibir una nota cada vez que publiquemos algo nuevo: npub1ag0rawstycy7nanuc6sz4v287rneen2yapcq3fd06972f8ncrhzqx

## Paso 4: Personaliza tu perfil

Aún tienes trabajo por hacer personalizando tu perfil. Para ello, haz clic en el avatar que Iris ha generado automáticamente para ti en la esquina superior derecha de la pantalla y luego haz clic en "editar perfil".

![Perfil](assets/7.jpeg)

Solo tienes que indicarle a Iris dónde encontrar tu imagen y tu banner de perfil en la web. Te recomiendo que alojes tu propio contenido: protege lo que es tuyo.

![Otra opción](assets/8.jpeg)

Si lo prefieres, también puedes descargar imágenes, Iris las almacenará por ti en nostr.build, un servicio gratuito de alojamiento de contenido visual para Nostr.

Como puedes ver, también puedes configurar tu cliente para poder recibir y enviar sats. Así podrás recompensar a los autores de contenido que te gusten o, mejor aún, acumular sats por el contenido increíble que publiques.

## Paso 5: Respaldo del par de claves

Este paso es crucial si quieres mantener el acceso a tu perfil una vez que te desconectes del cliente o que tu sesión haya expirado.
Primero, haz click en el icono de "Configuracion" representado por un engranaje.
![Setting](assets/9.jpeg)

Luego, copia y pega uno por uno tus npub, npub hex, nsec, y nsec hex en un archivo de texto que mantendras seguro. En caso de que sepas hacerlo, recomiendo encriptar este archivo.

![Clef](assets/10.jpeg)

> ⚠️ Ten en cuenta la advertencia que Iris te da. Si bien puedes compartir tu llave publica sin miedo alguno, la historia es completamente diferente para tu llave privada. Cualquiera que tenga esta ultima sera capaz de acceder a tu contenido

## Conclusion

Ahi tienes. pequeña avestruz, haz dado los primeros pasos en Nostr. Ahora, necesitaras aprender a correr a la velocidad de la luz. Pronto publicaremos guias que te enseñaran a como administrar tus llaves y como integrar lightning dentro de tu experiencia Nostr usando getalby.

**guia escrita por FranklynHart en colaboracion con Agora256**'
