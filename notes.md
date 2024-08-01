# Procesas

- [x] pradinė failų struktūra:
    - index.html
    - gitignore
    - main.css (bet ne vienintelis)
- [x] Paviešinti projektą per Github Pages (gausim URL)
- [x] Readme.md
    - skirta aprašyti kas, ką ir kodėl daro
    - įterpti nuorodą į galiojantį dizainą
    - įterpti nuorodą, kur tas kodas gali būti pamatytas
- [x] atlikti dizaino analize
- [x] surašyti HTML
- [x] išsikirpti nuotraukas ir jas panaudoti:
    - panaudoti reliatyvų kelią
- [ ] atskiri puslapiai, kuriuose naviguojama "ratu"
    - Sign up
    - Sign in
    - Fprgot password
- [ ] aprašome stilių:
    - turinys turi būti ekrano centre (tiek horizontaliai, tiek vertinkaliai)
    - turinys bus fiksuoto pločio (pikseliais)
- [ ] stilių failas vienas, jame stilius pritaikytas visiems puslapiams

# Pozicionavimas 
1. Vaikui duodam 'position: absolute'
2. Artimiausiam tėvui (kuriam norime turėti atskaitos tašką) suteikiame: 
a)"position: relative", jeigu tas elementas neturi kitokių "posiotion" savybių;
b) paliekame tokią "position" savybę kokią turėjo tas elementas, jei nurodytas elementas ją jau turi.

Išvada: 
absoliučiai pozicijonuojmas elementas. 

# Apie pločius ir aukščius
Jeigu yra komandos width arba height, tai lygiavimo komandos top ir bottom, left ir right įgyją pirmumo teises. Paeksperimentuokite su width arba height komandomis ir lygiavimu.

# Patarimai

/* .pomidoras {
    background-color: red;
    padding: 20px;
    font-size: 16 px;
} 
    šią savybę galima pritaikyti daugeliui elementų naudojant klases*/
    
/* .form.form{} peržiūrėti CSS selektorius
# kalba apie atributą ID. Patarimas nerašyti, nes ta taisyklė labai griežta. Naudoti patariama tik pačiame HTML arba JavaScript.

body, body * tai reiškia, kad ima visus body elementus{ 
    margin: 0;
    padding: 0;
    vertical-align: top;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;    
    box-sizing: border-box;
} 
 absoliutus centriukas
{Position: absolute;
Top: 50%;
Left: 50%;
Transform, translate (-50% ; -50%) }

*/

Nuoroda į blur komandą naudojamą CSS
https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/blur
Išbandyti filtrų savybes
https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter

Can I use 
https://caniuse.com/

Formos stilius perkiale į kitą css failą ir kitam projektui galime drąsiai naudoti, taip sutaupysime laiko.

