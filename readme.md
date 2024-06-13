# Instalacion de dependencias

## Dependencias de desarrollo
Solo van a existir en el ambito de desarrollo. Son los paquetes que se necesitan mientras se esta desarrollando el proyecto, pero una vez que el proyecto este listo, no van a hacer falta.
Para instalar una dependencia de desarrollo, se hace de la siguiente manera:
```
npm install -D nombre-de-la-dependencia
```
Para desinstalar una dependencia de desarrollo, se hace de la siguiente manera:
```
npm uninstall -D nombre-de-la-dependencia
```

## Dependencias de produccion
Va a irse a produccion. Estas dependencias son parte de la lógica del proyecto y son necesarias para que el proyecto funcione correctamente en produccion. Para instalar una dependencia de produccion, se hace de la siguiente manera:
```
npm install nombre-de-la-dependencia
```
Para desinstalar una dependencia de produccion, se hace de la siguiente manera:
```
npm uninstall nombre-de-la-dependencia
```

## Dependencias Globales
Son instalaciones en todo el sistema operativo (va de la mano de la version de NodeJS). Estos paquetes no estan asociados a un proyecto en especifico. Para instalar una dependencia global, se hace de la siguiente manera:
```
npm install -g nombre-de-la-dependencia
```

Si queremos desinstalar una dependencia global, se hace de la siguiente manera:
```
npm uninstall -g nombre-de-la-dependencia
```