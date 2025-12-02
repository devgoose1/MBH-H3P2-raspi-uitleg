Welkom bij de uitleg voor de basics van de Raspberry Pi. Hier staat (bijna) alles wat je nodig hebt om te beginnen!



# Voorbereiding
Voordat je kan beginnen moet je een paar dingen klaarzetten. Je kan de Raspberry Pi niet gebruiken op je laptop, want het is een soort van mini computer.

**1. Wat heb je nodig**
- Een monitor
- Een lader voor de Raspberry Pi
- Een toetsenbord
- Een muis

**2. Alles verbinden**
1. Stop de lader in een stopcontact en in de Raspberry Pi
2. Verbind de monitor aan de Raspberry Pi
3. Verbind het toetsenbord en de muis aan de Raspberry Pi door ze in de USB poorten te stoppen

**3. Inloggen**
Je bent nu klaar om te beginnen! Als het goed is heb je toen de de lader en monitor verbond op de monitor wat code automatisch zien draaien. Dit start het systeem op.

Als het goed is, zie je nu een scherm om in te loggen. Dit is een wit menu waar je `username: leerling` is. Je wachtwoord staat op je Raspberry Pi. Log in en laat de systemen opstarten.

# De raspberry pi  gebruiken
Lekker bezig!  Je bent nu ingelogd en ziet een standaard startscherm. Iedere Raspberry Pi heeft als het goed is standaard een *browser en console* erbij gekregen. Ook is het handig om even te checken of je wifi hebt. Dit doe je door rechtsboven in je scherm te kijken. Als je wifi hebt, zie je een blauw wifi icoontje. Als je dat niet hebt, zie je een witte monitor met een rode X erbij. Als dat zo is, ga dan even naar een docent. Die kan je verder helpen.

**Eerste dingen om te doen**
1. Ga naar de *console*. Dit kan je doen door `ctrl + alt + t` te klikken. Dat opent de console.
2. Typ `sudo apt update` en daarna `sudo apt upgrade`. Dit update je systeem. Doe dit ook altijd als je een nieuw programma of library installeert.

**Handige commands**
- `ls`: laat de inhoud van een map zien
- `cd <mapnaam>`: ga naar de map die je hebt aangegeven (BELANGRIJK: geen <> bij de command gebruiken. Die staan er hier alleen bij om als voorbeeld te gebruiken)
- `cd ..`: Ga 1 map terug. Dus als je in `mapnaam/mapnaam2` zit, ga je nu naar `mapnaam`
- `cd ../..`: Ga 2 mappen terug (meer ../ doet meer mappen terug)
- `mkdir <mapnaam>`: Maakt een nieuwe map aan
- `nano <bestandnaam>`: Gebruik dit om in een bestand tekst en code te schrijven

# Mogelijkheden van de Raspberry Pi
Heel simpel gezegd: Bijna oneindig! Je kan er superveel mee! Sensoren, lampjes, knoppen, software, etc. Het is eigenlijk een Arduino met meer mogelijkheden.


# Handig om te doen:
Maak een github repository aan en upload aan het einde van de les al je code naar Github. Github slaat automatisch alle versies van je bestanden op en je kan altijd terug naar oudere versies. Dus als je in een les vastloopt en je code werkt niet meer, dan kan je altijd terug naar een werkende versie. Dit is zeer aan te raden. Dit is compleet gratis en heel makkelijk te doen!
