# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Analiza prebivalstva po zakonskem stanu v Sloveniji

Pri projektni nalogi bom primerjal prebivalstvo po različnih starostnih skupinah glede na zakonski stan po statističnih regijah v Sloveniji. Pogledal bom v kateri regiji je največ porok oziroma ločitev, kje se poročajo najmlajši oz. najstarejši ter podatke za Slovenijo nato še delno primerjal s podatki v nekaterih drugih Evropskih državah. Podatke bom večinoma vzel iz SURSA, nekatere (za druge evropske države) pa tudi iz eurostata.

Viri podatkov:
-https://ec.europa.eu/eurostat/web/main/data/database
-https://pxweb.stat.si/SiStat/sl/Podrocja/Index/100/prebivalstvo

Oris tabel:

Tabela 1: število porok po regijah glede na starostno skupino prebivalstva za zadnjih 10 let (tu me bo zanimalo predvsem v katerih regijah se poročajo najmlajši oziroma najstarejši).

Tabela 2: Število ločitev po regijah glede na starostno skupino prebivalstva za zadnjih 10 let (to bom potem lahko primerjal z številom porok po regijah).

Tabela 3: Število vdovelih po regijah glede na starostno skupino prebivalstva za zadnjih 10 let (manj podrobno).


Tabela 4: Število porok, ločitev in vdovelih po državah (Slovenija in še nekatere druge izbrane države EU).


## Program

Glavni program in poročilo se nahajata v datoteki `projekt.Rmd`.
Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta:

* obdelava, uvoz in čiščenje podatkov: `uvoz/uvoz.r`
* analiza in vizualizacija podatkov: `vizualizacija/vizualizacija.r`
* napredna analiza podatkov: `analiza/analiza.r`

Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi `lib/`.
Potrebne knjižnice so v datoteki `lib/libraries.r`
Podatkovni viri so v mapi `podatki/`.
Zemljevidi v obliki SHP, ki jih program pobere,
se shranijo v mapo `../zemljevidi/` (torej izven mape projekta).
