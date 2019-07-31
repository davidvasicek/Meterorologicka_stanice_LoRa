# Meterorologicka_stanice_LoRa

Meteorologická stanice ...... 

### Komponenty
 - vnější mnechanické díly k meteostanici WH1080 a WH1090 (obsahuje anemometr, srážkoměr, ukazatel směru větru) [e-shop](https://www.hadex.cz/t110-vnejsi-mechanicke-dily-k-meteo-wh1080-a-wh1090/) | [technická specifikace](https://www.sparkfun.com/datasheets/Sensors/Weather/Weather%20Sensor%20Assembly..pdf)
- Teplotní a vlhkostní čidlo DHT22 [e-shop]() |  [datasheet]()

#### Zapojení

###### Srážkoměr

Srážkoměr (člunkový) - Člunkový srážkoměr zachycuje srážky, které svádí na dělený překlápěcí člunek. Po naplnění jeho jedné poloviny příslušným objemem vody (odpovídajícím úhrnu srážek např. 0,1 mm) se člunek překlopí, čímž z první poloviny vyteče voda a srážka začne stékat do druhé poloviny. Překlopení je zaznamenáno a jejich počet určuje celkový úhrn srážek. Člunkové srážkoměry se vyrábí s různou záchytnou plochou (např. 200 cm² nebo 500 cm²). Automatické srážkoměry používané k profesionálnímu měření jsou vybaveny vytápěním, aby bylo možno kontinuálně měřit i množství tuhých srážek. [odkaz1]


Princip funkčnosti srážkoměru spočívá v elektromagnickém jazýčkovým spínačem..... K desce Arduino můžeme tento srážkoměr připojit dvoudrátově přes PULL_DOWN rezistor 






výpočet rychlosti věru http://cactus.io/hookups/weather/anemometer/davis/hookup-arduino-to-davis-anemometer-wind-speed
program pro vytváření DPS https://howtomechatronics.com/tutorials/arduino/arduino-wireless-weather-station-project/


http://cactus.io/projects/weather/arduino-weather-station












odkaz1 ...https://cs.wikipedia.org/wiki/Sr%C3%A1%C5%BEkom%C4%9Br
