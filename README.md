# GIP

Eindejaars Project

## Structuur

De ESP gaat vochtigheidsmetingen doen en bekijken of de grond van de plant droog is.
Als de grond niet droog is gaan we niets doen.
Anders gaan we het water geven.
Na het geven van de water, gaat de ESP een request sturen naar de server om te laten weten dat de plant op dat bepaald tijd stipt water heeft gekregen.
We kunnen ook zelf de planten water geven via de user-interface (bv: website).
Dit wordt gerealiseerd door WebSockets.

### Level 1

De planten automatisch water kunnen geven en dit registreren in een database.

### Level 2

Een applicatie opbouwen met WebSockets, waar we zelf de planten water kunnen geven.

### Level 3

Grafieken van het gegeven water over een bepaalde periode, in de applicatie laten zien.

## Nodige materiaal

1. ESP32
1. Water pump
1. [Water flow meter](https://www.otronic.nl/a-62712241/watersensors/water-flow-sensor/?gclid=EAIaIQobChMI0Kmt57iC-wIVFMd3Ch2C9wM4EAQYBCABEgLqLvD_BwE)
1. [Vochtigheidsmeter voor grond](https://www.digikey.be/nl/products/detail/dfrobot/SEN0114/6588525)
1. Relay
1. LEDs
1. Knoppen
