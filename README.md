# json2016h1

### Json files with the gas price on Spain during the first half of 2016

This repo include json files taken daily from [minetur.gob.es](https://sedeaplicaciones.minetur.gob.es/ServiciosRESTCarburantes/PreciosCarburantes/EstacionesTerrestres/)
 aka Ministry of Industry, Energy and Tourism
This files that can be used anywhere as all **GitHub Pages** sites now have CORS headers set by default.

Just use a link like this:

```
http://datos-precio-carburante.github.io/json2016h1/{YYYYMMDD}.json
```

// example

http://datos-precio-carburante.github.io/json2016h1/20160327.json

From  [minetur.gob.es/API](https://sedeaplicaciones.minetur.gob.es/ServiciosRESTCarburantes/PreciosCarburantes/EstacionesTerrestres/) only get current day prices are available, that's why this repository could be useful if someone want to check previous prices.

You can get this files displayed on a map, and also apply some filters, here:

* App: http://app-preciocarburante.rhcloud.com/gasolina95?date=20160327
* http://app-preciocarburante.rhcloud.com/gasolina95?date=20160327&filter=only-this&admin=Provincia&list=barcelona // only Barcelona province data
* http://app-preciocarburante.rhcloud.com/gasolina95?date=20160327&filter=only-this&admin=Provincia&list=barcelona&rotulo=repsol // add brand filter

* More Info: https://raw.githubusercontent.com/sigon426/app-preciocarburante/master/README.md
* Girhub repo: http://github.com/sigon426/app-preciocarburante

Check the [ways data can be reused](http://sede.minetur.gob.es/en-US/datosabiertos/Paginas/modalidades-reutilizacion.aspx) from minetur.gob.es

### Ficheros json con el precio del carburante en España durante la primera mitad del año 2016

Este repositiorio incluye ficheros json objetidos diariamente desde el Ministerio de Industria, Energía y comercio  [minetur.gob.es](http://sedeaplicaciones.minetur.gob.es/ServiciosRESTCarburantes/PreciosCarburantes/EstacionesTerrestres/)

Estos ficheros pueden incluirse en cualquier sitio, ya que todos los sitios de **GitHub Pages** tienen activados los CORS headers por defecto.

Usa este link:

```
http://datos-precio-carburante.github.io/json2016h1/{YYYYMMDD}.json
```

// ejemplo

http://datos-precio-carburante.github.io/json2016h1/20160327.json

Desde la API del [minetur.gob.es](https://sedeaplicaciones.minetur.gob.es/ServiciosRESTCarburantes/PreciosCarburantes/EstacionesTerrestres/) solo se puede obtener el fichero con los datos del día en curso, por eso este repositorio puede ser util para alguien que quiera obtener ficheros mas antiguos.

Puedes ver los precios de cualquier día en un mapa, e incluso aplicar algún filtro, usando esta web:

* App: http://app-preciocarburante.rhcloud.com/gasolina95?date=20160327
* http://app-preciocarburante.rhcloud.com/gasolina95?date=20160327&filter=only-this&admin=Provincia&list=barcelona // solo la proviincia de Barcelona
* http://app-preciocarburante.rhcloud.com/gasolina95?date=20160327&filter=only-this&admin=Provincia&list=barcelona&rotulo=repsol // solo gasolineras REPSOL

* Información: https://raw.githubusercontent.com/sigon426/app-preciocarburante/master/README.md
* Girhub repo: http://github.com/sigon426/app-preciocarburante

Consulta las [condiciones](http://sede.minetur.gob.es/es-ES/Paginas/aviso.aspx#Reutilizacion) del minetur.gob.es para la reutilización de los datos
