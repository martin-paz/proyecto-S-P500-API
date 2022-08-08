![S&P500](./img/descarga.jpg)
# ***Proyecto: S&P 500 + API yfinance***

<p>
El objetivo de este proyecto es brindar un analisis tanto cuantitativo como cualitativo de los movimientos diarios e intradiarios, retorno gap, variacion media, el calculo del VIX, y por medio de un grafico mostrar cuales son las mejores empresas e industrias en el franja de tiempo desde el año 2000 y 2021 inclusive
<p>

# KPI
<p>
En este apartado se buscar evaluar el compartamiento de como poder invertir teniendo en cuanta los objetivos ya nombrados arriba:<br><br>
Retornos de los movimientos GAP<br>
Retorno movimientos Intradiarios<br>
Variacion media diaria<br>
Volatilidad diaria<br>
Grafico VIX<br>
Variacion: mejores empresas<br>
Variacion: mejores sectores


<p>


# Extraccion de los simbolos de cada indice y uso de la api yfinance
<p>
El proposito de este apartado es la extraccion de los simbolos de las empresas por medio de wikipedia y el uso de la api yfinance guardar todos los datos que correspondan a cada simbolo extraido de wikipedia
Para traer dichos simbolos se uso la libreria pandas para leer dicho link y posteriomente luego guardar los simbolos en una lista. Para la extraccion de datos de la api Yfinance de yahoo se toma como franja de tiempo desde el año 2000 hasta el año 2021 con un intervalo de tiempo de 1 dia
<p>

## Analisis de los KPIs <br> <br>

## Movimientos gap.

<p >El mejor dia para invetir teniendo en cuenta el retorno gap es el dia Martes<p> <br>

![retorno Gap](./img/retorn_gap.png) <br><br>

## Movimientos intradiarios. <br>

<p> El mejor dia para invitar teniendo en cuantos los movimientos intradiarios es el dia jueves <p><br>

![retornoIntra](./img/retorn_intra.png) <br><br>

# Variacion media

El dia con mayor variacion media es el dia Martes <br>

![VariacionMEdia](./img/variacion-media.png) <br><br>

# Volatilidad por dia.

El dia con mayor volatilidad es el dia Miercoles<br>

![volatilidadDia](./img/volatilidad.png) <br><br>

# Grafico VIX entre los años 2020-2021

Como se puede apreciar, la fecha de mas alta volatilidad que afecto al sp500 fue en junio del 2009, que empezo con un alto valor la primera de semana y empezo a descender al final de la semana del mismo mes <br>

![vix](./img/VIX.png) <br><br>

# Las mejores empresas S&P500

variacion historica de las mejores empresas del sp500 desde el año 2000 hasta el 2021 inclusive en las que invertir <br>

![empresas](./img/empresas_00_21.png) <br><br>

# Mejores sub-industrias 

mejores sectores del sp500 entre el año 2000 y el año 2021<br>

![empresas](./img/industrias.png) <br><br>