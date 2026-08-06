+++
date = '2026-08-06T15:21:57+02:00'
draft = true
title = 'Exemples de com es fan les coses en Markdown'
featured_image = "img/esbart_tothom.jpg"
+++

# Seccio 1

# Seccio 2

## Subseccio 2.1

### Subseccio 2.1.1

Aixo es un paràgraf.

No s'han de posar espais ni separacions al principi.  
També hi poden haver salts de línia dins el mateix paràgraf, es fan posant dos espais al final de la línia anterior.

Text **en negreta**, *en cursiva*, i ***en negreta cursiva*** 

Es poden fer també separadors horitzontals:

---


* Així és com a fa una llista no numerada
* Una cosa
* Una altra cosa
* Més coses

1. I així és com es fa una llista numerada
2. Cosa dos
3. Cosa 3

* Es poden fer llistes
  * amb múltiples nivells
  * un sota l'altra
* I fins i tot
  1. Es poden combinar llistes numerades
  2. i no numerades
* També es pot fer que un element d'una llista  
  contingui mútiples línies
  
  I fins i tot múltiples paràgrafs,  
  posant dos espais al principi de cada línia

* I si necessitem començar un element d'una llista no numerada amb un número?
* 1986\, quin gran any. Posem una contrabarra al final del número.

> Així és com es fa una cita  
> que pot ser més d'una línia
>
> També es poden citar en múltiples paràgrafs
>
>> I fins i tot es pot citar dins una cita
>
> * Dins una cita es poden fer servir
> * **Tots** els altres elements


# Imatges
Es poden incrustar imatges al text així:    
![Descripció de la imatge](../../img/logo_esbart.jpg)
![Imatge molt grossa](../../img/esbart_tothom.jpg)

Sobre les imatges:
* Cada pàgina té una imatge a la capçalera de dalt
  * La imatge de capçalera és el paràmetre "featured_image" de la capçalera
  * La ruta és "img/nom_de_fitxer.jpg"
  * La imatge la redimensionarà automàticament el navegador perquè ocupi tot l'ample de la pàgina
  * Interessa que siguin imatges prou grans per ocupar tot l'ample, però no gegants, que pesin massa
* Les imatges addicionals que volguem incrustar a mitja pàgina
  * La ruta és "../../img/nom_del_fitxer.jpg"
  * Si tenim moltes imatges, podem organitzar-les en directoris, com ens vagi bé (probablement sota img/) i referenciar-les amb la seva ruta
  * Si la imatge és petita (com el logo de l'esbart) es queda al tamany original
  * Si la imatge és més gran que l'espai disponible per a text, el navegador la redimensionarà automàticament (però ojo que no sigui gegant, que pesen massa!)

# Enllaços
Així és com es fa un enllaç a [Duck Duck Go](https://duckduckgo.com)  
Hi ha una cas especial, si l'adreça que volem posar és igual al text: <http://destreses.cat>

I així és com es fa un enllaç a [una altra pàgina interna](../../nosaltres)
Fixa't en la barra d'adreces:
* Aquesta pàgina és a ```/actuacions/prova/```
* Per tant ".." es refereix a ```/actuacions```
* "../.." es refereix a ```/```, l'adreça principal del web
* "../../nosaltres" es refereix a ```/nosaltres```, el lloc on volem anar
* Interessa fer servir sempre enllaços relatius (referint-nos a pisos amunt des d'on estiguem) i no adreces completes, perquè així funcionarà tant a la web normal com a futur.

# Emojis
Haig d'admetre que això no ho he fet servir mai, perquè sempre faig webs avorrides, però el jovent feu servir aquestes coses :wink:

En [aquesta web](https://github.com/ikatyang/emoji-cheat-sheet/) hi ha una llista de tots els emojis suportats.

Es fan servir així: :dancing_men::dancing_women:

# Empotrar vídeos de youtube:
Necessites la referència del vídeo, de la URL de youtube.
Per exemple, per empotrar aquest vídeo: [https://www.youtube.com/watch?v=ObEBYwO0HCw](https://www.youtube.com/watch?v=ObEBYwO0HCw)
```
{{< youtube ObEBYwO0HCw >}}
