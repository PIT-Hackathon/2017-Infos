# IoT - Internet of Things

Eines der Themen für den [PIT-Hackathon 2017](https://github.com/PIT-Hackathon/2017-Infos) ist die Entwicklung eines IoT Systems und auf dieser Seite erfährst Du, was es mit dem Thema auf sich hat. Falls das etwas für Dich ist, kannst Du Dich mit Hilfe von ein paar kleinen Aufgaben schon ein bisschen vorbereiten - musst es aber natürlich nicht.

## Was ist IoT?

Der Begriff IoT steht für Internet of Things bzw. das Internet der Dinge. Grob gesagt, wird versucht, die analoge Welt um uns herum digital greifbar zu machen um mit diesen Daten neue Informationen zu gewinnen und sie weiterzuverarbeiten. Sei es ein einfacher Schalter oder ein Bewegungssensor, die Wetterstation oder das Hamsterrad - alles kann Daten liefern und ins Netz gestellt werden. Genauso können die vernetzen Geräte auf diese Daten zugreifen und selbst wieder auf andere Daten reagieren.

## Was muss ich können/mitbringen, um eine IoT Anwendung beim Hackathon zu entwickeln?

Spaß am Basteln und gute Ideen. Evtl. kennst Du bereits den Arduino, den Raspberry Pi oder ein NodeMCU und hast schonmal damit gearbeitet oder Du kennst Dich etwas mit Elektronik aus.

## Das hört sich schon mal gut an - wie geht es weiter?

Welches Thema Du wählen möchtest, musst Du erst zu Beginn des Hackathons entscheiden. Vielleicht informierst Du Dich schon mal bei den [anderen Themen](https://github.com/PIT-Hackathon/2017-Infos), ob noch eine Alternative für Dich dabei ist.

## Kann ich mich schon irgendwie vorbereiten?

Eine Vorbereitung ist nicht notwendig, erlaubt Dir aber natürlich an dem Wochenende tiefer ins Thema einzusteigen. Falls Du also schonmal ins Thema reinschnuppern möchtest, findest Du hier ein paar Links. Schaue Dir doch mal ein paar Tutorials an, vielleicht hast Du ja schon eine gute Idee, die Du während des Hackathons kurz vorstellen und dann gemeinsam in der Gruppe umsetzen möchtest.

### Hardware / Software

Für den Hackathon haben wir eine Auswahl an Hardware zusammengestellt, mit der wir im Bereich Internet of Things arbeiten wollen.

#### Raspberry Pi

Einst als kleiner und günstiger Computer für Schulen und die Lehre entwickelt, hat sich der Raspberry Pi als Bastelrechner durchgesetzt. Er kommt während des Hackathons als Steuerzentrale für das IoT zum Einsatz und kann zusätzlich über eine Erweiterungsschnittstelle selbst Hardwaremodule ansprechen.

- <https://tutorials-raspberrypi.de/>

![Raspberry Pi 3](images/RaspberryPi.jpg)

#### NodeMCU / ESP8266

Die NodeMCU Hardware ist eine Mikrocontroller-Plattform ähnlich zum Arduino. Da sie sehr günstig ist und zudem auch WLAN mitbringt, ist sie bestens geeignet um Sensorknoten für unser IoT-System zu entwickeln. Im Gegensatz zum Raspberry Pi ist sie natürlich nicht so leistungsfähig, dennoch reicht die Geschwindigkeit zum Erfassen und Senden von Sensordaten aus.

- <http://www.mikrocontroller-elektronik.de/nodemcu-esp8266-tutorial-wlan-board-arduino-ide/>

![NodeMCU ESP8266 Mikrocontroller](images/NodeMCU.png)

#### Sensoren

Damit Du Deine IoT Idee umsetzen kannst, haben wir versucht, eine Auwahl an Sensoren und Aktoren zu treffen, die Dir und den anderen Gruppen während des Hackathons zur Verfügung stehen. Schau Dir doch mal die Liste an, vielleicht hast Du ja eine gute Idee, was für ein Projekt man mit den Bauteilen umsetzen könnte. Die genauen Bezeichnungen der Module können Dir helfen, mehr Informationen zu den einzelnen Komponenten zu finden.

- NFC Module (RC522 RFID-Modul) und passende NFC Tags zur kontaktlosen Kommunikation ([Arduino Bibliothek](https://github.com/miguelbalboa/rfid))
- TFT Displays (240x320, ILI9341 kompatibel)
- Adafruit NeoPixel Stick
- Temperatur- / Luftfeuchtigkeitssensoren (DHT22)
- Gyroskop (Lagesensor, der Bewegungen in unterschiedliche Richtungen erkennen kann - ITG3205)
- 433MHz Sender zum Steuern von Funksteckdosen
- [37teiliges Arduino Sensorpaket (Wiki von Tkkrlab.nl)](https://tkkrlab.nl/wiki/Arduino_37_sensors)
- ...

##### Bibliotheken

#### MQTT - MQ Telemetry Transport oder Message Queue Telemetry Transport

MQTT ist ein Nachrichtenprotokoll für die sogenannte M2M (Machine to Machine) Kommunikation. Es ist relativ leichtgewichtig, wird sowohl vom Raspberry Pi als auch von den NodeMCU Mikrocontrollern unterstützt, hat sich im Bereich IoT einen festen Platz ergattert und soll damit als Grundlage für die Kommunikation während des Hackathons dienen.
Die Kommunikation mit dem Server (im MQTT Umfeld auch Broker genannt) erfolgt von Seiten der Clients über Topics, auf die sie lesen oder schreiben können. Topics können dabei hierarchisch angelegt werden. Ein Beispiel wäre eine Wetterstation, die in das Topic "/wetter/paderborn/temperatur" jeweils die aktuelle Temperatur hineinschreibt. Ein weiterer Client könnte dann dieses Topic lauschen und wird vom Broker benachrichtigt, wenn es neu geschrieben wird.

- [Einführung in MQTT](https://www.predic8.de/mqtt.htm)

### Tools

Folgende Tools werden wir für die Entwicklung verwenden. Solltest Du Deinen eigenen Rechner zum Entwickeln mitbringen, kannst Du Dir zur Vorbereitung die Tools bereits installieren und sie Dir schonmal etwas genauer anschauen.

#### Arduino IDE

Um für die eingesetzten Mikrocontroller Programme zu entwickeln, benötigen wir die Arduino IDE. Sie kann von der Webseite [Arduino.cc](http://www.arduino.cc) heruntergeladen werden. Da wir allerdings nicht direkt für die Arduino Plattform Programme entwickeln, sondern für die NodeMCU Plattform, muss die Arduino IDE noch für dieses Board eingerichtet werden. Wenn Du dem Link in dem [NodeMCU Abschnitt](#nodemcu--esp8266) folgst, findest Du in der NodeMCU Einführung unter "Schritt 2 – Die Arduino IDE installieren und konfigurieren" eine Anleitung, wie man das NodeMCU Board einbindet.

#### MQTT.fx

Um während des Hackathons einfacher auf einen MQTT Server, der z.B. auf einem Raspberry Pi laufen kann, zugreifen zu können oder selbst Nachrichten über einen MQTT Server zu versenden, kann ein MQTT Client verwendet werden. Ein guter Client, der frei verfügbar ist, ist MQTT.fx. Du kannst ihn unter folgendem Link erreichen

- <http://www.mqttfx.org/>
