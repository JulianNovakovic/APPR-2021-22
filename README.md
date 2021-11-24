# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Analiza prebivalstva pozakonskem stanu v Sloveniji

Pri projektni nalogi bom primerjal prebivalstvo po različnih starostnih skupinah glede na zakonski stan po statističnih regijah v Sloveniji. Pogledal bom v kateri regiji je največ porok, ločitev, kje se poročajo najmlajši oz. najstarejši ter podatke za Slovenijo nato še delno primerjal s podatki v nekaterih drugih Evropskih državah. Podatke bom večinoma vzel iz SURSA, nekatere pa tudi iz eurostata. 

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
