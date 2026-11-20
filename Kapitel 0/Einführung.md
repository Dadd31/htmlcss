## Aufgabe 1

Ich denke, dass mein Browser die Domain bei einem DNS-Server erfragt, um die IP-Adresse der Seite zu bekommen, und sich danach über HTTPS verbindet.

**1. `http://www.beispiel.de/bilder/tux.png`**

- Protokoll: `http`
- Domain-Name: `www.beispiel.de`
- Pfad: `/bilder/tux.png`

**2. `https://www.w3.org/standards/`**

- Protokoll: `https`
- Domain-Name: `www.w3.org`
- Pfad: `/standards/`

**3. `https://wiki.selfhtml.org/wiki/HTML`**

- Protokoll: `https`
- Domain-Name: `wiki.selfhtml.org`
- Pfad: `/wiki/HTML`

## Aufgabe 3

Bei `nslookup www.example.com` und `nslookup example.com` werden verschiedene Adressen aufgelistet.

## Aufgabe 4

Ich gebe `https://www.gymnasium-hueckelhoven.de` ein. Anders als in Aufgabe 1 gedacht, verbindet sich der Browser nicht gleich mit der IP, weil er sie noch nicht kennt. Zuerst fragt er das DNS, das ist wie ein Telefonbuch, und bekommt die IP-Adresse. Dann schickt er seine Anfrage an den Server, verschlüsselt durch HTTPS, also sicherer als HTTP. Der Server schickt die Datei zurück und der Browser baut die Seite auf. Fehlende Bilder und Stylesheets fordert er extra nach.