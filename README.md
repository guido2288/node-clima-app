# App De clima

App de consola que busca el ciudad y nos trae la informacion del clima de la ciudad celeccionada. Se conecta a la Api de [Mapbox](https://www.mapbox.com/) y [OpenWeather](https://openweathermap.org/)

```
=======================
 Seleccione una opción 
=======================

? ¿Qué desea hacer? (Use arrow keys)
❯ 1. Buscar cuidad 
  2. Historial 
  0. Salir 

```

Podemos seleccionar la ciudad buscada dentro de un listado de 5 resultados

```
=======================
 Seleccione una opción 
=======================

? ¿Qué desea hacer? 1. Buscar cuidad
? Ciudad:  Mendoza
? Seleccione lugar (Use arrow keys)
❯ 0. Cancelar 
  1. Mendoza, Mendoza, Argentina 
  2. Mendoza, Argentina 
  3. Mendoza General Hospital, A. Morales Street, Santa Maria, Bulacan 3022, Phi
lippines 
  4. Mendozas Taqueria & Cantina, Vía Argentina, Panamá, Panamá, Panama 
  5. Mendoza, Weissenbruchlaan 149, Rotterdam, South Holland 3054 LM, Netherland
(Move up and down to reveal more choices)
```

Información que nos trae
```
Información de la ciudad

Ciudad: Mendoza, Mendoza, Argentina
Lat: -32.88333
Lng: -68.83333
Temperatura: 26.77
Mínima: 26.77
Máxima: 26.77
Clima Actual: cielo claro


? 
Presione Enter para continuar
```

Y cuenta con el historial de hasta las ultimas 5 busquedas. Almacenadas en un archivo .json

```
=======================
 Seleccione una opción 
=======================

? ¿Qué desea hacer? 2. Historial
1. Mendoza, Mendoza, Argentina
2. Córdoba, Córdoba, Argentina
3. Buenos Aires, Argentina


? 
Presione Enter para continuar
 
```
# Instrucciones

 1. npm init
 2. Configurar las api key en el archivo .env




