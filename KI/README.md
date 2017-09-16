# Künstliche Intelligenz
Eines der Themen für den PIT-Hackathon 2017 ist die Entwicklung von Chatbots
unter Einsatz von künstlicher Intelligenz. Auf dieser Seite erfährst Du, was es
mit dem Thema auf sich hat. Falls das etwas für Dich ist, kannst Du Dich und
deinen Laptop mit Hilfe der Informationen hier auf den Hackathon vorbereiten -
das ist allerdings keine Voraussetzung, sondern freiwillig.

## Was ist Künstliche Intelligenz?
Die Beantwortung von Wissensfragen, das Erkennen von berühmten Bauwerken auf
Bildern oder die einfache Spracherkennung in Apps - mittlerweile haben einige
Anwendungen Einzug in den Alltag gehalten, die auf Künstlicher Intelligenz
basieren. Und in Zukunft werden noch ganz andere Dinge unterstützt werden: Die
Prognose des Arztes, die Nachbearbeitung eines Handy-Schnappschusses und
vielleicht sogar die Klausur-Aufgaben.

Künstliche Intelligenz ist ein Gebiet in der Informatik, dass sich mit der
Automatisierung intelligenten Verhaltens befasst. Oft geht es dabei darum,
menschliche Intelligenz nachzuahmen.
(Quelle: [Wikipedia](https://de.wikipedia.org/wiki/Künstliche_Intelligenz))

Bei der Künstlichen Intelligenz gibt es wiederum verschiedene Teilgebiete, eins
dieser Gebiete ist die Musteranalyse und -erkennung. Hier geht es unter anderem
darum, Sätze zu verstehen oder den Inhalt von Bildern zu erkennen. Mit diesem
Themengebiet wollen wir uns beim Hackathon auseinandersetzen.

Auf diesem Gebiet hat in den letzten Jahren der Einsatz von maschinellem Lernen
und neuronalen Netzen als Hilfsmittel großen Fortschritt gebracht. Ziel ist es
hier, aus einer Menge an Beispielen automatisiert Regeln abzuleiten, mit denen
dann neue, unbekannte Beispiele korrekt erkannt werden. Das wollen wir beim
Hackathon ausprobieren.

## Was wollen wir machen?
Prinzipiell sollen die Teilnehmer gemeinsam herausfinden und entscheiden, was
die Gruppe entwickelt. Um den Einstieg in das Thema zu vereinfachen, werden wir
aber ein paar Dinge vorbereiten.

Wir haben uns als Grundlage für das Thema Künstliche Intelligenz und den
Hackathon Folgendes Gartenszenario überlegt:

Wir werden einen Chatbot (errbot) vorbereiten, der in Slack integriert ist.
Damit kann der Chatbot Nachrichten an den Slack-Channel senden und diese
empfangen. Damit wir die Nachrichten der Nutzer verstehen und damit etwas
Sinnvolles anfangen, bieten wir eine Integration in eine Texterkennungsplattform
(WIT.ai) an. Außerdem, bieten wir eine einfache Integration in die IoT-Welt,
damit von dem Chatbot aus eine Lampe an- und ausgeschaltet werden kann. Das
müsst ihr dann aber noch alles zusammenbauen, damit man von dem Chat aus die
Lampe an- und ausschalten kann.

Auf dieser Grundlage könnt ihr dann außerdem das Ganze ausbauen, z.B.
komplizierte Texte erkennen bzw. Befehle auslösen oder andere KI-Dienste
anbinden (z.B. Bilderkennung, Spracherkennung, Wikipedia, Wolfram Alpha, ...).
Was ihr macht, liegt letztendlich an euch.

## Was muss ich können/mitbringen, um mit KI beim Hackathon zu entwickeln?
Nur deinen Kopf und bestenfalls deinen Laptop! Wenn Du schon ein wenig in Python
programmieren kannst umso besser.

Es ist zwar von Vorteil, wenn du dich schon Mal mit der Programmiersprache
Python oder sogar den hier vorgestellten Tools auseinander gesetzt hast - eine
Voraussetzung ist das allerdings nicht!

Die meiste “Magie” wird über normale Programmierschnittstellen (also
Funktions-/Methodenaufrufe) geregelt. Außerdem gibt es noch eine zugängliche
Benutzeroberfläche für das Trainieren der Texterkennung mit WIT.

## Das hört sich schon mal gut an - wie geht es weiter?
Welches Thema Du wählen möchtest, musst Du erst zu Beginn des Hackathons
entscheiden. Vielleicht informierst Du Dich schon mal bei den anderen Themen, ob
noch eine Alternative für Dich dabei ist.

## Kann ich mich schon irgendwie vorbereiten?
Eine Vorbereitung ist nicht notwendig, erlaubt Dir aber natürlich an dem
Wochenende tiefer ins Thema einzusteigen. Falls Du also schonmal ins Thema
reinschnuppern möchtest, findest Du hier ein paar Links.

## Tools
Folgende Tools werden wir für die Entwicklung verwenden

### Visual Studio Code (Entwicklungsumgebung)
Welchen Editor man für die Entwicklung nutzt, ist fast egal. Falls Du nicht auf
einen bestimmten Editor festgelegt bist, lohnt sich auf jeden Fall ein Blick auf
VS Code. Viele sind erstmal von "Visual Studio" irritiert und denken an die
riesige Entwicklungsumgebung von Microsoft - aber VS Code heisst nur aus
Marketing-Gründen wie der große Bruder, hat mit ihm aber eigentlich nichts zu
tun. Dieser Text wurde übrigends mit VS Code und Spacemacs geschrieben ;)
https://code.visualstudio.com/

### Python-Interpreter (Programmiersprache, Ausführumgebung)
Python ist eine interpretierte Programmiersprache, die einen Interpreter für die
Ausführung benötigt. Unter Linux ist der entsprechende Interpreter in der
Paketverwaltung zu finden für Windows kann man den Interpreter hier herunterladen:
[www.python.org/downloads/](https://www.python.org/downloads/)
(Für den Hackathon sollte der Interpreter in Version 3.x verwendet werden)

Die Sprache und die Standard-Bibliothek ist hier dokumentiert:
[docs.python.org/3/](https://docs.python.org/3/)  
Das offizielle Tutorial findet ihr hier:
[docs.python.org/3/tutorial/](https://docs.python.org/3/tutorial/)  
Aber es gibt auch viele weitere Tutorials im Netz, zum Beispiel:
https://www.learnpython.org/

Um mit Visual Studio Code Python zu entwickeln empfielt es sich die Python
Extension zu installieren: https://marketplace.visualstudio.com/items?itemName=donjayamanne.python

### GIT-Client (Versionsverwaltung)
GIT ist eine weit verbreitete Quellcode-Versionsverwaltung. Eine
Quellcode-Versionsverwaltung hilft dabei den Quellcode einfach im Team
auszutauschen und zu integrieren. Außerdem hilft sie dabei Änderungen am
Quellcode zu versionieren und damit nachverfolgbar zu machen. Die Datei, die du
gerade liest, ist zum Beispiel bei Github abgelegt - wie der Name vermuten
lässt, ist das ein GIT-basiertes System.

Wir empfehlen, dass du mit deinem Team GIT einsetzt. GIT-Clients für Windows
sind z.B. [Sourcetree](https://www.sourcetreeapp.com/) und [GitKraken](https://www.gitkraken.com/).
Linux-User finden noch weitere GIT-Clients in ihrer wohlbekannten Paketverwaltung.

### GIT, GIT-Bash (Versionsverwaltung, Shell)
Je nach GIT-Client, braucht man noch die zugrunde liegenden Konsolen-Tools, die
von dem GIT-Client dann aufgerufen werden. Mit dabei ist unter anderem
GIT-Bash - diese emuliert die unter Linux bekannte Bash-Textkonsole (Shell). Die
wiederum erlaubt es, erste Schritte mit der WIT-Plattform zu testen.

Linux-User finden Git in ihrer wohlbekannten Paketverwaltung und für die
Windows-Plattform findet man es hier: [Git-for-Windows](https://git-for-windows.github.io/)

### WIT.ai (Textanalyse-Plattform)
[WIT](https://wit.ai) ist eine Plattform, die uns dabei hilft die eine Texterkennung nach unseren Bedürfnissen zu erstellen und anzupassen.

Danach können wir aus unserer Anwendung heraus einen Text an die WIT-Plattform
schicken und die schickt uns dann den erkannten Inhalt in einer Form zurück, die
man gut in Anwendungen verarbeiten kann. Dabei muss der Text nicht genau dem
entsprechen was wir vorsehen, sondern er muss nur “so ähnlich” sein.
Beispielsweise folgende Texte:

> * “What is the weather in Paris?”
> * “Give me the current weather in Paris”
> * “Is it sunny or rainy in Paris now?”

... könnten dazu führen dass Folgendes verstanden und zurückgeliefert wird:
```JSON
{
    "msg_id": ...,
    "_text": ...,
    "entities": {
        "intent": [{
            "confidence": 0.99797362726099,
            "value": "weather"
        }, {
            ...
        }],
        "location": [{
            "confidence": 0.938,
            "value": "Paris"
        }, {
            ...
        }]
    }
}
```
WIT ist sich also zu 99% bzw. 93% sicher, dass es darum geht das Wetter für den Ort Paris zu erfahren.

Eine Einführung Tutorials und Beispiele zu WIT findet ihr unter:
[wit.ai/docs](https://wit.ai/docs). Dort könnt ihr euch einen kostenlosen Account
erstellen und schon Mal etwas rumprobieren.

### ErrBot (Multi-Backend Chatbot)
Der [Errbot](http://errbot.io) ist ein in Python geschriebener Chatbot, der sich
an verschiedene Chat-Systeme anklemmen lässt:
* Slack
* Telegram
* HipChat
* IRC
* XMPP
* Test 
* Standalone

Man kann ihm konkrete Kommandos beibringen mit denen er einem Benutzer gewisse
Dienste abnehmen soll und darüber hinaus kann man ihm durch eine Integratio mit
Wit.ai beibringen, in laufende Konversationen hinein zu lauschen um zu diesen
dann relevante Informationen zu liefern oder als Reaktion Kommandos auszuführen.
Ausserdem kann man ihm darüber beibrigen, für komplexere Aktionen beim Benutzer
nach Details zu fragen. Beispiel für eine Lampen-Steuerung:

> * User:   Errbot es ist zu hell.
> * Errbot: Aktuell ist die Helligkeit bei 70%. Um wieviel Prozent soll ich dimmen?
> * User:   Um 20% bitte.
> * Errbot: Das Licht wurde von mir um 20% auf 50% gedimmt. Stimmt es so?
> * User:   Immer noch zu hell.
> * Errbot: Um wieviel Prozent soll ich dimmen?
> * User:   Um 10% bitte.
> * Errbot: Das Lich wurde von mit um 10% auf 40% gedimmt. Stimmt es so?
> * User:   Ja.
> * Errbot: Alright.

Die Herausforderung liegt dabei nicht nur in der Integration mit Wit.ai
sondern auch darin für einen gegebenen User den Status der Konversation zu
speichern und nachzuverfolgen.

### PAHO-MQTT
[Paho-MQTT](https://pypi.python.org/pypi/paho-mqtt/1.3.0) ist eine Python-Bibliothek
für das MQTT-Protokoll.

MQTT ist ein Client-Server-Protokoll (der Server wird auch "Broker" genannt)
für die Machine-to-Machine-Kommunikation (M2M) und wird im Bereich
Internet-of-Things eingesetzt. Eine MQTT Nachricht besteht aus einem Header,
dem Topic (das Thema, auf das sich die Nachricht bezieht) und der Payload (die
eigentliche Information).
(Siehe auch: [Wikipedia](https://de.wikipedia.org/wiki/MQTT))

Die von uns bereitgestellte "Lampe" unterstützt folgende Befehle:

| Befehl             | Topic              | Payload |
|--------------------|--------------------|---------|
| Lampe einschalten  | /ki/lamp1/cmd/set  | on      |
| Lampe ausschalten  | /ki/lamp1/cmd/set  | off     |
| Status abfragen    | /ki/lamp1/cmd/get  | state   |

Als Antwort auf die Befehle sendet die Lampe jeweils über das Topic
`/ki/lamp1/state` den aktuelle Status (`on` oder `off`).
