>### [Dark Sky API Request Parameters][1]
[1]:https://darksky.net/dev/docs#forecast-request
#### units=[units] 

|units|si|ca|uk2|us|auto|
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|Temperature|**°C**<br>(Degrees Celsius)|**°C**<br>(Degrees Celsius)|**°C**<br>(Degrees Celsius)|**°F**<br>(Degrees Fahrenheit)|-|
|Wind Speed|**m/s**<br>(Meteres per second)|**km/h**<br>(Kilometers per hour)|**mph**<br>(Miles per hour)|**mph**<br>(Miles per hour)|-|
|Distance|**km**<br>(Kilometers)|**km**<br>(Kilometers)|**mi**<br>(Miles)|**mi**<br>(Miles)|-|
|Precip Intensity|**mm/h**<br>(Millimeters per hour)|**mm/h**<br>(Millimeters per hour)|**mm/h**<br>(Millimeters per hour)|**in/h**<br>(Inches per hour)|-|
|Precip Accumulation|**cm**<br>(Centimeters)|**cm**<br>(Centimeters)|**cm**<br>(Centimeters)|**in**<br>(Inches)|-|
|Pressure|**hPa**<br>(Hectopascals)|**hPa**<br>(Hectopascals)|**hPa**<br>(Hectopascals)|**mbar**<br>(Millibar)|-|

**Temperature**  
~~`apparentTemperatureHigh`~~, ~~`apparentTemperatureLow`~~, `apparentTemperatureMax`, `apparentTemperatureMin`, `dewPoint`, `Temperature`, ~~`temperatureHigh`~~, ~~`temperatureLow`~~, `temperatureMax`, `temperatureMin`  

**Wind Speed**  
`windGust`, `windSpeed`

**Distance**  
`nearest-station`, `nearestStormDistance`, `visibility`

**Precip Intensity**  
`precipIntensity`, `precipIntensityMax`

**Precip Accumulation** (snowfall)  
`precipAccumulation`

**Pressure**  
`pressure`

### Common
**% (Percent)**  
`cloudCover`, `humidity`, `precipProbability`

**° (Degrees)**  
`nearestStormBearing`, `windBearing`

**DU ([Dobson units](https://en.wikipedia.org/wiki/Dobson_unit))**  
`ozone`



>### Links

[International System of Units](https://en.wikipedia.org/wiki/International_System_of_Units)

[Imperial units](https://en.wikipedia.org/wiki/Imperial_units)

[Metrication Conversion process](https://en.wikipedia.org/wiki/Metrication#Conversion_process)


