FiltroAEDE
==========

Lista de Filtros para Adblock Plus: Boicot a los adscritos a AEDE.

Versión actual: 2.4


Cómo añadir a AdBlock Plus:
----------

Primero necesitas [tener instalado AdBlock Plus o actualizado (2.0 o superior)]

• Para añadir filtros manualmente:
- En las preferencias de AdBlock puedes gestionar tus listas y añadir nuevas. 
- Copia la URL donde lo pida: http://raw.github.com/gangsthub/FiltroAEDE/master/ABPAEDE.txt
    - *Nota: no funciona con el esquema 'https'!*
- Recomiendo escribir en el título "Filtro Boicot a AEDE + version" para que salga bien la primera vez que aparece. El título (con la versión) se actualizará automáticamente si se le da al botón 'Actualizar'.
- (Si necesitas más detalles en las instrucciones, en pobre.tk [lo explican](http://pobre.tk/p/i/c/2-filtro-aede) muy bien)

• Cómo bloquear por archivo host:

PC
--
Copiar el contenido de HOSTSAEDE.txt a
- En WINDOWS: C:\windows\system32\drivers\etc\hosts
- En IOS: sudo pico /private/etc/hosts
- En LINUX: /etc/hosts

ANDROID
-------
- En ANDROID: instalar la aplicación (https://sufficientlysecure.org/index.php/adaway/) o (http://forum.xda-developers.com/showthread.php?t=2190753&nocache=1)
- Añadir como suscripción la url raw al archivo "HOSTSAEDE" (https://raw.githubusercontent.com/carcheky/FiltroAEDE/master/HOSTSAEDE.txt)


----------

Funcionamiento:
----------

FiltroAEDE [se compone de] dos partes o listas:

- La primera lista bloquea de manera general los dominos y subdominios de los miembros de AEDE con ABP y los scripts. Si solo estuviera esta lista, en algunas, se presentarían las webs y su contenido como si se hubiera borrado la hoja de estilo.
- Por eso es necesaria la segunda lista, bloquea el cuerpo de la página.


Notas:
----------
- MUY recomendado tener activadas otras listas como EasyList, Antisocial, Nauscopicos: [listado completo]
- Gracias por leer el README. Infórmate con medios libres o no adscritos a AEDE.

Agradecimientos:
----------
- [@j3j5]
- http://marcaspa.in/
- https://twitter.com/CanonAEDE_NO

Must Check:
----------
- https://twitter.com/CoalicionProInt
- [Artículo] de FiltroAEDE en Pobre.TK

*Gracias ;)*

#### Cualquier duda, contactar con el mail de mi perfil: [@gangsthub]
[se compone de]:https://github.com/gangsthub/FiltroAEDE/blob/master/ADPAEDE.txt
[tener instalado AdBlock Plus o actualizado (2.0 o superior)]:https://adblockplus.org/es
[@gangsthub]:https://github.com/gangsthub
[listado completo]:https://adblockplus.org/en/subscriptions
[@j3j5]:https://github.com/j3j5
[Artículo]:http://pobre.tk/p/i/c/2-filtro-aede
