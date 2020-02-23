### Units of Measure
`https://api.darksky.net/forecast/[key]/[latitude],[longitude]?exclude=[blocks]&lang=[language]&units=[units]`

#### units=[units] 

|units|si|ca|uk2|us|auto|
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|Temperature|**°C**  (Degrees Celsius)|**°C**  (Degrees Celsius)|**°C**  (Degrees Celsius)|**°F**  (Degrees Fahrenheit)|-|
|Wind Speed|**m/s**  (Meteres per second)|**km/h**  (Kilometers per hour)|**mph**  (Miles per hour)|**mph**  (Miles per hour)|-|
|Distance|**km**  (Kilometers)|**km**  (Kilometers)|**mi**  (Miles)|**mi**  (Miles)|-|
|Precip Intensity|**mm/h**  (Millimeters per hour)|**mm/h**  (Millimeters per hour)|**mm/h**  (Millimeters per hour)|**in/h**  (Inches per hour)|-|
|Precip Accumulation|**cm**  (Centimeters)|**cm**  (Centimeters)|**cm**  (Centimeters)|**in**  (Inches)|-|
|Pressure|**hPa**  (Hectopascals)|**hPa**  (Hectopascals)|**hPa**  (Hectopascals)|**mbar**  (Millibar)|-|
|Barometer|-|-|-|**in**  (inHg - Inches of Mercury)|-|

**Temperature**  
~~`apparentTemperatureHigh`~~, ~~`apparentTemperatureLow`~~, `apparentTemperatureMax`, `apparentTemperatureMin`, `dewPoint`, `Temperature`, ~~`temperatureHigh`~~, ~~`temperatureLow`~~, `temperatureMax`, `temperatureMin`  

**Wind Speed**  
`windGust`, `windSpeed`

**Distance**  
`nearest-station`, `nearestStormDistance`, `visibility`

**Precip Intensity** (rain)  
`precipIntensity`, `precipIntensityMax`

**Precip Accumulation** (snow)  
`precipAccumulation`

**Pressure**  
`pressure`  
uk2: **hPa** (Hectopascals), but **mbar** (Millibar) by BBC in U.K. 

**Barometer** en-US  
[Pressure hPa|mbar] = [Barometer in(inHg)] x 33.8639

### Common
**% (Percent)**  
`cloudCover`, `humidity`, `precipProbability`

**° (Degrees)**  
`nearestStormBearing`, `windBearing`

**DU ([Dobson units](https://en.wikipedia.org/wiki/Dobson_unit))**  
`ozone`



>### Links
[Dark Sky API Request Parameters](https://darksky.net/dev/docs#forecast-request)
[International System of Units](https://en.wikipedia.org/wiki/International_System_of_Units)  
[Imperial units](https://en.wikipedia.org/wiki/Imperial_units)  
[Metrication Conversion process](https://en.wikipedia.org/wiki/Metrication#Conversion_process)  
[List of public broadcasters by country](https://en.wikipedia.org/wiki/List_of_public_broadcasters_by_country)

