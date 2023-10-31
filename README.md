# Personal Command Guide
Door middel van deze Command Guide ga je kennis maken met de terminal van Linux. Voer alle gevraagde activiteiten uit en maak je eigen Personal Command Guide.

## Je eigen repository
Maak een eigen account aan op de website github.com. Github kun je als IT-er gebruiken om de bestanden van je eigen projecten te beheren en samen te werken met anderen.

Voer het onderstaande stappenplan uit om je eigen repository (bibliotheek) aan te maken in Github. Je kopieert deze repository en maakt hier je eigen bibliotheek van.

### Stap #1
1. Maak een eigen account aan op Github.com.
2. Installeer Gitbash op je eigen laptop.
3. Installeer Github Desktop op je eigen laptop.
4. Installeer Visual Studio Code op je eigen laptop.
5. Clone deze [repository (markdackus247/personalcommandguide)](https://github.com/markdackus247/personalcommandguide.git) naar je eigen account. 
6. Gebruik Github Desktop om de repository naar je eigen laptop te kopieren.
7. Open in Visual Studio Code de folder waarin de repository staat.

### Stap #2
Om deze Persoonlijke Command Guide te kunnen maken heb je twee virtuele machines nodig.
1. Installeer een eigen (virtuele) Ubuntu Desktop computer.
2. Installeer een eigen (virtuele) Ubuntu Live Server.
3. Installeer een virtuele PFsense router in VirtualBox. Voorzie de PFsense router van twee netwerkkaarten. 1ste Netwerkkaart moet op NAT staan. 2de netwerkkaart moet op intern "linuxcmd" staan.
4. Zorg ervoor dat alle virtuele machines zijn verbonden met het interne netwerk "linuxcmd".

### Stap 3
Doorloop alle onderdelen van de persoonlijke command guide. Geef steeds toelichting bij alle commando's. Werk in je eigen Github repository.

Hieronder staan de onderdelen van de command guide.
1. [Software installeren](pcm/1.%20Software.md)
2. [Mappen](pcm/2.%20Mappen.md)
3. [Bestanden](pcm/3.%20Bestanden.md)
4. [Tekstbestanden](pcm/4.%20Tekstbestanden.md)
5. [Gebruikers](pcm/5.%20Gebruikers.md)
6. [Datum en tijd](pcm/6.%20Datum%20en%20tijd.md) 
7. [Bash](pcm/7.%20Bash.md)
8. [Zoeken](pcm/8.%20Zoeken.md)
9. [Process](pcm/9.%20Processen.md)
10. [Permissions](pcm/10.%20Permissions.md)
11. [Pipes](pcm/11.%20Pipes.md)

### Stap 4
Mini Challenge: Maak een goede filestructuur voor de [bestanden van de gebruiker John Doe](/Documents/John%20Doe/). Maak hiervoor eerst de gebruiker John Doe aan op de Ubuntu Server.
