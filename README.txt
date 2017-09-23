# Base de dades "On Votar"

Aquest repositori conté la base de dades encriptada de la web del referèndum ("https://onvotar.garantiespelreferendum.com/")

## Estructura
La base de dades sencera està dins la carpeta "db".
Està composada de 256 carpetes, amb 256 arxius d'uns 35 kb cada arxiu, fent un total de 65536 arxius, i 2.2 GB.

## Dades
Les dades estan encriptades, 
per tant ni jo mateix sé què hi ha, només es poden desencriptar les dades corresponents a cada persona, 
fent servir una combinació del DNI + data de naixement + codi postal, i el que en resulta és el lloc on has d'anar a votar.

## Scripts
A més de la base de dades, hi ha els scripts que vaig fer servir per anar-me descarregant els arxius.
