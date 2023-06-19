A navigációs elemeknek funkcionálisnak kell lenniük minden képernyőméreten, ezért érdemes a mobile first elvet szem előtt tartva közelíteni a problémához. A kis képernyőméreteken két megközelítés közül választhatsz:

építesz egy vertikális navigációt (amely horizontálissá alakítható nagyobb képernyőn) vagy
egy összecsukható navbart alkalmazol (amely vertikálisan kinyitható érintésre)
A második a népszerűbb megoldás, azonban a trükközésmentes megoldáshoz JavaScriptet kellene használnunk. Emiatt most maradunk még az első változatnál, megépítjük a vertikális változatot, aztán hozzáadjuk a media queryt, a nagyobb képernyőket célozva.

Pozicionálás, formázás, speciális állapotok és media queryk
Mindegy a pontos végső megjelenés, minden navigációs elemet ugyanazon lépések segítségével építhetsz meg:

pozicionálod a navbart,
megformázod az elemeket (tipográfia, box-modell tulajdonságok),
hozzáadod a speciális állapotokra vonatkozó stílusokat (mint a hover vagy az aktív állapot), majd végül
media queryket definiálsz a nagyobb képernyőkre.