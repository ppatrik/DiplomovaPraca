# Koncept prezentácií

Pri prezentacii by som asi zacal, ze ukazem nejake Arduino (idealne
nano) a poviem, ze toto zariadenie je jedno z mnohych zariadeni na
trhu, ktore akceleruju prenikanie oblasti IoT do bezneho zivota.
Potom nejaky strucny popis, ze to ma piny, ktore ide ovladat (davat
napatie) a kontrolovat (merat napatie) - teda ovladat rozne moduly
(napr. relatka), komunikovat cez rozne protokoly s inymi
zariadeniami alebo senzormi. Upozornil, by som, ze tento
mikropocitac nema operacny system, len sa tam uploadne skompilovany
program a ten sa vykonava. Tu by som ukazal trebars na kode blinku
setup/loop programovaci model (je tam aj digitalWrite) - viem si
predstavit aj nejaky analogRead, ktory kontrolujes frekvenciu
blikania. Toto je miesto na zdoraznenie parametrov mikropocitacia -
teda taktovaciu frekvenciu, velkost SRAM, ROM a flashe.

Na tomto mieste by som prezentaciu akoby strihol a ukazal svet, ako
ho poznaju sucasni vyvojari - teda silne IDE, eventove riadenie
(idealnym prikladom je GUI, ale ak nejaky message-based networking)
a znovupouzitelnost vo forme komponentov. Cez priklad GUI by som
vysvetlil, co sa chape pod pojmom eventove riadenie, co sa chape pod
pojmom komponent (ze to ma nejake lahko nastavitelne vlastnosti a
poskytuje nejake metody).

Tu je idealne miesto polozit otazku: Nedaju sa tieto 2 svety spojit?
Nemozem pripojene moduly, senzory, piny, protokoly, atd. a ich
"softverove ovladace" vnimat ako komponent s eventovym riadenim? Tu
by som zdorazil, ze taketo spojenie prinasa mnoho vyziev - ako
navrhnut system komponentov, ako navrhnut akysi softverovy
framework, do ktoreho by taketo komponenty boli vkladane, ako
navrhnut podporne aplikacie, aby islo tymto sposobom rychlo
prototypovat aplikacie (napr. okienkove aplikacie sa kedysi len
programovali, az neskor sa zacalo pouzivat
https://en.wikipedia.org/wiki/Rapid_application_development -
prostredie Delphi bolo jednym z prvych, co RAD implementovali).
Zdoraznil by som, ze vzhladom na obmedzenia Arduin, vsetko musi byt
navrhnute tak, aby kod optimalizoval kazdy jeden bajt v RAMke a
kazdu jednu instrukciu vo frameworku. Aplikacia na prototypovanie
musi byt user-friendly, co znamena okrem ineho aj analyzu kodu
(analyza kodu s cielom vhodne doplnit funkcie obsluhujuce udalosti
podla "naklikanych" veci do uz existujuceho kodu, atd.).

Potom by mohlo prist, ze ako to vyzera teraz = nejaky velmi strucny
prehlad roznych IDE a toolov pre Arduino vyvoj, aby bolo jasne, ze
existuje akesi zorientovanie sa v problematike.

A mozno az teraz by som uviedol ciele/zadanie prace a literaturu.
