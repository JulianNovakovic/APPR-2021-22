# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Analiza prebivalstva po zakonskem stanu v Sloveniji in primerjava z EU

Pri projektni nalogi bom primerjal prebivalstvo po različnih starostnih skupinah glede na zakonski stan po statističnih regijah v Sloveniji. Pogledal bom v kateri regiji je največ porok oziroma ločitev, kje so poročeni najmlajši oz. najstarejši ter podatke za Slovenijo nato še delno primerjal s podatki v nekaterih drugih Evropskih državah. Podatke bom večinoma vzel iz SURSA, nekatere (za druge evropske države) pa tudi iz eurostata.

## Viri podatkov:

* https://ec.europa.eu/eurostat/web/main/data/database
* https://pxweb.stat.si/SiStat/sl/Podrocja/Index/100/prebivalstvo

## Tabele

* Tabela 1 - Število ljudi glede na zakonski stan, spol in starostno skupino po regijah (stolpci): Leto, regija, spol, starostna skupina, poročeni, ločeni, vdoveli, samski (vir tabele: https://pxweb.stat.si/SiStatData/pxweb/sl/Data/-/05E2006S.px/table/tableViewLayout2/
* Tabela 2 - Število poročenih glede na starost ob poroki (stolpci): Leto, regija, spol, starostna skupina, število porok (vir tabele: https://pxweb.stat.si/SiStatData/pxweb/sl/Data/-/05M2008S.px/table/tableViewLayout2/)
* Tabela 3 - Primerjava EU s Slovenijo (stolpci): Država, leto, spol, starostna skupina, poročeni, ločeni, vdoveli, samski (vir tabele: https://ec.europa.eu/eurostat/databrowser/view/DEMO_PJANMARSTA__custom_1688196/default/table?lang=en)

## Analiza

* V katerih regijah so poročeni najmlajši, najstarejši ipd.
* Primerjava Slovenije z drugimi državami EU po številu porok, ločitev ipd.
* Primerjava Slovenije z drugimi državami EU po starosti, pri kateri se ljudje poočajo, ločujejo ipd.

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
