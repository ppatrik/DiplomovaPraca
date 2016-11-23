# 1. prezentácia diplomovej práce

* Prezentácia [PDF](prezentacia.pdf) a [Powerpoint](prezentacia.pptx)
* [Rozšírené zadanie k prezentácii](prezentacia.docx) - rozpracované

# Demo projekt

Led dioda ma blikat v 1 sekundovom intervale (1 sekundu svieti potom 1 sekundu nesvieti). 
Po zatlacení tlacidla led dioda prestane blikať. 
Po dalsom zatlaceni tlacidla zacne znova blikat ako to bolo na zaciatku.

Schema zapojenia aj so zakladnym `.ino` kodom.
https://circuits.io/circuits/3289375-demo-projekt-led-button

# Poznámky po prezentovaní

* preniest vyvojove nastroje z velkeho sveta (4GB ram) do sveta arduina kde je k dispozicii len 2KB ram
* je nutne v ramke pre kazdy a jeden bit rozanalyzovat ci je potrebny v jednotlivych komponentoch
* pri vyvoji planovaca zajdeme az ku compilatorom
* vyzvou je aj tvorba "klikacej aplikacie" ktora musi vediet presne sparovat tie veci z klikania ku miestam v kóde, cize potrebujeme analyzovat napisany zdrojovy kod, ci sa tam uz ta metoda nachadza alebo este nie
