#### Comandos utiles

* **lerna bootstrap**: Instala las dependencias de nuestros paquetes y los va a enlazar entre ellos.
* **lerna changed**: Informa que los paquetes están preparados para publicarse.
* **lerna version**: Publica una nueva version de nuestros paquetes y hace push a nuestro repositorio.
* **lerna publish**: Ademas de publicar nuestros paquetes y hacer push a nuestro repositorio actualiza nuestras dependencias.
* **lerna add**: Nos Permite agregar dependencias a 1 o mas paquetes por ejemplo:
    * **lerna add babel-core**: Esto agregaria babel-core a todos nuestros paquetes.
    * **lerna add babel-core --scope=test1**: Esto agregaria babel-core solo al paquete test1