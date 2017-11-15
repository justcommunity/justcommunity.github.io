---
layout: default
title: Sprecherprofil
description: ka.

permalink: SpeakerProfile.html
---

# {{ page.title }}

Speakerprofile werden in GitHub in MarkDown-Dateien erfasst. Jeder Speaker bekommt die Chance sein Profil selber zu bearbeiten. Das funktioniert, in die jewelige Datei bearbeitet und ein Pull-Request für die Änderung erstellt wird. Das JustCommunity e.V. Team wird die Änderungen prüfen und ggf. mergen.  

## Aufbau

Eine Markdown Datei für das Speakerprofil entspicht folgendem Aufbau:

~~~ markdown
---
layout: default
title: "Voller Name des Sprechers"
date: 2017-12-01 08:30:00 +0100
topics: "Themen Liste, Getrennt, nach Komma"
categories: Speaker
---

# {{ page.title }}

**Themen:** {{ page.topics }}

![Profilbild](/assets/img/speakers/SpeakerName.jpg)

## Kontakt:
- [E-Mail](mailto:me@domain.com)
- [Twitter](https://twitter.com/handle)
- [XING](https://xing.de/...)
- [Facebook](https://facebook.com/...)
- [Blog](http://www.myblog.com/)
- [Website](http://www.website.de/)

## Bio:
Kurze Beschreibung zur Person, wie sie üblicherweise für Talks verwendet wird.
~~~

Falls ihr nicht schon ein Profil habt, kopiert diesen Code und platziert ihn in eine neue MarkDown-Datei. Passt den Code dann entsprechend den folgenden Regeln an.

Zum anlegen oder ändern des Profils erstellt ihr bitte ein Pull-Request. Das Team wird den Pull-Request anschauen, ggf. um Änderungen bitten, oder direkt mergen.   

## Regeln zur Profildatei

Generell sollte alle Profilseiten ähnlich aufgebaut sein, daher solltet ihr euch an folgende Regeln halten:

- Die Profil-Datei wird wie der Sprecher bennant, aber ohne Lehrzeichen und ohne Umlaute, bzw. Sonderzeichen (URL-konform). Z. B: aus "Jürgen Gutsch" wird "JuergenGutsch.md"
- Der volle Name und die themen werden nur in den Metadaten (Front-Matters) hinterlegt.
- Auf der Seite selber werden die ersten beiden Zeilen mit page.title und page.topics nicht geändert und genau so übernommen.
- Das Profilbild ist das einzige Bild und sollte 300x300px betragen, ansonsten wird es per CSS verzerrt dargestellt
- Die Kontaktdaten sollten so vollständig wie möglich sein. Nicht alle Daten müssen angegeben werden, aber damit werdet ihr von den UGs Kotaktiert. Last das was ihr nicht angeben wollt komplett weg.
- Die Bio so kompakt wie möglich halten, so wie ihr sie üblicherweise bei Konferenzen, Events, Talks, etc. angebt. Übermäßig grosse Bios werden nicht anzeptiert. 

Sollte änderungen für ein Profil stark von den Regeln abweichen, können wir es nicht akzeptiern und bitten um Nachbeserung.
 
## Pull-Requests

Erstellt für das neue oder geänderte Speakerprofil einen Pull-Request.  