---
layout: wpub
title: "Zadanie 3."
date: 2016-05-12
category: wpub
---

Tretie zadanie pozostava z vytvorenia si vlastneho "jazyka" na transformaciu XML prezentacie do citatelnej XHTML a PDF podoby. Houzial, koli casovej tiesni som bol schopny spravit iba XHTML verziu.

Forma XML dokumentu je popisana pouzitim definicie XML schemy. Na tuto schemu sa potom XML subor odkazuje a voci nej sa validuje. Tym sa obmedzuju elementy pouzite v XML prezentacii.

Pri transformacii kazdy element slide tvori samostatny XHTML dokument. 

### Opis pouzitych elementov

V XML prezentacii som umoznil pouzivanie nasledujucich elementov

* __peresentation__ 
  * root element XML-ka a resprezentuje objekt prezentacie
* __info__
  * informacie o elemente, v ktorom sa nachadza. Moze byt v elemente presentaton, alebo slide
  * obsahuje informacie o autorovi, nazve a datume vytvorenia
* __section__
  * rozdeluje preentaciu do logickych sekcii
* __slide__
  * predstavuje jeden slide prezentacie. Mozu sa v nom nachadzat elementy info (uz opisany) a content
* __content__
  * predstavuje realny obsah prezentacie. Jeho potomkami su elementy typu block. V jednom slajde mozu byt maximalne 2 bloky (vtedy sa umiestnia vedla seba). Ak je blok iba jeden, tak zabera celu plochu prezentacie.
* __blok__
  * moze mat dcerske elementy ul (unsorted list), p (paragraf) a image (obrazok)
* __ul__
  * inspirovane HTML
* __li__
  * inspirovane HTML. Obsiahnuty text musi byt obaleny paragrafom
* __p__
  * inspirovane HTML. Ma zmesany obsah (okrem textu moze obsahovat element emphasis)
* __emphasis__
  * zvyraznenie casi textu (bold)
* __image__
  * obsahuje cestu k obrazku, ktory sa ma zobrazit
