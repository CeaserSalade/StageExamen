# Debriefing

## Projectoverzicht
Doel van de opdracht: Het doel van dit project is het ontwikkelen van een interactieve widget waarmee klanten eenvoudig kunnen berekenen hoeveel serviceminuten zij nodig hebben voor specifieke diensten. 
De applicatie biedt een overzicht van alle beschikbare diensten, toont de kosten in serviceminuten, en laat klanten diensten selecteren binnen vooraf ingestelde limieten. De berekening wordt realtime weergegeven en kan worden verzonden naar een webhook voor integratie met externe systemen.

## Taken

## Overzicht van alle beschikbare diensten met kosten in serviceminuten.
### Ontwikkel een interface die een lijst toont van alle beschikbare diensten met bijbehorende serviceminuten.

* De widget toont alle diensten uit de gekoppelde collectie.

* Elke dienst wordt weergegeven met een naam en het aantal serviceminuten.

## Mogelijkheid om diensten te filteren op vooraf gedefinieerde categorieën.
### Voeg een filterfunctie toe waarmee gebruikers diensten kunnen filteren op categorieën.

* Er is een dropdown- of knoppenmenu waarmee gebruikers kunnen filteren.

* Alleen diensten van de geselecteerde categorie worden weergegeven.

## Mogelijkheid om per dienst een maximumaantal afnames te definiëren.
### Voeg een invoerveld of selectiemenu toe waarmee gebruikers het aantal afnames per dienst kunnen instellen (tot een maximumwaarde).

* Gebruikers kunnen het aantal afnames per dienst aanpassen.

* De widget voorkomt dat gebruikers meer dan het maximum selecteren.

## Dynamische berekening van het totaal aantal geselecteerde serviceminuten.
### Implementeer een rekenfunctie die het totaal aantal serviceminuten bijwerkt op basis van de gekozen diensten en aantallen.

* De berekening wordt direct bijgewerkt bij wijzigingen in de selectie.

* De weergegeven totaalwaarde is correct.

## Weergave van het totaal aantal geselecteerde serviceminuten op de interface.
### Toon het totaal aantal serviceminuten onderin, net boven de knop om het te bevestigen.

* De totaalwaarde is zichtbaar en duidelijk leesbaar.

## Bevestigingsknop waarmee het totaal verzonden kan worden naar een webhook.
### Voeg een knop toe waarmee de geselecteerde diensten en het totaal aantal serviceminuten naar een webhook worden verzonden.

* Er is een configureerbare knop onderin toe.

* Bij klikken wordt de data met javascript een POST request verzonden naar de webhook.

* Configureerbare webhook.

## Intuïtieve en responsieve gebruikersinterface geschikt voor desktop en mobiel.
### Ontwikkel een gebruiksvriendelijke en responsive interface.

* De widget werkt goed op desktop, tablet en telefoon schermformaten.

* Een gebruiker moet binnen maximaal 3 klikken een dienst kunnen selecteren en het aantal kunnen instellen.

* 80% van de testgebruikers moet de widget kunnen gebruiken zoals deze bedoeld is zonder extra uitleg.

* De widget moet binnen 500ms reageren op interacties (zoals klikken, invoer, filteren).

## Diensten worden beheerd in een collectie en de widget is daaraan gekoppeld.
### Zorg ervoor dat de widget de diensten ophaalt uit een vooraf gedefinieerde collectie.

* De widget laadt de juiste diensten uit de gekoppelde collectie.

## Doelgroep
De klanten van GraagGoedOnline.nl B.V.
