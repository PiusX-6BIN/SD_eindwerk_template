# [PROJECTNAAM]

> stappenplan:
> - [ ] **Gebruik Markdown** om het designdocument in te vullen.
> - [ ] **Vul de titel in** (bovenaan) met de naam van je project.
> - [ ] **1. BESCHRIJVING: Schrijf een tekst** waarin je je project zo volledig mogelijk beschrijft.
> - [ ] **2. SCENARIO: Lijst de stappen op** die een gebruiker doorloopt tijdens een normaal gebruik van je programma (als er meerdere scenario's mogelijk zijn, beschrijf je het meest gebruikte).
> - [ ] **3. ONTWERP: Teken** alle verschillende schermen die een gebruiker kan tegenkomen. Deze tekening mag een versimpelde versie van je applicatie zijn.
> - [ ] **4.1. PLANNING: Lijst de taken op** die je moet uitvoeren om je project te maken. Geef bij elke taak aan welke delen ervan _moeten_ gebeuren en welke _optioneel_ zijn.
> - [ ] **4.2. PLANNING: Werk een planning uit**, waarin je probeert in te schatten wanneer je welke taak zult uitvoeren.
> - [ ] **4.3. PLANNING: Stel (minstens) 3 deadlines op**, waartegen je _zeker_ bepaalde taken hebt uitgevoerd. De 3e deadline valt sowieso op 25 mei, op deze datum is je applicatie volledig klaar. Je mag dit verwerken in de planning uit de vorige stap.
> - [ ] **Verwijder de voorbeelden** hieronder wanneer je ze niet meer nodig hebt.

## BESCHRIJVING

> voorbeeld: 
> 
> Ik bouw een tutorial-website waarop ik verschillende games maak met p5.js en uitleg hoe ik ze heb gemaakt, stap voor stap. Elk spel kan je ook spelen op de pagina van het spel. Gebruikers kunnen een account aanmaken om commentaar te geven of vragen te stellen bij elke tutorial.
> 
> De gebruikers en wachtwoorden worden, samen met de commentaren, opgeslagen in een mySQL database. De overige inhoud maak ik rechtstreeks aan met HTML. De spellen worden gemaakt in Javascript met p5.js. De bedoeling is om minstens 3 spellen te hebben aan het einde van dit project.

## SCENARIO

> voorbeeld: 
> 
> 1. Een gebruiker (A) surft naar de website.
> 2. De hoofdpagina wordt getoond aan (A).
> 3. (A) drukt op de knop `'LOG IN'`.
> 4. De website toont een login-formulier.
> 5. (A) vult zijn gegevens in en logt in.
> 6. De hoofdpagina wordt opnieuw getoond. De knop `'LOG IN'` is vervangen door een account-knop.
> 7. (A) gebruikt de menu om naar een tutorial-pagina te surfen.
> 8. De tutorialpagina wordt getoond. Hier ziet (A) het spel, de instructies om het spel te spelen, een uitleg over hoe het spel gemaakt werd en een commentaar-gedeelte.
> 9. (A) test het spel uit.
> 10. (A) scrollt naar het commentaar-gedeelte en vult een vraag in.
> 11. De vraag wordt opgeslagen in de database en gelinkt aan de account van (A) en de juiste pagina.
> 12. De pagina wordt opnieuw geladen, en de vraag wordt getoond in het commentaar-gedeelte. Het commentaar-gedeelte is gesorteerd van nieuw naar oud.

## ONTWERP

## PLANNING

> voorbeeld: 
> 
> Takenlijst:
> 1. Games:
>    - spel 1 ontwerpen
>    - spel 1 uitwerken
>    - spel 2 ontwerpen
>    - spel 2 uitwerken
>    - spel 3 ontwerpen
>    - spel 3 uitwerken
> 2. Database:
>    - database ontwerpen voor: gebruikers, wachtwoorden en commentaren
>    - ontwerp normaliseren
>    - database implementeren in PHPMyAdmin
> 2. Website:
>    - website ontwerpen
>    - HTML uitwerken voor hoofdpagina en tutorialpagina
>    - Voorbeeld-commentaren toevoegen in HTML
>    - CSS uitwerken voor hoofdpagina en tutorialpagina
>    - Login-popup maken
>    - Login-formulier in login-popup maken
>    - Login-formulier laten werken met PHP
>    - Voorbeeld-commentaren vervangen door commentaren uit database met PHP
>    - Commentaar-formulier toevoegen
>    - Commentaar-formulier laten werken met PHP
> 
> Planning:
> 1. DEADLINE 1 (**30 maart**)
>    - spel 1 uitdenken (tekenen en uitschrijven)
>    - website ontwerpen (tekenen)
>    - tutorialpagina voor spel 1 uitwerken (html + css) met voorbeeld-commentaren en placeholders
>    - spel 1 uitwerken en op eigen tutorial-pagina plaatsen
> 2. DEADLINE 2 (**27 april**)
>    - database ontwerpen en normaliseren
>    - database implementeren en vullen met voorbeeld-populatie
>    - commentaren laden op tutorialpagina van spel 1
>    - hoofdpagina uitwerken (html + css)
>    - login-formulier maken (html + css) en laten werken
> 3. DEADLINE 3 (**25 mei**)
>    - commentaar-formulier maken en laten werken
>    - spel 2 uitdenken en uitwerken
>    - tutorialpagina voor spel 2 uitwerken