# Base de dades "On Votar"

Aquest repositori conté una còpia de la web "on-votar" i la base de dades corresponent amb la informació d'on anar a votar.

## Web original
Tots els arxius s'han descarregat de https://onvotar.garantiespelreferendum.com/

## Web
A la carpeta "web" hi ha la web, amb una petita modificació per cridar la base de dades directament des d'aquest repositori (per tant, descarregar la base de dades és opcional).

## Estructura
La base de dades sencera està dins la carpeta "db".
Està composada de 256 carpetes, amb 256 arxius d'uns 35 kb cada arxiu, fent un total de 65536 arxius, i 2.2 GB aproximadament.

### Dades
Les dades de la base de dades estan encriptades, 
per tant no es poden llegir, només es poden desencriptar les dades corresponents a cada persona, 
fent servir una combinació del DNI + data de naixement + codi postal, i el que en resulta és simplement el lloc on anar a votar.

## Scripts
A més de la base de dades, hi ha els scripts que vaig utilitzar per descarregar els arxius de la base de dades

