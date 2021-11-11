title: 5. Manual del operador
++++

# Manual del operador

![](posts/images/urblady.gif#inline)
![](posts/images/urman.gif#inline)

Tienes una gran variedad de opciones para instalar Urbit, puedes hacer uso del siguiente índice para localizar la opción que te sea más cómoda:

> Actualmente todas las guías son mediante el minado de un cometa, me es inviable la obtención de un planeta, espero en un futuro poder hacer una guía enfocada a identidades de mayor nivel que un cometa. Pese a todo, espero que os sirva vuestro cometa como punto de partida para introduciros en Urbit.

1. ```~localhost``` - Operando con **Port GUI**.
2. ```~localhost``` - Operando con **CLI en Linux (Debian/Ubuntu)**. */~pendiente/*
3. ```~localhost``` - Operando con **CLI en Windows (WSL2)**. */~pendiente/*
4. ```~localhost``` - Operando con **CLI en Linux (Debian/Ubuntu) y Docker**. */~pendiente/*
5. ```~localhost``` - Operando con **CLI en Windows (WSL2) y Docker**. */~pendiente/*
6. ```~cloud``` - Operando con **CLI en servidor compartido**. */~pendiente/*
7. ```~cloud``` - Operando con **CLI en VPS**. */~pendiente/*
8. ```~hosting``` - No quiero operar.

He querido diferenciar aquellas opciones donde tenemos acceso físico a los datos (~localhost) de aquellas donde nuestros datos se encuentran en la nube (~cloud). También existe la opción para aquellos que no quieran hacer uso de un hosting.

## 1. Operando con Port GUI.

Es sin lugar a dudas **la opción más directa y accesible**. Para ello únicamente debemos instalar Port, dependiendo de nuestro sistema operativo tendremos diferentes formas:

- **MacOS**:

Simplemente descarga y abre el archivo ```.dmg``` de [Github](https://github.com/urbit/port/releases/latest/download/Port.dmg).

- **Linux**:

Para Linux se hace uso de **snap**. Si tienes snap ya instalado simplemente escribe en un terminal ```sudo snap install port```.
Si no tienes instalado **snap**, puedes seguir las instrucciones que ofrecen en su documentación para tu distribución específica (https://snapcraft.io/docs/installing-snapd)

- **Windows**:

Este último mes ha sido lanzada la versión para Windows, de esta opción podéis encontrar algún que otro bug. Esperemos que el desarrollador sea capaz de solucionarlo lo antes posible.

La dirección de descarga de la aplicación se encuentra en su repositorio de Github en la pestaña de **Releases** (hhttps://github.com/urbit/port/releases/latest/download/PortSetup.exe). Descargad aquél archivo ```.exe``` que se encuentre en la última versión liberada.

---

Una vez tengamos instalado Port, nos encontraremos con la siguiente pantalla de bienvenida donde se presentan todas las opciones que nos ofrece Port:

![](posts/images/port_home.png#center)

Como método introductorio haremos uso de la opción **Start without an ID** para minar un cometa. Simplemente debemos hacer click en esa opción y Port se encargará de todo lo demás.

## 8. No quiero operar.

Existen diversos proveedores que te venderan un planeta y haran toda la operativa por ti. Esta opción es bastante simple y seguramente tendrá un coste de mantenimiento. 

Urbit está diseñado para que sea **portable**. Ésto significa que pese a que te encuentres bajo los servicios de un proveedor, puedas posteriormente ser tú el que se ocupe de la operativa. Un buen hosting debe asegurarte que en un futuro puedas obtener tus datos y así poder iniciar tu planeta sin perder ningún tipo de información.

Al utilizar uno de los siguientes proveedores se da por hecho que **confías tus datos a ellos**, pese a todo, mientras tengas tú planeta éste siempre te pertenecerá.
Alguno de los proveedores son:

- [Escape pod store](https://www.escapepod.store/)
- [Third Earth](https://third.earth/)
- [Tlon Corporation](https://tlon.io/)
- [UrbitHost](https://urbithost.com/)

---

**Reconocimientos:**

> - https://urbit.org/using/os/basics
> - https://subject.network/posts/urbit-wsl2/
> - https://subject.network/posts/urbit-windows-docker/
> - https://linuxize.com/post/how-to-use-linux-screen/
> - https://blog.remilia.org/launching-urbit-on-windows/
> - https://blog.remilia.org/urbit-cloud-host/
> - https://urbit.org/getting-started/cli

*[4. Tu cápsula planetaria (Landscape)](4_capsula.md) < Anterior lección* - *Siguiente lección > [6. Udon: markdown para Urbit ](6_udon.md)*
