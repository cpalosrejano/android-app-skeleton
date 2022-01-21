# DATA

Este directorio contiene todo lo relacionado con los datos que la app maneja. Ya sean de red,
de UI, o de base de datos. También contendrá la implementación de como se obtienen estos mismos
(mediante room, retrofit, etc etc)

Para ello se divide en dos directorios:

### model
Este directorio contiene los modelos que se utilicen en la app
(tanto los de red, como los de la cama de dominio, o los de UI).

### repository
Estará el patrón repositorio de cada método (login, register, users...) y como se gestionarán los
datos de estos mismos. Se p