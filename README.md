[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/nAvSA6dS)
# PE8 - Foutopsporing
## Intro
Een lokale pizzazaak liet onlangs een applicatie ontwikkelen waarbij klanten (gebruikers) zelf hun pizza kunnen bestellen. De applicatie werd opgeleverd maar bij de eerste ingebruikname werden nog enkele problemen vastgesteld.
Aan jou de taak om de applicatie te verbeteren door onderstaande fouten op te lossen.

## Opdracht
Maak een lokale clone van deze repository, los de bugs in de juiste volgorde op en zorg voor een ***commit bij elke bugfix***. Gebruik hiervoor het ID als commit-message. Vergeet het eindresultaat niet te ***pushen*** voor de deadline verstreken is!

___
> Tip: **Gebruik breakpoints en de debugging tools van Visual Studio om de fouten op te sporen!**
___

## Bugreport

| ID | Omschrijving |
| -- | ------------ |
| BUG-01  | Bij het selecteren van een ongeldige actie sluit de applicatie af. |
| BUG-02  | Wanneer de actie "n", "a" wordt ingegeven, wordt de applicatie afgesloten. |
| BUG-03  | Het formaat van een telefoonnummer wordt altijd als foutief getoond | 
| BUG-04  | Ondanks de foutmelding "Telefoonnummer moet in het formaat 0000/00.00.00" kan de gebruiker daarna wel gewoon een leverdatum ingeven |
| BUG-05  | Bij ingave van een foutieve leverdatum/tijd (bv 31-04-1995 12u30) crasht de applicatie, zorg voor een correcte validatie. |
| BUG-06  | De validatie van de leverdatum/tijd werkt niet correct, ook geldige tijdstippen worden als foutief aangeduid |
| BUG-07  | Ondank dat een leverdatum/tijd niet als geldig wordt beschouwd gaat de applicatie toch verder naar de volgende stap. |
| BUG-08  | Er kunnen oneindig veel pizza's ingegeven worden, dit terwijl op voorhand een aantal gevraagd wordt |
| BUG-09  | De toets 'E' voegt geen extra topping toe, deze functie moet hoofdletter onafhankelijk zijn. |
| BUG-10  | De leverdatum/tijd wordt foutief weergegeven in het overzicht. |
| BUG-11  | Het totaalbedrag van een order moet als munteenheid worden weergegeven met een correcte afronding |
| BUG-12  | Nadat de samenvatting van het order getoond kan er enkel met de enter-toets worden verder gegaan, dit zou ook met alle andere toetsen moeten werken. |
| BUG-13  | Nadat een bestelling voltooid wordt zou het hoofdmenu opnieuw getoond moeten worden. |


![bugs](media/bug3-6-7.png)
![bugs](media/bug4-5.png)
![bugs](media/bug8.png)
![bugs](media/bug10-11-12.png)
