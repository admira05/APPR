# APPR-2021-22
Vzorčni repozitorij za projekt pri predmetu Analiza podatkov s programom R.


*Tematika*

V projektu bom analizirala preseljevanje Slovencev od leta 2000 do 2020. Predstavila bom meddržavne in regijske selitve glede na spol, potem bom analizirala tudi preseljevanje glede na starost in namen. Podatke sem pridobila na SURS-u.

Uporabila bom 4 tabele, katere bom najprej preuredila po stolpcih. Vsako tabelo bom tudi grafično predstavila tako, da bodo razvidni trendi oz vzorci. 

TABELA 1: *Preseljevanje znotraj Slovenije*
Za vsako leto posebej bom predstavila število ljudi, ločenih po spolu, ki so preseljevali med regijami. Selitve bom obravnavala glede na 12 statičnih regij v Sloveniji.
Grafični prikaz te tabele bo zemljevid.
(stolpci: letnice, regije, spol, število ljudi, ki se je vselilo v to regijo in število ljudi, ki se je odselilo iz te regije).

TABELA 2: *Meddržavne selitve - priseljevanje v Slovenijo glede na starost in izobrazbo* 
Cilj tabele je prikazati število ljudi, ločenih v različne starostne skupine in ravni izobrazbe, ki so se priselili v Slovenijo v času med letma 2000 in 2020. 
(stolpci: letnice, spol, starostna omejitve, stopnja izobrazbe,vrednost oz. število ljudi, ki se je priselilo v Slovenijo)

TABELA 3: *Meddržavne selitve - priseljevanje v Slovenijo glede na državo predhodnega bivališča* 
V tej tabeli bo razvidno koliko ljudi se je iz drugih držav priselilo v Slovenijo, pri čemer bom dodala še starostno omejitev. Tabelo bom grafično prikazala s stolpčnim grafom.
(stolpci: letnice, država predhodnega bivališča, starostna omejitev, število ljudi)

TABELA 4: *Meddržavne selitve glede na namen selitve*
Cilj te tabele je analizirati število ljudi, ki se je preselilo iz drugih držav v Slovenijo, glede na različne namene priseljevanja (zaposlitev, sezonsko delo, združitev z družino, študij in drugo). 
(Stolpci: letnice, namen selitve, število ljudi, ki se je priselilo)



*Program*

Glavni program in poročilo se nahajata v datoteki projekt.Rmd. Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta: 
obdelava, uvoz in čiščenje podatkov: uvoz/uvoz.r 
analiza in vizualizacija podatkov: vizualizacija/vizualizacija.r 
napredna analiza podatkov: analiza/analiza.r

Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi lib/. Potrebne knjižnice so v datoteki lib/libraries.r Podatkovni viri so v mapi podatki/. Zemljevidi v obliki SHP, ki jih program pobere, se shranijo v mapo ../zemljevidi/ (torej izven mape projekta).
