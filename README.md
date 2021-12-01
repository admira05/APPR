# APPR-2021-22
Vzorčni repozitorij za projekt pri predmetu Analiza podatkov s programom R.


Tematika

V projektu bom analizirala preseljevanje Slovencev od leta 2000 do 2020. Predstavila bom meddržavne in regijske selitve glede na spol, potem bom analizirala tudi preseljevanje glede na starost in namen. Podatke sem pridobila na SURS-u.

Uporabila bom 5 tabel:

TABELA 1: Preseljevanje znotraj Slovenije oz. po kohezijskih regijah (stolpci: letnice, regije, spol, število ljudi, ki se je vselilo v to regijo in število ljudi, ki se je odselilo iz te regije

TABELA 2: Meddržavne selitve - priseljevanje v Slovenijo (stolpci: letnice, država predhodnega bivališča, spol, število ljudi, ki se je preselilo v Slovenijo)

TABELA 3: Meddržavne selitve - odseljevanje iz Slovenije Enaka tabela kot zgornja, le da so podatki po odseljevanju.

TABELA 4: Meddržavne selitve glede na namen selitve Cilj te tabele je predstaviti različne namene priseljevanja v Slovenijo (zaposlitev, sezonsko delo, združitev z družino, študij, drugo) glede na starostno omejitev. (stolpci: letnice, država predhodnega bivališča, starostna omejitev, namet selitve, število ljudi, ki se je preselilo)

TABELA 5: Meddržavne selitve glede na namen selitve Enaka tabela kot zgoraj, le da so podatki o različnih namenih prebivalstva, ki se odseljuje iz Slovenije.

Program
Glavni program in poročilo se nahajata v datoteki projekt.Rmd. Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta:

obdelava, uvoz in čiščenje podatkov: uvoz/uvoz.r
analiza in vizualizacija podatkov: vizualizacija/vizualizacija.r
napredna analiza podatkov: analiza/analiza.r
Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi lib/. Potrebne knjižnice so v datoteki lib/libraries.r Podatkovni viri so v mapi podatki/. Zemljevidi v obliki SHP, ki jih program pobere, se shranijo v mapo ../zemljevidi/ (torej izven mape projekta).
