# IoT - Internet of Things
Eines der Themen f�r den [PIT-Hackathon 2017](https://github.com/PIT-Hackathon/2017-Infos) ist die Entwicklung eines IoT Systems und auf dieser Seite erf�hrst Du, was es mit dem Thema auf sich hat. Falls das etwas f�r Dich ist, kannst Du Dich mit Hilfe von ein paar kleinen Aufgaben schon ein bisschen vorbereiten - musst es aber nat�rlich nicht.

## Was ist IoT?
Der Begriff IoT steht f�r Internet of Things bzw. das Internet der Dinge. Grob gesagt, wird versucht, die analoge Welt um uns herum digital greifbar zu machen um mit diesen Daten neue Informationen zu gewinnen und sie weiterzuverarbeiten. Sei es ein einfacher Schalter oder ein Bewegungssensor, die Wetterstation oder das Hamsterrad - alles kann Daten liefern und ins Netz gestellt werden. Genauso k�nnen die vernetzen Ger�te auf diese Daten zugreifen und selbst wieder auf andere Daten reagieren.

## Was muss ich k�nnen/mitbringen, um eine IoT AnwenDung beim Hackathon zu entwickeln?
Spa� am Basteln und gute Ideen. Evtl. kennst Du bereits den Arduino, den Raspberry Pi oder ein NodeMCU und hast schonmal damit gearbeitet oder Du kennst dich etwas mit Elektronik aus.

## Das h�rt sich schon mal gut an - wie geht es weiter?
Welches Thema Du w�hlen m�chtest, musst Du erst zu Beginn des Hackathons entscheiden. Vielleicht informierst Du Dich schon mal bei den [anderen Themen](https://github.com/PIT-Hackathon/2017-Infos), ob noch eine Alternative f�r Dich dabei ist.

## Kann ich mich schon irgendwie vorbereiten?
Eine Vorbereitung ist nicht notwendig, erlaubt Dir aber nat�rlich an dem Wochenende tiefer ins Thema einzusteigen. Falls Du also schonmal ins Thema reinschnuppern m�chtest, findest Du hier ein paar Links. Schaue Dir doch mal ein paar Tutorials an, vielleicht hast Du ja schon eine gute Idee, die Du w�hrend des Hackathons kurz vorstellen und dann gemeinsam in der Gruppe umsetzen m�chtest.

### Hardware / Software
F�r den Hackathon haben wir eine Auswahl an Hardware zusammengestellt, mit der wir im Bereich Internet of Things arbeiten wollen.

#### Raspberry Pi
Einst als kleiner und g�nstiger Computer f�r Schulen und die Lehre entwickelt, hat sich der Raspberry Pi als Bastelrechner durchgesetzt. Er kommt w�hrend des Hackathons als Steuerzentrale f�r das IoT zum Einsatz und kann zus�tzlich �ber eine Erweiterungsschnittstelle selbst Hardwaremodule ansprechen.

- https://tutorials-raspberrypi.de/

![Raspberry Pi 3](images/RaspberryPi.jpg)

#### NodeMCU / ESP8266
Die NodeMCU Hardware ist eine Mikrocontroller-Plattform �hnlich zum Arduino. Da sie sehr g�nstig ist und zudem auch WLAN mitbringt, ist sie bestens geeignet um Sensorknoten f�r unser IoT-System zu entwickeln. Im Gegensatz zum Raspberry Pi ist sie nat�rlich nicht so leistungsf�hig, dennoch reicht die Geschwindigkeit zum Erfassen und Senden von Sensordaten aus.

- http://www.mikrocontroller-elektronik.de/nodemcu-esp8266-tutorial-wlan-board-arduino-ide/

![NodeMCU ESP8266 Mikrocontroller](images/NodeMCU.png)

#### Sensoren


#### MQTT - MQ Telemetry Transport oder Message Queue Telemetry Transport
MQTT ist ein Nachrichtenprotokoll f�r die sogenannte M2M (Machine to Machine) Kommunikation. Es ist relativ leichtgewichtig, wird sowohl vom Raspberry Pi als auch von den NodeMCU Mikrocontrollern unterst�tzt, hat sich im Bereich IoT einen festen Platz ergattert und soll damit als Grundlage f�r die Kommunikation w�hrend des Hackathons dienen.
Die Kommunikation mit dem Server (im MQTT Umfeld auch Broker genannt) erfolgt von Seiten der Clients �ber Topics, auf die sie lesen oder schreiben k�nnen. Topics k�nnen dabei hierarchisch angelegt werden. Ein Beispiel w�re eine Wetterstation, die in das Topic "/wetter/paderborn/temperatur" jeweils die aktuelle Temperatur hineinschreibt. Ein weiterer Client k�nnte dann dieses Topic lauschen und wird vom Broker benachrichtigt, wenn es neu geschrieben wird.

- [Einf�hrung in MQTT](https://www.predic8.de/mqtt.htm)

### Tools
Folgende Tools werden wir f�r die Entwicklung verwenden. Solltest Du Deinen eigenen Rechner zum Entwickeln mitbringen, kannst Du Dir zur Vorbereitung die Tools bereits installieren und sie Dir schonmal etwas genauer anschauen.

#### Arduino IDE
Um f�r die eingesetzten Mikrocontroller Programme zu entwickeln, ben�tigen wir die Arduino IDE. Sie kann von der Webseite [Arduino.cc](http://www.arduino.cc) heruntergeladen werden. Da wir allerdings nicht direkt f�r die Arduino Plattform Programme entwickeln, sondern f�r die NodeMCU Plattform, muss die Arduino IDE noch f�r dieses Board eingerichtet werden. Wenn Du dem Link in dem [NodeMCU Abschnitt](#nodemcu--esp8266) folgst, findest Du in der NodeMCU Einf�hrung unter "Schritt 2 � Die Arduino IDE installieren und konfigurieren" eine Anleitung, wie man das NodeMCU Board einbindet.

#### MQTT.fx
Um w�hrend des Hackathons einfacher auf einen MQTT Server, der z.B. auf einem Raspberry Pi laufen kann, zugreifen zu k�nnen oder selbst Nachrichten �ber einen MQTT Server zu versenden, kann ein MQTT Client verwendet werden. Ein guter Client, der frei verf�gbar ist, ist MQTT.fx. Du kannst ihn unter folgendem Link erreichen

- http://www.mqttfx.org/

##### Bibliotheken


