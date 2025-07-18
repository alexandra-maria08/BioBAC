<p align="center">
  <img src="downloads/biobac3.png" width="400" />
  <img src="downloads/biobac2.png" width="400" />
  <img src="downloads/biobac1.png" width="400" /><br>
  <img src="downloads/2.png" width="400" />
  <img src="downloads/1.png" width="400" />
</p>

---

# Documentație – Proiect BioBAC

## 1. Titlu și autori

**Titlu:** BioBAC – Platformă interactivă pentru pregătirea examenului de bacalaureat la biologie  
**Autori:** NICOLAE MARIA ALEXANDRA și GHIGA MARIA ALEXANDRA – clasa a 9-a B, profesor coordonator MITRACHE CLAUDIA.

## 2. Argumentul proiectului

Elevii care se pregătesc pentru bacalaureat la biologie întâmpină dificultăți în găsirea unor resurse clare, interactive, sintetizate și mobile. BioBAC oferă o soluție prietenoasă, structurată, accesibilă gratuit și adaptată nevoilor reale ale liceenilor.

## 3. Descriere generală și utilitate educațională

BioBAC este o aplicație educațională interactivă, concepută special pentru elevii care se pregătesc pentru Bacalaureatul la biologie. Platforma oferă lecții sintetizate, exerciții variate (grile, completări, asocieri), feedback vizual și instant, precum și un sistem de gamificare cu XP, niveluri și bară de progres.

Aplicația poate fi instalată pe telefon ca Progressive Web App (PWA) și funcționează offline pentru majoritatea funcțiilor, contul fiind necesar doar pentru salvarea progresului. Oferă traducere rapidă prin Google Translate, temă dark activabilă automat și un server Discord integrat, unde elevii pot accesa materiale suplimentare, resurse teoretice și discuții utile.

BioBAC poate fi folosită atât pentru învățarea individuală, cât și în clasă, oferind o experiență educațională modernă, accesibilă și motivantă.

## 4. Arhitectura aplicației

BioBAC este o aplicație educațională dezvoltată în HTML, CSS și JavaScript. Fiecare lecție și test este organizat într-o pagină HTML separată, cu un meniu principal accesibil din orice secțiune. Aplicația include:

- Lecții interactive cu teorie și exact 9 itemi fixați (grilă, completare, asociere), integrați cu gamificare (XP, niveluri, scor final), feedback instant și Text-to-Speech. În viitor, itemii pot deveni aleatori.
- Buton Google Translate în colțul din dreapta sus pentru traducere rapidă.
- Temă dark activată automat pe baza preferinței salvate în localStorage.
- Gamificare completă, cu XP, niveluri și bară de progres vizuală pentru fiecare lecție.
- Pagină de cont unde utilizatorul poate: vizualiza și modifica datele personale (nume, email, parola), totul fiind salvat și sincronizat în Firebase Firestore, modifica tema, să se deconecteze, să își șteargă contul.
- Integrare Firebase pentru stocarea sigură a datelor în cloud.
- PWA (Progressive Web App) cu suport pentru funcționare offline și instalare pe telefon.
- Design responsive, optimizat pentru desktop și mobil.
- Compatibilitate deplină cu browsere moderne.

În plus, aplicația este conectată la un server de Discord dedicat comunității BioBAC, unde sunt disponibile materiale de învățat, inclusiv:

- explicații teoretice suplimentare,
- linkuri utile,
- suport din partea echipei,
- socializare între elevi.

Aplicația este gândită pentru utilizare atât individuală, cât și la clasă, oferind o experiență completă, motivantă și ușor de accesat.

## 5. Tehnologii folosite

- HTML5, CSS3, JavaScript – limbaje de bază folosite pentru structură, stil și funcționalitate.
- Firebase Firestore – bază de date NoSQL utilizată pentru stocarea datelor despre conturi, progres, XP, nivel și preferințe ale utilizatorilor.
- Netlify – platformă de găzduire folosită pentru publicarea aplicației și generarea unui link accesibil online.
- Service Worker + Web App Manifest – pentru integrarea funcționalității PWA (Progressive Web App), ce permite instalarea aplicației pe telefon și rularea offline.
- Text-to-Speech Web API – pentru redarea audio a explicațiilor, sprijinind învățarea auditivă.
- Google Translate API – integrat simplu în interfață, permite traducerea automată a lecțiilor în mai multe limbi.
- Gamificare – sistem de puncte, XP și niveluri, integrat pentru a motiva elevii să continue învățarea.
- Animații CSS și JavaScript (Framer Motion / tranziții personalizate) – pentru un aspect modern și o experiență interactivă mai fluidă.
- Discord – spațiu de colaborare educațională, unde sunt postate materiale teoretice, întrebări, joculețe educaționale (de pe platforme precum Wordwall), și se menține legătura cu comunitatea de utilizatori.

## 6. Conținut și interactivitate

Lecțiile sunt clare, structurate pe idei esențiale, ușor de parcurs atât individual, cât și la clasă. Fiecare lecție include exact 9 itemi interactivi (grile, completări, asocieri), concepuți conform modelelor oficiale de Bacalaureat. Utilizatorul primește feedback imediat după fiecare răspuns, iar sistemul de punctaj motivează progresul.

Sistemul de gamificare este disponibil printr-un buton dedicat în sidebar, unde utilizatorii pot vedea XP-ul acumulat, nivelurile și alte elemente de progres.

## 7. Utilizarea inteligenței artificiale

Proiectul a fost realizat în colaborare cu un asistent AI care a sugerat cod, structură HTML/CSS, formulări de itemi. Toate propunerile au fost analizate, testate, adaptate și integrate conștient de autori.

## 8. Posibilități de dezvoltare

- Itemi aleatorii la fiecare accesare, pentru a evita învățarea mecanică și a crește varietatea exercițiilor.
- Feedback adaptiv: integrarea unui sistem care să analizeze răspunsurile elevului și să recomande automat lecții, exerciții sau explicații suplimentare în funcție de greșelile frecvente.
- Testare simulată cu cronometru & generare de subiecte unice: un modul care creează automat teste de bac pe bază de itemi aleatorii, cu posibilitatea de a simula condițiile reale de examen.
- Clasament național BioBAC: elevii cu cont pot concura în clasamente săptămânale sau lunare pe XP, stimulând învățarea prin gamificare.

## 9. Integrarea ca aplicație PWA

BioBAC este acum instalabil pe telefon ca aplicație reală (PWA): cu iconiță personalizată, funcționare offline, splash screen și experiență fullscreen. Elevii o pot accesa instant de pe net sau instala permanent.

## 10. Iconiță personalizată și branding

Am creat o iconiță care combină simboluri din biologie vegetală, animală și anatomie pentru a evidenția că BioBAC acoperă ambele secțiuni ale bacului.

## 11. Distribuție și accesibilitate

Elevii pot accesa BioBAC:
- Online: https://biobac.netlify.app
- Instalabil: aplicație PWA direct din browser

## 12. Concluzii

BioBAC este un proiect educațional modern, util și aplicabil imediat în licee. Demonstrează că tehnologia, pasiunea și colaborarea pot crea resurse reale pentru succesul la examen.

## 14. Bibliografie / Resurse consultate

- https://profesorjitaruionel.com  
- Manuale clasa IX-XII (Corint, Art)  
- https://developer.mozilla.org  
- Asistent AI  
- https://subiecte.edu.ro  
- https://wordwall.net/  
- https://kahoot.it/  
- https://digitaledu.ro/resurse-educationale-deschise/?_sfm_discipline=Biologie&_sfm_limba=Rom%C3%A2n%C4%83
