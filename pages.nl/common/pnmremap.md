# pnmremap

> Vervang de kleuren in een PNM afbeelding.
> Meer informatie: <https://netpbm.sourceforge.net/doc/pnmremap.html>.

- Vervang de kleuren in een afbeelding met diegene gespecificeerd in een kleurenpalet:

`pnmremap {{[-ma|-mapfile]}} {{pad/naar/kleurenpalet_bestand.ppm}} {{pad/naar/invoer.pnm}} > {{pad/naar/uitvoer.pnm}}`

- Gebruik Floyd-Steinberg dithering voor het representeren van missende kleuren in het kleurenpalet:

`pnmremap {{[-ma|-mapfile]}} {{pad/naar/kleurenpalet_bestand.ppm}} {{[-fs|-floyd]}} {{pad/naar/invoer.pnm}} > {{pad/naar/uitvoer.pnm}}`

- Gebruik de eerste kleur in het palet voor het representeren van missende kleuren in het kleurenpalet:

`pnmremap {{[-ma|-mapfile]}} {{pad/naar/kleurenpalet_bestand.ppm}} {{[-fi|-firstisdefault]}} {{pad/naar/invoer.pnm}} > {{pad/naar/uitvoer.pnm}}`

- Gebruik de gespecificeerde kleur voor het representeren van de missende kleuren in het kleurenpalet:

`pnmremap {{[-ma|-mapfile]}} {{pad/naar/kleurenpalet_bestand.ppm}} {{[-m|-missingcolor]}} {{kleur}} {{pad/naar/invoer.pnm}} > {{pad/naar/uitvoer.pnm}}`
