# Scriptura Digitală

Platformă web interactivă și educațională dedicată studierii, analizării și explorării geografice a textului biblic. Proiect realizat pentru Olimpiada Națională de Inovare și Creație Digitală InfoEducație 2026 (Secțiunea Web, Județul Dâmbovița).

## Link-uri Utile

- Live Demo (Homepage): https://davidadrian1092-pixel.github.io/Scriptura-Digital-/
- Repozitoriu GitHub: https://github.com/davidadrian1092-pixel/Scriptura-Digital-
- Pagina Proiectului pe Forumul InfoEducație: https://community.infoeducatie.ro/t/scriptura-digitala-web-dambovita-lucrari-2026-nationala/6483

---

## Ghid de Utilizare (Cum se folosește aplicația)

Aplicația este concepută pentru a fi intuitivă și ușor de navigat. Iată cum poți explora toate modulul disponibile:

### 1. Lectura și Navigarea Textului Biblic
- Selectarea cărților și capitolelor: Folosește meniul de navigare pentru a alege rapid cartea și capitolul dorit.
- Evidențiere versete: Dă click pe un verset pentru a-l marca temporar și pentru a facilita citirea sau compararea.
- Derulare fluidă: Paginarea se face automat, cu derulare lină la schimbarea capitolului.

### 2. Harta Interactivă Istorică
- Explorare geografică: Mergi la secțiunea Harta Istorică pentru a vedea locațiile și regiunile menționate în textele biblice.
- Schimbare trasee: Apasă pe butoanele dedicate pentru a încărca traseele specifice (Traseul lui Iisus, Drumul lui Moise, Viața lui Samson, Drumul Fecioarei Maria).
- Traseele Apostolilor: Deschide submeniul „Trasee Apostoli” pentru a selecta drumurile parcurse de Sfântul Andrei, Sfântul Petru sau alți apostoli.
- Ecran complet: Apasă butonul „Fullscreen Hartă” pentru a mări harta pe tot ecranul pentru o analiză mai detaliată.

### 3. Modulul Quiz (Test de Cunoștințe)
- Alegerea nivelului: Selectează nivelul de dificultate dorit (Ușor, Mediu sau Greu).
- Răspuns la întrebări: Alege varianta pe care o consideri corectă. Aplicația oferă feedback vizual imediat.
- Calcul punctaj: La finalul testului vei primi scorul obținut și posibilitatea de a relua testul cu întrebări generate dinamic.

### 4. Accesibilitate și Muzică de Fundal
- Dimensiune text: Ajustează mărimea fontului din controalele de accesibilitate pentru o citire comodă.
- Redare vocală (Text-to-Speech): Activează citirea automată a textului prin intermediul sintezei vocale din browser.
- Player audio ambiental: Din bara audio, alege o melodie bisericească/ambientală din listă, apasă Play și ajustează volumul după preferințe.

### 5. Schimbarea Limbii
- În partea de sus a paginii ai la dispoziție selectorul de limbi (RO, EN, FR, DE, ES, JA, AR). Un simplu click pe limba dorită va traduce conținutul interfeței.

---

## Funcționalități Principale

- Interfață complet responsive, optimizată pentru calculator, tabletă și telefon.
- Încărcare rapidă a datelor fără reîncărcarea paginii (Single Page Application în Vanilla JS).
- Hartă interactivă dezvoltată cu Leaflet.js și straturi OpenStreetMap.
- Modul de evaluare a cunoștințelor cu întrebări dinamice și sistem de scor.
- Suport de accesibilitate (modificare text, lectură vocală nativă, ambianță audio).
- Script Python propriu de conversie a datelor biblice din XML (USFX) în format JSON.

---

## Tehnologii Utilizate

- Frontend: HTML5 semantic, CSS3 (variabile native, flexbox/grid), Vanilla JavaScript (ES6+)
- Data Processing: Python 3 (scriptul convert.py)
- Biblioteci & API-uri: Leaflet.js, OpenStreetMap, Web Speech API, Google Translate Widget
- Deployment: GitHub Pages integrat cu GitHub Actions Workflow

---

## Instalare și Rulare Locală (Git Bash)

Dacă vrei să clonezi și să rulezi proiectul pe calculatorul tău:

1. Deschide Git Bash și clonează repozitoriul:
   git clone https://github.com/davidadrian1092-pixel/Scriptura-Digital-.git

2. Intră în folderul proiectului:
   cd Scriptura-Digital-

3. Deschide aplicația:
   Deschide fișierul index.html în browserul tău sau folosește extensia Live Server din VS Code.

4. (Opțional) Rularea scriptului de conversie date:
   Dacă modifici sursa XML a Bibliei, rulează în terminal:
   python convert.py

---

## Structura Fișierelor

- index.html - Pagina principală a aplicației
- style.css - Stilurile vizuale și regulile de design responsive
- app.js - Logica aplicației (navigare, hartă, quiz, audio, accesibilitate)
- convert.py - Scriptul Python propriu pentru conversia datelor XML în JSON
- .github/workflows/ - Workflow-ul de automatizare pentru GitHub Pages

---

## Declararea Originalității și Drepturi de Autor

Conform regulamentului oficial al concursului InfoEducație:
- Structura HTML, stilizarea CSS, logica JavaScript (app.js), modulul de Quiz și scriptul Python de conversie (convert.py) sunt concepute și scrise integral de autor.
- Textul biblic și resursele audio de fundal utilizate aparțin Domeniului Public (Public Domain).
- Librăriile externe (Leaflet.js) și serviciile terțe sunt resurse open-source integrate în aplicație.

Autor: David Cernovodeanu
