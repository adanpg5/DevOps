# Virtual BOX - Primeros pasos
 
  - [**¿Qué es Virtual Box?**](#qué-es-virtual-box)
  - [**¿Por qué y para qué?**](#por-qué-y-para-qué)
  - [**Instalación y configuración de nuestra primera máquina.**](#instalación-y-configuración-de-nuestra-primera-máquina)
  - [**Instalación del S.O**](#instalación-del-so)
  - [**¿Qué son las Guest Additions?**](#qué-son-las-guest-additions)
  

## **¿Qué es Virtual Box?**

Es un software de virtualización, también denominado hipervisor de tipo 2. Se utiliza para generar virtualizaciones de sistemas operativos dentro de un ordenador físico existente, generándose lo que se conoce como máquinas virtuales.

Una máquina virtual es un software que simula un sistema de computación y que tiene la capacidad de ejecutar programas como si fuera un ordenador real. Normalmente a este software se le define como «un duplicado eficiente y asilado de una máquina física«. El término actualmente incluye también a máquinas virtuales que no tienen equivalencia directa con un hardware físico.

## **¿Por qué y para qué?**

Esencialmente se utiliza para la virtualización de sistemas operativos que no podamos o queramos ejecutar en nuestro equipo informático. Permite trabajar con los sistemas operativos con normalidad, como si los instaláramos en nuestro equipo. Podemos decir que son una caja aislada dentro de nuestro ordenador, nada de dentro saldrá y genera problemas con nuestro equipo principal.

## **Instalación y configuración de nuestra primera máquina.**

En mi caso, he descargado la herramienta a través de la web oficial (https://www.virtualbox.org/), la versión 6.1

Una vez tengamos la aplicación instalada, iremos a crear una nueva máquina pinchando sobre **NUEVA**.

Elegimos el nombre que querrámos para la máquina (en mi caso le pondré el nombre de la versión del S.O que utilizaré), la ruta donde queremos instalar la máquina y el sistema operativo.

![1](./img/1.png)

Vamos a utilizar la máquina con 4GB de memoria RAM.

![2](./img/2.png)

Seleccionamos el tipo de disco (30GB, más adelante convertiremos el disco en SSD).

![3](./img/3.png)
![4](./img/4.png)

Ahora ya tenemos creada nuestra máquina.

![5](./img/5.png)

Convertimos el disco en SSD clickando el siguiente recuadro:

![17](./img/17.png)

Si queremos poder compartir bidireccionalmente el portapapeles de la máquina real tanto como de la virtual, debemos ir a Configuración>General y activarlo.

![6](./img/6.png)

También, para disfrutar de internet en la máquina virtual debemos habilitar el adaptador puente en Configuración>Red.

![7](./img/7.png)

La Extensible Firmware Interface (EFI, lit. «interfaz de firmware extensible») fue desarrollada inicialmente por Intel en el 2002. La UEFI puede proporcionar menús gráficos adicionales e incluso proporcionar acceso remoto para la solución de problemas o mantenimiento.

![18](./img/18.png)

Por último, lo más importante. La imagen ISO del sistema operativo que deseamos usar. En este caso he descargado Ubuntu 21.10 a través de https://releases.ubuntu.com/21.10/ y la añadimos como Controlador: IDE.

![8](./img/8.png)

## **Instalación del S.O**

Tenemos todo listo para iniciar la máquina.

![9](./img/9.png)

Elegiremos el idioma en el que querramos trabajar.

![10](./img/10.png)

Elegimos el tipo de instalación, que en este caso lo dejo por defecto.

![11](./img/11.png)

Instalamos el S.O en el disco que hemos creado anteriormente al generar la VDI.

![12](./img/12.png)

Nos pedirá reiniciar la máquina tras completarse la instalación.

![13](./img/13.png)

Deberemos retirar la imagen ISO de la máquina, ya que el sistema ha sido instalado correctamente.

![14](./img/14.png)
![15](./img/15.png)

Por último, como recomendación, instalaremos las "Guest Additions" de Virtual Box.

## **¿Qué son las Guest Additions?**
VirtualBox Guest Additions es una colección de controladores de dispositivos y aplicaciones de sistema diseñadas para lograr una mayor integración entre los sistemas operativos host e invitado. Ayudan a mejorar el rendimiento interactivo general y la facilidad de uso de los sistemas invitados. Fácil integración del puntero del mouse.

![16](./img/16.png)
