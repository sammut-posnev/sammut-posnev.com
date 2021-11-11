title: 1. Introducción
++++

# Introducción

Urbit es un proyecto dificil de concretar porque, en lugar de ser un único producto, **es un sistema completo**. Cuando nos centramos elemento por elemento observaremos que hay diferentes compañías que ya se están encargando de construir dichos elementos, lo que nos diferencia es que en Urbit todos esos elementos conforman un mismo sistema fluido y sin interrupciones entre cada parte.

Por esta razón, la introducción a Urbit será una entrada muy extensa e intentaré explicarlo de la forma más accesible para todos porque si Urbit es sólo accesible para programadores, es que este proyecto ha nacido muerto. Para que Urbit sea útil, **Urbit debe ser entendido por usuarios fuera del ecosistema informático**. Como yo, y tal vez como tú.

## ¿Qué es Urbit?

Vamos directos al grano y empezamos con la definición más básica de Urbit:
> **Urbit** es una red peer-to-peer (p2p) de servidores personales con el objetivo de reducir la dependencia a grandes corporaciones y así cualquier persona pueda ejecutar y controlar su propio software.

En su nivel más básico, Urbit es un ordenador orientado a la privacidad con una identificación que se encuentra conectada p2p con otros ordenadores de Urbit.

Es decir, cada usuario de Urbit tiene una **identidad permanente** que le permite tener acceso a su propio ordenador personal que se encuentra en la nube y así poder interactuar con otros ordenadores Urbit (por ejemplo, personas) en una misma red, todo ello sin ningún intermediario.

![](posts/images/conectado.gif#small)

1. Cuando me refiero a "ordenador (computer)", no me refiero al sentido estricto de un dispositivo físico sino más bien un **software que computa**. Los desarrolladores se suelen referir a Urbit como un **SO alojado** debido a que éste se ejecuta/computa en una máquina virtual pero no con un significado de contenerizado o como VMWare o VirtualBox sino como un elemento que debido a **Nock** (la máquina virtual de Urbit) éste podría ser ejecutado con el mínimo de elementos.

    Me gustaría recalcar el "mínimo de elementos". **Urbit** como "SO alojado" no intenta reemplazar los sistemas operativos convencionales porque Urbit todavía requiere de un gestor de memoria, controladores de dispositivos, servicios de entrada/salida como tarjetas de red o dispositivos de almacenamiento.

2. Cuando me refiero a "ningún intermediario", me refiero a todos esos servidores centralizados que usamos cada día. Servidores en propiedad de Google, Facebook, Youtube, Instagram, Twitter, Slack, Amazon, Apple, etcétera. Todas estas compañías y sus productos **dependen de nuestros datos**.

    Datos de los cuales no tenemos la libertad o capacidad de mover libremente entre servicios. Si un proyecto muere, arrastrará con él todas tus imágenes, contactos, marcadores, etiquetas, etcétera.

    **Las grandes corporaciones no dudan en generar una dependencia del proveedor para mantener los usuarios, y sus datos, dentro de sus propios términos**. Compañías como Google que proclaman a los cuatro vientos dar soporte a una libre circulación de los datos, son tan cínicos como para reemplazar protocolos abiertos (Google Talk) por protocolos de su propiedad (Google Hangouts).

## ¿Cómo se siente usar Urbit?

Otra forma de explicar Urbit es describiendo su aspecto y cómo se siente usarlo. Visualmente, Urbit pertenece a un género denominado "**calm computing**". Urbit está diseñado para ser simple, básico, y libre de adicción. Aquí no encontrarás lucecitas ni colores extravagantes para llamar tu atención. Simplemente **"calma"**, funcionalidad, y herramientas con un propósito por y para las personas.

![](posts/images/visual.png)

*¿Deseas explorar y ver cómo es Urbit? > [4. Tú cápsula planetaria](4_capsula.md)*

## Elementos clave de Urbit

Como he dicho al principio, Urbit está compuesto por diversas capas que están construidas bajo un mismo sistema. Ésto puede causar cierta complejidad a la hora de entenderlo y es por ello que voy a detallar algunos de sus elementos.

### 1. Una red p2p

Hoy en día tienes dos opciones en cuanto al uso de Internet: **crear tu propio servidor o unirte a alguna aplicación o servicio**. A nosotros no nos sirven estas dos opciones. No queremos ser administradores del sistema y no queremos estar bajo las decisiones de una gran corporación.

En Urbit, **todas las comunicaciones son entre usuarios, sin nadie que actue entre intermediario**. Esto significa que no hay ningún dato que pueda ser capturado por dichas corporaciones, menos intrusión en tu vida online, y las comunicaciones vuelven a ser semi-privadas, boca a boca, o en petit comité. Más humano, más real.

### 2. Tu propio servidor

Los servidores son complicados. Excesivamente complicados. ¿Has usado alguna vez una terminal? Exacto. Es una forma horrible de trabajar, y eso es sólo una parte de la complejidad de un servidor. Para escabullirnos de esta complejidad, dejamos que las corporaciones hagan de servidor — ellos se pueden permitir un equipo de ingenieros. El problema es que actualmente la mayoría de nuestro día a día es mantenido por los servidores de dichas corporaciones — y esto significa que renunciamos al control por la complejidad.

> Como ejemplo, cada vez que usas Siri, tú mensaje es enviado a los servidores de Apple, donde es procesado y la respuesta es enviada devuelta a ti. Desafortunadamente, Siri nunca funciona si te encuentras sin conexión. Y ésto se aplica a todas las aplicaciones que usamos: nuestro día a día ocurre en los servidores de grandes corporaciones. 

**El problema no es sólo que no tengamos el control, sino que las empresas ven, registran y clasifican toda nuestra actividad**.

Fundamentalmente, Urbit es un servidor muy simple. Esto significa que Urbit puede ejecutar todo nuestro día a día sin la necesidad de una empresa intermediaria.

*¿Deseas explorar y saber más sobre las entrañas de Urbit? > [2. Urbit OS](2_urbitos.md)*

### 3. Control total de tu identidad digital y de sus datos

La identidad asociado a Urbit (**Urbit ID**) son **propiedad permanente de su usuario** — y esta propiedad está respaldada criptográficamente, no por una base de datos de una corporación.

**Una vez has tomado posesión de tú Urbit ID, no hay entidad que pueda quitartela**. Lógicamente, si empiezas a hacer spam en los grupos, otros usuarios podrían empezar a bloquearte pero ninguno de ellos puede evitar que hagas uso de tu Urbit ID o de acceder a tu ordenador Urbit.

Compara este hecho con el actual Internet donde Google es propietaria de tu cuenta de Gmail, donde Facebook es propietaria de tu perfil de Facebook, donde Twitter es propietaria de tu cuenta de Twitter. Y en cualquier momento y por cualquier razón, estos servicios puede negarte tu acceso. **Todos tus datos, todos tus seguidores, toda tu reputación ha desaparecido en un instante**. En Urbit, esto no ocurre pues tu identidad y datos te pertenecen.

### 4. Se incentiva la buena conducta

En la red de Urbit, **las identidades son finitas y a ellas se les adhiere una reputación**. Compara esto a la actual Internet donde las identidades son infinitas (cualquiera puede crear tantos correos electrónicos y perfiles en redes sociales como quiera, esencialmente son gratuitas) y como tal pueden producir spam, scams y ataques DoS cuando muchas identidades desechables atacan un mismo servidor de forma coordinada. 

En Urbit existen más de 4 mil millones de identidades (2^32 para ser exactos). **Un bien escaso genera valor. Esta escasez combinada con una reputación, implica un incentivo para una buena conducta**.

Puedes llegar a pensar que 4 mil millones de identidades son pocas para la cantidad de humanos que hay en la Tierra. No entraré aquí en detalles técnicos, pero si alguna vez llegamos a un punto que éste es un problema (lo cuál es un buen objetivo como problema), tenemos varias soluciones planteadas para que todo ser humano pueda acceder a la red Urbit. No tenemos intención de dejar nadie excluido.

![](posts/images/sammut-posnev_card.png#smaller#rounded)
![](posts/images/marzod_card.png#smaller#rounded)

*¿Deseas explorar y saber más sobre las identidades en Urbit? > [3. Urbit ID](3_urbitid.md)*

### 5. Privado, humano, y eficiente

Debido a que Urbit no está centralizado, no existe ningún incentivo para intentar controlar tu vida. **Urbit no está diseñado para espiarte, ni para generar una adicción presionando botones, ni para manipular tus emociones para mantener tu atención, ni para presionarte a comprar algo**.

Urbit es simple y personalizable, un lugar permanente para todas tus tareas relacionadas con la informática o con tus amistades en un entorno totalmente privado.

#### ¿Por qué Urbit es importante?

La humanidad no ha evolucionado lo suficiente como para ser capaz de administrar la cantidad de información que nuestra era tecnológica nos lanza día tras día. **Hay demasiadas noticias, demasiadas conexiones, demasiadas opiniones**. Un exceso de información que ninguno de nosotros puede llegar completamente a comprender.

Aquí es donde aparece Urbit. Urbit es un entorno que nos permite hacer todo lo que queremos con el ordenador, pero en comunidades de nuestra propia elección, de una forma que se sienta natural y conforme a nuestra propia libertad personal.
Urbit desde sus cimientos es seguro, privado y tranquilo. No hay corporaciones que te espien ni políticos que te manipulen.

Y esto es lo que necesitamos. **La humanidad necesita tomar ventaja de los avances tecnológicos sin ser dominados por ellos**. Urbit es una herramienta de **código abierto** que todos podemos poseer y que se encuentra bajo dominio absoluto de sus usuarios.

----

A continuación profundizaremos en el sistema y los elementos que conforman Urbit.

*Siguiente lección > [2. Urbit OS](2_urbitos.md)*

**Reconocimientos**

> - https://subject.network/posts/urbit-introduction/
> - https://davis68.github.io/martian-computing/
> - A la comunidad de "Art by Urbit".
> - https://urbit.org/blog/urbit-for-normies/