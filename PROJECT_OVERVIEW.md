# AskTimmy

## Doel

Een lokale helpdesk waarmee gebruikers veelvoorkomende computerproblemen zelf kunnen oplossen, ook als de wifi uitvalt. De interactieve AskTimmy-pdf dient als inhoudelijk vertrekpunt.

## Doelgroep

Gebruikers van geselecteerde Windows-laptops die via Intune worden beheerd, en de beheerder die de helpdesk inhoudelijk bijwerkt. We gaan ervan uit dat gebruikers doorgaans lokale beheerdersrechten hebben op hun laptop.

## Eerste versie

- Kies een onderwerp via pictogrammen voor beamerverbindingen, wifi, audio en veelvoorkomende problemen.
- Typ een vraag in de zoekbalk om passende stappenplannen te vinden.
- Voeg als beheerder oplossingen toe en werk bestaande stappenplannen bij.
- Gebruik de knop **Wifi opnieuw inschakelen** om de wifi-adapter kort uit en daarna weer in te schakelen. Windows kan om bevestiging vragen. Als de actie mislukt, toont AskTimmy een handmatig stappenplan.

## Nog niet

- Een chat die vervolgvragen stelt.
- Automatische synchronisatie van inhoud tussen laptops.

## Platform

Een lokale Windows-app die ook zonder internet werkt.

## Frameworks en bouwstenen

.NET 10 met WPF, een basis voor Windows-apps die goed aansluit op Windows-instellingen en lokale herstelacties.

## Opslag

Bewaar de oplossingen in een lokaal bestand dat met de app meegeleverd wordt. De beheerder werkt de inhoud bij op de beheerderslaptop en neemt die mee in een volgende versie. Zoekvragen worden niet opgeslagen. Neem geen persoonsgegevens op in de oplossingen.

## Vormgeving

Gebruikt het design system in `design-system/`. De vormgeving kan later worden aangepast.

## Eisen

- De wifi-adapter mag niet worden verwijderd. Enkel uit- en inschakelen.

## Publicatie

Verspreid nieuwe versies van de app en de bijbehorende oplossingen met Intune naar geselecteerde laptops. Gebruik het versiebeheer in Intune voor updates.
