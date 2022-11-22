SVASTA PAMETNO ZA PROCITATI:
https://www.webprogramiranje.org/

KORISNI LINKOVI:
https://flexboxfroggy.com/
https://mastery.games/flexboxzombies/
https://fontawesome.com/icons/
https://www.svgviewer.dev/
https://bennettfeely.com/clippy/
https://animista.net/play/basic/shadow-drop-2/shadow-drop-2-left
https://getbootstrap.com/docs/5.2/getting-started/introduction/
https://grid.layoutit.com/

TEORIJA HTML&CSS:

https://www.w3schools.com/css/css_positioning.asp
https://www.w3schools.com/cssref/css_selectors.asp

TEORIJA JS:
*= - dodela vrednosti
*let - rezervisana rec u JS pomocu koje deklarisemo promenljivu
*const - rezervisana rec u JS pomocu koje deklarisemo konstante
*razlika izmedju let i const - ukoliko smo deklarisali sa const, nije moguce menjati vrednost konstanti, sem u slucaju kada
je u pitanju objekat. (tada konstanta pokazuje na taj isti objekat, ali se vrednosti unutar njega mogu menjati, dok se referenca na 
taj objekat ne sme menjati.)
    const broj = 5
    broj = 10
    ! GRESKA !

    const niz = [1, 2, 3]
    niz.push(4)
    const noviNiz = []
    noviNiz = niz
    = LEGITIMNO =

*razlika izmedju != i !==, kao i == i === - dvostruko jednako provera istinitost samo po vrednosti, dok trostruko proverava i po tipu podatka; razlicitost se takodje proverava na isti nacin

*&& - (logicko i) provera uslova koja je istinita kada su svi uslovi ispunjeni; u svakom drugom slucaju je netacno (false).
*|| - (logicko ili) provera uslova koja je istinita ukoliko je bar jedan uslov tacan.

*for, while, do...while - ciklicna struktura koja prekida svoje izvrsavanje kada uslov prestaje da bude validan.
    for(deklaracijaIterator; proveraUslova; stepenPomeranja(prelazak na sledecu iteraciju)) {
        blok koda koji se ciklicno izvrsava
    }

    deklaracijaIterator
    while(proveraUslova) {
        blok koda koji se izvrsava
        stepenPomeranja(prelazak na sledecu iteraciju)
            -ukoliko se ovaj korak ne desi, petlja zakucava u beskonacnost
    }

    do{
        blok koda koji ce se bar jednom izvrsiti
    }while(proveraUslova)

Komande u komandnoj liniji:
ls
ls -a
touch imeFajla (kreira fajl u trenutnom folderu)
mkdir imeFoldera (kreira folder u trenutnom folderu)
rm imeFajla (brise naznaceni fajl)
rm -r imeFoldera (brise navedeni folder)
cd .. (vracanje u roditeljski folder)
cd imeFajla
code .

GIT:
git config --global user.name "korisnicko ime"
git config --global user.email "korisnicki mail"
git config user.name (provera username-a)
git config user.email (provera email-a)
git clone URL (URL - uniform resource locator)
git pull (git fetch i git merge)
git add imeFajla 
git add .
git commit -m "kratka poruka komita"
git status
git log
git push


#Domaci_1

1. Napisati kod koji sabira svaki treci element u nizu. (pretpostavka da je niz brojeva u pitanju)
2. Napisati funkciju koja za prosledjeni broj ispisuje zbir njegovih cifara.
3. Napisati funkciju koja za prosledjeni broj ispisuje broj sa ciframa u obrnutom redosledu.
4. Napisati kod koji ispisuje string ukoliko mu je broj karaktera veci od 7, a ispisuje ga do pola ukoliko bilo gde u stringu postoji karakter '!'.
5. Napisati funkciju koja vraca duzinu za prosledjeni string.
6. Napisati funkciju koja racuna stepen broja. (stepenBroja(2, 3) ce vratiti rezultat 8, 2 na 3)
<<<<<<< HEAD
7. Napisati kod koji kao rezultat ispisuje koliko se puta izabrani karakter pojavio u stringu.
=======
7. Napisati kod koji kao rezultat ispisuje koliko se puta izabrani karakter pojavio u stringu.

#Domaci_2

1. Napisati kod koji ispisuje string otpozadi.
2. Napisati funkciju koja vraca poziciju trazenog elementa u nizu.
3. Napraviti niz objekata po izboru i ispisati ih u konzoli.
4. Iz postojeceg niza uzeti elemente na parnim indeksima i napraviti novi niz od tih elemenata. (pomocu push() metode)
5. Proveriti da li je prosledjena recenica u vidu stringa adekvatno interpunkcijski terminisana.

6. Iscrtati sledecu figuru za n = 5

* * * * * 
  * * * *
    * * * 
      * * 
        *

7. Iscrtati sledecu figuru za n = 5

* * * * *
* * * *
* * *
* *
*

#Domaci_3

https://nicepage.com/website-design/preview/mountain-adventure-19154?device=desktop
<<<<<<< HEAD
>>>>>>> d168150d5c69f67d0f5f98e07174ae46e7be8c16
=======

#Domaci_4

https://nicepage.com/templates/preview/pilates-studio-and-sports-16816?device=desktop
<<<<<<< HEAD
>>>>>>> 1ae096db9a6748fe4be4c5abbb2f6323821139a7
=======

#Domaci_5

https://cssgridgarden.com/
https://grid.layoutit.com/
<<<<<<< HEAD
>>>>>>> a61437b62d1e10e6c2ffdcf301b6dabfdf60fbdb
=======

#Domaci_6

https://expertmovingservices.com/
https://michalsnik.github.io/aos/
https://swiperjs.com/demos
>>>>>>> 3f8f8aa3c0632c8a6de8cb9265a0a1de887e96c2
