---
layout: wpub
title: "Zadanie 2."
date: 2016-03-10
category: wpub
---

Druhe zadanie pozostava z prace s DocBook. Zakladom prace bola sablona, ktoru nam poskytli, ale aj ta vyzadovala upravy na to, aby som docielil pozadovany vysledny produkt.

### Pouzite elementy

Elementy, ktore som pridal oproti tym, co boli poskytnute boli:

* __itemizedlist__ - zoznam necislovanych poloziek (ako napr. tento)
* __indexterm__ - oznacenie pojmu pre index pojmov
* __footnote__ - poznamka pod ciarov
* __table__ - tabulka
* __figure__ - obrazok
* __emphasis__ - zvyraznenie textu

Okrem tychto elementov som samozrejme pouzil aj ich dalsich potomkov, ktori boli potrebny na vykonanie toho co som potreboval. Niektorim elementom som nastavoval aj atributy. Napr. *width* a *scalefit*, aby obrazky boli skalovane podla potreby. Dalej *role* pre zvyraznenie textu, aby bol hruby. Roze *id* atributy, potrebne na odkazovanie v ramci dokumentu. Najzaujimavejsie vsak boli podla mna atributy elementu *xref*, ktore som musel nastavovat, aby odkazy na obrazky boli spravne sklonovane.

### Zmeny v sablonach a parametroch

Najvacise zmeny som robil v sablone pre abstrakt. Ako v slovencine tak aj v anglictine. Nakolko jediny abstrakt v mojej praci bola anotacia, tak som tuto sablonu poupravoval na mieru, ktora je u nas fakultou predpisana. Dalsimi zmenami v parametroch som docielil, ze kapitola (najvacsia jednotka textu) sa neoznacovala slovom *Kapitola*, ale pramo nazvom kapitoly aj s nasledujucim poradovym cislom, zmenu v cislovani tabuliek a obrazkov, zmeny vo formatovani tabuliek, generovanie zoznamu obrazkov a tabuliek, formatovanie popiskov pre tabulky a obrazky atd.

### Zhrnutie

Vysledny dokument sice nie je presna kopia vzoroveho, ale vo lisi sa len v zopar veciach. Praca s DocBook-om bola velmi zaujimava a hlavne v tom, ze vela veci bolo vhodne nastavenych off-the-shelf a pritom sa vsetko dalo extenzivne modifikovat. Tento proces modifikacie vsak bol celkom narocny, hlavne koli vyhladavaniu dokumentacie. Robili sme s verziou 4.3 a verzia 5.0 ma obsaznu, ajked neprehladnu, dokumentaciu. k verzii 4.3 tej dokumentacie bolo pomenej (mozno neviem kde hladat)