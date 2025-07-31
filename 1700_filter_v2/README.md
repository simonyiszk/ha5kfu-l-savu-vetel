# 1691 MHz-s interdigital szűrő NYÁK lapból

A szűrő a www.changpuak.ch/electronics/interdigital_bandpass_filter_designer.php segítségével lett megtervezve. Ezen repóban a szűrő dobozát alkotó NYÁK darabok CNC-vel való gyártásához készült fájlok szerepelnek. 
A gyártás során volt, amit át kellett tervezni, változáslista:
- a körvonalba NEM kell beleszámolni a marófej vastagságát, ezt a program tudja kezelni
- a nagyobb furatokat marófejjel tudtuk készíteni, ezeket viszont külön rétegre kellett rakni, mint a körvonal, mert a program rossz sorrendben akarta készíteni őket
- a többi furatot viszont drillként kell felvenni

A doboz kétrétegű 1,6mm-es FR4-es NYÁKlemezből készült. Az összeállítás viszonylag egyszerű volt, de az illeszkedés megkönnyítéséhez a bemarásokat tűreszelővel tágítani kellett. 

A hangolócsavarok rögzítőanyáinak készült bevágásba nagyon könnyen be lehetett forrasztani a rézből készült M4-es anyákat.

A doboz összeforrasztását megkönnyítette, hogy előre beónoztuk az illeszkedő felületeket. A fedlappal érintkező oldalakra öntapadós rézfóliát forrasztottunk, hogy a fedlappal majd jól érintkezzen. Leforrasztás előtt a hangoláshoz jól rá kell szorítani, jelenleg kis pillanatszorítóval próbálkozunk. Jobb lett volna középre is néhány csavart tervezni, mert a végeken leszorított NYÁK felpúposodik és középen nem érintkezik.

Az összeforrasztás során elrontottuk az összeállítást, az alaplapot fordítva forrasztottuk be, így az egyik tervezett csavar nem fér el a csatlakozótól, így új lyukakat kellett fúrni.

A rezonátor pálcáit először 4mm-es sárgaréz csőből készítettük el, amibe M3-as csavart forrasztottunk, de azóta lecseréltük sárgarézből esztergált pálcákra őket. Szintén sárgarézből készítettünk M3-as hangolócsavarokat is. A pálcák tervezett hossza túl nagy, még teljesen kicsavart hangolócsavarral is túl alacsony a sávkzépi frekvencia, 1-1,5mm-t le kellett belőlük reszelnem.

A korábbi szűrőnek nagyobb volt a sávszélessége (100 MHz), de kisebb a mérete. A sávszélesség csökkentésével a beiktatási csillapítás növekedett, ezért növeltem meg a doboz méreteit. A cél a maximum 0.5 dB-s beiktatási csillapítás (ehhez viszont sokáig kell hangolni a szűrőt, még nem sikerült pont jól eltalálnom).
