Dokumentacja techniczna strony internetowej.

##   Minecraft - poradniki

Strona internetowa mająca na celu pomóc niedoświadczonym graczom, odnależć się w świecie Minecrafta.
Strona dostępna jest w języku polskim <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Flag_of_Poland_%28normative%29.svg/2000px-Flag_of_Poland_%28normative%29.svg.png" width = "25px">

## Spis treści

* [Opis projektu](#Opis-projektu)

* [Cel projektu](#Cel-projektu)

* [Wymagania](#Wymagania)

* [Layout strony](#Layout-strony)

* [Sitemap](#Sitemap)

* [Użyte języki](#Użyte-języki)

* [Autorzy](#Autorzy)

* [Licencja](#Licencja)

* [Inspiracja](#Inspiracja)

<a name="Opis-projektu"/>
<a name="Cel-projektu"/>
<a name="Wymagania"/>
<a name="Layout-strony"/>
<a name="Budowa-strony"/>
<a name="Sitemap"/>
<a name="Użyte-języki"/>
<a name="Autorzy"/>
<a name="Licencja"/>
<a name="Inspiracja"/>

# Opis projektu
Zgodnie wybraliśmy temat - blog będzie przewodnikiem do gry Minecraft stworzonej przez studio Mojang AB, którego szefem i głównym projektantem jest Markus Persson, znany szerzej jako Notch. Strona zawiera wskazówki dla początkująch graczy, którzy chcą rozpocząć swoją przygodę z grą "Minecraft". Na naszej stronie gracz, krok po kroku, pozna świat "Minecraft" i dostosuje się do niego. 


# Cel projektu
Jesteśmy dwójką uczniów łomżyńskiej ASP, których zadaniem było stworzenie strony internetowej na zajęcia Programowania Aplikacji Internetowych.


# Wymagania

Aby uruchomić stronę potrzebna jest dowolna przeglądarka internetowa. 

Preferowane przeglądarki to:
* [Mozilla Firefox](https://www.google.com/intl/pl_ALL/chrome/)
* [Google Chrome](https://www.mozilla.org/pl/firefox/)
* [Safari](https://www.apple.com/safari/)
* [Opera](https://www.opera.com/pl)
* [Internet Explorer](https://support.microsoft.com/pl-pl/help/17621/internet-explorer-downloads)
                  
# Layout strony
Przedstawiony layout strony nie ukazuje ostatecznego projektu. Służy tylko pokazaniu najważniejszych elementów.
![](https://i.imgur.com/8f2ARsD.png)

# Budowa strony
Projekt jest zbydowana z dwóch głównych grup stron. 
Pierwsza z nich to /index.html, czyli główna strona projektu zawierająca opis strony oraz jej przeznaczenie.
Drugą jest folder /blog i pliki w nim zawarte, w tym:
* index.html - główna strona bloga - zawiera opis bloga oraz jego przeznaczenie, po prawej stronie znajdują się odnośniki do innych stron bloga:
  * bloki.html
  * moby.html
  * opcje.html
  * pierwsza-noc.html
Strony składają się z 3 sekcji - nagłówka (menu), sekcji głównej (main) oraz stopki (footer).
Budowa strony /index.html:
* body
  * div#wrapper
    * header - nagłówek (menu)
      * nav
        * div.logo - odnośnik do /index.html
        * a.top-blog-button - odnośnik do /blog/index.html
    * main#index - sekcja główna
      * section#first
      * section#second
      * section#third
  * footer (stopka)
    * section
    * section
    * section.social-logo (logo GitHuba)
 
 Budowa stron blogowych (/blog):
 * body
  * div#wrapper
    * header - nagłówek (menu)
      * nav
        * div.logo - odnośnik do /index.html
        * a.top-blog-button - odnośnik do /blog/index.html
    * main - sekcja główna
      * article - artykuł, czyli lewa część postu
        * section   - akapit artykułu
          * header  - nagłówek akapitu
          * p       - treść akapitu
      * aside - część nawigacyjna strony, polecane artykuły, czyli prawa część postu
        * header - "zobacz również"
        * nav
          * section   - czyli jeden tytuł i opis polecanego artykułu
            * header  - nazwa polecanego artykułu
            * p       - opis polecanego artykułu
  * footer (stopka)
    * section
    * section
    * section.social-logo (logo GitHuba)
      


# Sitemap
![](https://i.imgur.com/BFDJ8V6.png)

# Użyte języki

* [HTML5]
* [CSS3]


# Autorzy

* **Krystian** - *Programowanie, dokumentacja* - [Github](https://github.com/ogonnn)
* **Kacper** - *Programowanie, pomysł, design* - [Github](https://github.com/malczykk33)

# Licencja
```
 MIT License

Copyright (c) [2018] [Kacper Malczyk] [Krystian Ogonowski]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

# Inspiracja
https://minecraft-pl.gamepedia.com/Strona_g%C5%82%C3%B3wna
