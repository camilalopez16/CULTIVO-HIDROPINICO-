# CULTIVO-HIDROPONICO-
- ᴘʀᴏᴛᴏʏᴘᴇ ᴏғ ᴛʜᴇ ᴍᴏɴɪᴛᴏʀɪɴɢ ᴀɴᴅ ɪʀʀɪɢᴀᴛɪᴏɴ sʏsᴛᴇᴍ ᴏғ ᴀ ʜʏᴅʀᴏᴘᴏɴɪᴄ ᴄʀᴏᴘ ᴡɪᴛʜ ᴛʜᴇ ᴘɪᴄ16ғ15244.


En este repositorio se encontrará el informe, el código y los anexos de un Cultivo realizado por Juan Camilo Triana y María Camila López. principalmente, este tiene como objetivo desarrollar un prototipo para el monitoreo y riego de un cultivo hidropónico; sin dejar atrás que también se desea diseñar un prototipo no solo mecánico sino también digital. de igual manera, la implementación de los algoritmos para su funcionamiento básico utilizando el PIC16F15244. por ultimo, se lleva a cabo la validación experimental del funcionamiento del sistema.

Para poder hablar de esto, principalmente se necesita saber en que consiste. entonces, un cultivo es aquel que prescinde totalmente de la tierra para cultivar los alimentos.
de igual manera, además, de este se puede sacar provecho ya que es perfecto para el ahorro de recursos, fundamentalmente de agua gracias a la reutilización de la misma y los alimentos son más seguros por la ausencia de productos químicos y de riesgos de enfermedades que se producen en la tierra.

El cultivo en sí va a monitorear dos variables de importancia en el cultivo, serán la temperatura y la humedad las magnitudes que permitirán tomar decisiones en el cuidado del cultivo, subsistencia en las condiciones específicas requeridas por el tipo de planta que se vaya a sembrar, además el montaje contará con un sensor de nivel en su tanque suministrador de agua el cual dará conocimiento del estado del nivel de agua restante en el sistema, además de proveer seguridad ya la motobomba que alimentará al cultivo.

# DOCUMENTACIÓN 
- http://ww1.microchip.com/downloads/en/DeviceDoc/PIC16F15213-14-23-24-43-44-Data-Sheet-DS40002195B.pdf.
-  https://www.microchip.com/wwwproducts/en/PIC16F15244.     
- http://ww1.microchip.com/downloads/en/DeviceDoc/PIC16F15244-Curiosity-Nano-Hardware-User-Guide-DS50003045A.pdf.

-  https://microchipdeveloper.com/tls2101:start.


# Software utilizado

- https://www.microchip.com/en-us/development-tools-tools-and-software/mplab-x-ide.
-  https://www.microchip.com/en-us/development-tools-tools-and-software/mplab-ecosystem-downloads-archive.
-  https://www.microchip.com/en-us/development-tools-tools-and-software/embedded-software-center/mplab-code-configurator.
-  https://www.microchip.com/forums/f249.aspx.
-  https://packs.download.microchip.com/.

# Materiales 

![WhatsApp Image 2021-05-27 at 3 51 29 PM](https://user-images.githubusercontent.com/80223879/119895489-75f91f80-bf03-11eb-8da5-0f3aa7de3db2.jpeg)

# Configuración 


La implementaci´pon se hará en un cultivo donde a base de sensores se tomarán desiciones para llevar a cabo acciones especificas, las cuales son: regar, bombear agua y mostrar en pantalla valores generados por los sensores. 
![1](https://user-images.githubusercontent.com/80223879/119896559-ce7cec80-bf04-11eb-8e6d-4b57a6b28748.png)


# Como Utilizarlo

La función que lleva a cabo el proyecto se basa en tomar las decisiones dependiendo de los valores arrojados por los sensores como la humedad, temperatura, entre otros. Así mismo como la implementación de modulación y muestreo para tomar señales análogas convirtiendolas a digitales para que el PIC pueda leer estos comandos 
