title: 3. Urbit ID
++++

# Urbit ID

En el apartado anterior nos hemos encontrado con que **Azimuth** es uno de los nucleos que conforman el subsistema de Urbit, el cual se encarga de las identidades o direcciones criptográficas. Dichas identidades son esencialmente una clave pública cuya infraestructura se encuentra bajo el dominio de un contrato en la cadena de bloques.
Su estructura es similar a como IPv4 está diseñado pero con terminos específicos como **galaxias, estrellas, planetas, lunas**, que sirven para identificar y diferenciar la granularidad de dicha identidad, parecido a como las direcciones IPv4 se subdividen en clase A, B, C, y D. 

> Tú identificación en Urbit es mediante un nombre de cuatro silabas como por ejemplo **~sammut-posnev** el cual te pertenece mediante el uso de una clave tipo **~palfun-foslup-fallyn-balfus**. Este nombre y su clave te permite acceder a tu Urbit OS y hacer uso de la red P2P de Urbit.

Aunque el contrato de Azimuth sea usado para almacenar toda la información relacionada con las identidades en Urbit, todas las operaciones que impliquen a Azimuth deben ser canalizadas mediante el contrato Ecliptic, el cual a su vez pertenece a Azimuth. Es decir, mientras que el contrato de **Azimuth se encarga del almacenaje**, el contrato de **Ecliptic se encarga de la lógica** en las operaciones que impliquen interactuar con Azimuth, como por ejemplo a la hora de verificar la identidad de una persona que intenta acceder a sus datos.

Estos contratos están registrados en la cadena de bloques de Ethereum y, a día de hoy, Urbit ID es algo tangible, totalmente desplegado y representado como un **ERC-721 non-fungible token (NFT)**.

![](posts/images/urbit-sigils.png#center#small)

## ¿Galaxias, estrellas, planetas, lunas?

Nuestro Urbit ID es en realidad un número y de ese número generamos un nombre mnemotécnico y pronunciable, junto con un estandarte o imagen identificativa. Por ejemplo, **~sammut-posnev** es **87.819.520** (un número de 32-bit, como si de una IP se tratase).

Técnicamente, un **planeta** es una identidad digital totalmente segura a la que tú tienes acceso con una clave criptográfica, como si de un monedero de Bitcoin se tratase. Al igual que el Bitcoin, la cantidad de planetas se encuentra matemáticamente limitada.

Como ya hemos dicho, un planeta es simplemente un número y la cantidad de números bits que tenga su nombre nos permitirá clasificarlo en:

- **8-bit galaxias**: representan los "organos de gobierno" de Urbit. Establecen las direcciones de las estrellas.
> 2^8-bits hacen 256 galaxias como por ejemplo ~syd.
- **16-bit estrellas**: suministran la red p2p de Urbit, ya sea mediante OTAs o de conectividad entre IDs. Establecen las direcciones de los planetas.
> 2^16-bits hacen 65,280 estrellas como por ejemplo ~delsym.
- **32-bits planetas**: son básicamente identidades personales.
> 2^32-bits hacen 4,294,901,760 planetas como por ejemplo ~mighex-forfem.
- **64-bits lunas**: su proposito inicial es la de representar dispositivos o cuentas asociadas a un planeta, como por ejemplo menores o chat-bots. Cada planeta dispone de 2^32 lunas.
> Por ejemplo ~dabnev-nisseb-nomlec-sormug
- **128-bits cometas**: son identidades sin ningun tipo de reputación, elementos principales de los spammers y bots. Cualquier persona puede generarlas.
> Por ejemplo ~satnet-rinsyr-silsec-navhut--bacnec-todmeb-harwen-fabtev

En total hay **4,294,967,296** de direcciones disponibles y de cada una de ellas se pueden generar 2^32 lunas.

![](posts/images/urbit-bits.png#center)

## El valor de tú identidad en Urbit

Como las identidades de Urbit son finitas, en un principio tienen una valoración similar a las criptomonedas como por ejemplo Bitcoin. Así pues, **debes tener a buen resguardo tus claves para acceder a tu Urbit UD** porque una vez han sido perdidas, son irrecuperables.

> Actualmente puedes comprar tu Urbit ID en [Opensea.io](https://opensea.io/assets/urbit-id?query=urbit), en [Urbit.live](https://urbit.live/buy) o de cualquier persona que tenga una identidad y que desee transferirla.

Existen un total de 2^32 identidades, el simple hecho de su **escasez** hace que tengan valor. Al tener una barrera monetaria de entrada hace que la gente esté menos dispuesta a usar su identidad como spam o para abusar de la red Urbit, haciendo de **Urbit una comunidad amigable**. Una comunidad en la que puedes llegar a asumir que todo extraño es una persona con la que te puedes llevar bien hasta que se demuestre lo contrario. Puedes ver que Urbit no está reinventando las relaciones y naturaleza humana, simplemente está creando un incentivo económico para ellas.

La propia escasez hace que la reputación de un individuo funcione, de tal forma que hacer spam o ser un troll se convierta en un negocio. **Si la cantidad de dinero para obtener un nuevo planeta excede la cantidad de dinero que puedes generar a través del spam hasta que tu reputación se vea afectada, no existirá el spam**. Las propias galaxias y estrellas que se dediquen a vender planetas a spammers también desarrollaran una reputación de "malos vecinos". El abuso a cualquier nivel está diseñado para que sea contraproducente y económicamente asfixiante.

Pese a todo, Urbit todavía no dispone de un sistema propio de reputación, simplemente porque su comunidad aún es lo suficientemente pequeña y que ser amigable es un acto instintivo.

> Las estrellas y planetas pueden abandonar su padrino si así desean. Además, los padrinos pueden decidir dejar de dar servicio a cualquier estrella o planeta. Esto está diseñado para incentivar la buena conducta por ambas partes. Un pacto mutuo entre ambos es importante en una red donde sus identidades son limitadas.

![](posts/images/conectado_nikolas.png#center#small)

**Urbit es una red de redes** y está diseñada específicamente para las comunidades — para su comunicación y colaboración. Cuantas más personas usen Urbit, debido al propio diseño, más comunidades se crearan. Cuantas más comunidades existan, más gente querrá entrar, y así el ciclo se repite sucesivamente.

Una vez estamos dentro de Urbit, nos damos cuenta que es una red bastante inusual por las siguientes razones:

1. Urbit es en si misma una plataforma.
2. Las conexiones son P2P.
3. La privacidad es muy alta.
4. El descubrimiento de nuevas comunidades es relativamente bajo.
5. La autonomía que tiene uno mismo para hacer lo que quiera es increible.
6. La cantidad de grupos y de conexiones entre nodos es prácticamente infinita.

En definitiva, **Urbit puede servirnos como una meta-red de diferentes tipos de redes personales e individuales, cada una de ellas con su propio valor**.

Pese a ello, es importante puntualizar que Urbit tiene utilidad aparte de su red pues **cada uno de nosotros puede usar Urbit para crear documentos personales, almacenar datos y escribir código para el sistema**. Es por esta razón que pese a que la red de Urbit sea pequeña, ésta tenga valor para sus individuos.

---

**Reconocimientos:**

> - https://urbit.org/blog/the-urbit-address-space/
> - https://urbit.org/blog/value-of-address-space-pt1/
> - https://urbit.org/blog/value-of-address-space-pt2/
> - https://urbit.org/blog/value-of-address-space-pt3/
> - https://urbit.org/blog/iot/
> - https://davis68.github.io/martian-computing/lessons/lesson02-azimuth-1.html
> - https://urbit.org/understanding-urbit/urbit-id
> - https://blog.urbit.live/an-intro-to-urbit-names/

*[2. Urbit OS](2_urbitos.md) < Anterior lección* - *Siguiente lección > [4. Tu cápsula planetaria (Landscape)](4_capsula.md)*