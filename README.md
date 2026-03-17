# Educational Game - Sustainable Future for All in Europe

Acest proiect este un joc 2D interactiv și educațional dezvoltat în C++ folosind framework-ul [Raylib](https://www.raylib.com/). A fost creat în cadrul proiectului internațional **"Gender, Digitalization, Green - Ensuring a Sustainable Future for all in Europe"** (Cod referință: 2023-1-RO01-KA220-HED-000154433).

## Descrierea Jocului
Scopul jocului este de a educa utilizatorii despre sustenabilitate, schimbări climatice, energii regenerabile și legislația de mediu a Uniunii Europene, printr-o experiență interactivă sub formă de labirint.

Jucătorul controlează un personaj care explorează harta, adună comori, luptă cu inamici și rezolvă chestionare pentru a progresa. 

## Funcționalități
- **Explorare și Colectare:** Navighează harta și adună pietre prețioase pentru a câștiga puncte adiționale.
- **Sistem de Misiuni (Quests):** Interacționează cu NPC-urile pentru a primi misiuni (ex. învingerea unui număr de inamici sau colectarea unui anumit număr de rubine) care te recompensează cu monede și puncte.
- **Sistem de Chestionare (Trivia):** Ajngând în zonele semnalizate cu `?`, vei primi întrebări grilă cu tematică verde (ecologie). Răspunsurile corecte îți aduc monede și puncte, în timp ce răspunsurile greșite te penalizează cu scor și viață (HP).
- **Combat:** Inamici de diverse tipuri se plimbă pe hartă. Jucătorul se poate apăra trăgând cu proiectile.

## Controale
* **Săgeți Direcționale (Sus/Jos/Stânga/Dreapta):** Deplasare personaj
* **Space:** Trage (proiectil) 
* **E:** Interacțiune cu NPC / Preluare & finalizare misiune
* **Enter:** Confirmare răspuns în cadrul unui chestionar
* **C:** Afișează/Ascunde răspunsul corect la întrebări
* **P:** Pauză
* **Sus/Jos:** Scroll în paginile de meniu și pentru selectarea răspunsului

## Credite
Acest proiect implică un parteneriat între mai multe universități:
* Universitatea de Științe Agricole și Medicină Veterinară (București, România)
* Universitatea Națională de Știință și Tehnologie POLITEHNICA (București, România)
* Universitat Autonoma de Barcelona (Spania)
* Universidade do Porto (Portugalia)
* Uzhgorodskyi Nacionalnyi Universitet (Ucraina)

**Realizat de studenții:**
Voicu Alexandru, Duță George, Halca Anna, Marinescu Doru, Oprea Ioana Antonia.

**Profesori coordonatori:** 
Mihai Caramihai, Daniel Chiș.

## Cum se rulează?
(Proiectul include un executabil deja compilat pentru Windows, plus biblioteca dinamică necesară).
1. Fiind în folderul principal, dublu-click pe `joc.exe`.
2. Asigurați-vă că aveți fișierul `raylib.dll` și folderul `resources/` în același director cu executabilul.

Se poate recompila sursa `joc.cpp` folosind compiler-ul *g++ MinGW* vizând biblioteca *Raylib*.
