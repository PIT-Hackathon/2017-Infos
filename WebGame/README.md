# Web Game
Das Thema "Web" Game beim [PIT-Hackathon 2017](https://github.com/PIT-Hackathon/2017-Infos) umfasst die erste Phase der Spieleentwicklung, von der Erstellung eines Konzepts bis zum lauffähigen Prototypen. Dabei werdet ihr diverse Rolle wie Game Designer, Game Developer, Visual Artist, Audio Engineer uvm. einnehmen und zusammen im Team euer Spiel entwickeln. 

## Was ist ein Web Game?
Ein Web Game ist ein im Browser lauffähiges Spiel und kann ohne Installation auf diversen Geräten (PC, Handy, usw.) gespielt werden. Bei Bedarf lässt sich das Spiel auch in eine Desktop Applikation [verpacken](https://electron.atom.io). Trotz Browser können die Spiele auf die Besonderheiten der Endgeräte reagieren und so z.B. den Neigungssensor im Handy als Lenkrad in das Spiel integrieren.

## In welchen Rollen werden wir an dem Spiel arbeiten?
Ihr werdet eine oder mehrere der folgenden Rollen bei der Entwicklung einnehmen.

### Game Designer
Der Game Designer einwickelt eine Vision des Spiels. Er beschreibt was der Spieler in dem Spiel unternehmen kann, welche Charaktere er treffen wird und welche Entscheidungen er treffen kann. Alle Optionen und sämtliche Interaktionen werden durch den Game Designer definiert.

### Game Developer
Als Game Developer setzt ihr die Ideen des Game Designer technisch um. Dafür werden diverse Kompontenten wie Physik, Grafik Engine, AI uvm. entwickelt oder integriert.

### Visual Artist
Der Visual Artist erstellt alle visuallen Element, wie 3D Modelle, Texturen, Materialien und Effekte, für das Spiel.

### Audio Engineer
Der Audio Engineer ist vergleichbar mit dem Visual Artist, nur das dieser statt Grafiken Geräusche erstellt. Dazu gehören neben Effekten auch die Hintergrund Musik, der Sound Track und vertonte Dialoge.

### Animator
Der Animator erweckt die 3D Modelle des Visual Artist zum Leben.

### Level Designer
Der Level Designer kombiniert die visuellen und akustischen Komponenten und erstellt damit ein Level für das Spiel. 

### Producer
Der Producer steuert und überwacht den Erstellungsprozess des Spiels (auch Finanziell).

### QA Tester
Die QA bestätigt die Qualität des Spiels und zeigt Mängel (Bugs) auf.

## Gibt es ein Game Engine die ich verwenden kann?
Es gibt [diverse Game Engines](https://github.com/showcases/javascript-game-engines) mit der ihr euer Web Game erstellen könnt. Um euch die Auswahl zu erleichtern haben wir  drei Engines ausgewählt und entsprechende Vorlagen vorbereitet.

### Phaser
Phaser ist eine Open Source 2D Game Engine um HTML 5 Spiele für den Browser als auch dem Desktop zu entwickeln.

Weiter Infos: [http://phaser.io](http://phaser.io)

Vorlagen auf GitHub:
- JavaScript [https://github.com/PIT-Hackathon/2017-WebGame-Phaser-ES2017](https://github.com/PIT-Hackathon/2017-WebGame-Phaser-ES2017)

### Babylon.js
Babylon.js ist eine Open Source 3D Game Engine. Die Engine wurde komplett in Typescript geschrieben.

Weiter Infos: [https://www.babylonjs.com](https://www.babylonjs.com)

Vorlagen auf GitHub:
- JavaScript [https://github.com/PIT-Hackathon/2017-WebGame-Babylon-ES2017](https://github.com/PIT-Hackathon/2017-WebGame-Babylon-ES2017)
- TypeScript [https://github.com/PIT-Hackathon/2017-WebGame-Babylon-TypeScript](https://github.com/PIT-Hackathon/2017-WebGame-Babylon-TypeScript)

### Three.js
Wer eine 3D-Anwendung wie ein Spiel ins Internet bringen will, kommt an WebGL kaum vorbei. Doch die Programmierung darin ist umständlich und fehleranfällig. Mit der JavaScript-Bibliothek Three.js gehts viel leichter.
WebGL bietet dem JavaScript-Entwickler eine Unmenge an Möglichkeiten – von der Darstellung einfacher 3D-Modelle bis hin zur direkten Programmierung des Grafikprozessors. 

Weiter Infos: [https://threejs.org](https://threejs.org)

Vorlagen auf GitHub:
- JavaScript [https://github.com/PIT-Hackathon/2017-WebGame-Three-ES2017](https://github.com/PIT-Hackathon/2017-WebGame-Three-ES2017)

## Muss das Spiel im Browser (Web) laufen oder kann ich auch eine Desktop Applikation entwickeln?
Nein, es muss kein Web Game sein. Du kann auch jede beliebig andere Plattform nutzen. 

## Kann ich auch eine andere Sprache oder Tool (z.B. Unity) verwenden?
Ja, du kannst jede andere Sprache oder Tool verwenden. Wir Mentoren haben uns jedoch speziell auf die Web Entwicklung mit Phaser & Co vorbereitet.

## Womit entwickeln wir nachher?
Wenn du unsere Vorlagen verwendest, dann benötigst du nur folgende Tools für die Entwicklung. Diese könnt ihr vorab auf eueren Geräten installieren oder wir machen das zu Beginn des Hackathons.

### 1. Code Editor 
Ihr benötigt einen Text Editor um den Source Code schreiben zu können. Am besten einen mit Syntax Highlight, Code Vervollständigung und Validierung. Unser Vorschlag: Visual Studio Code [https://code.visualstudio.com](https://code.visualstudio.com)

### 2. Node.js und NPM
Node.js werden wir zum "kompilieren" oder besser [transpilieren](https://en.wikipedia.org/wiki/Source-to-source_compiler) des Source Codes verwenden. Dabei kommen Tools wie [Babel](https://babeljs.io) oder [Typescript](https://www.typescriptlang.org) zum Einsatz. Diese Tools und auch die notwendigen Bibliotheken für euer Projekt findet ihr in der [NPM Registry](https://www.npmjs.com).

Download: [https://nodejs.org](https://nodejs.org)

### 3. Webpack [Optional/Intern]
Webpack ist ein Module-Bundler und gleichzeitig Build-System. Das heißt es fasst mehrere Module (z.B. NPM Pakete) in zusammen und das Build-System konvertiert die Module in ein für den Browser verständliches Format. Dazu gibt es noch einen passenden Server mit dem Ihr euer Spiel lokal hosten könnt. Webpack überwacht dabei den gesamten Quellcode und erstelle automatisch eine neue Version sobald eine Änderung festgestellt wurde. 

Weiter Infos findet ihr im Git Repository: [https://github.com/webpack/webpack](https://github.com/webpack/webpack)

### 4. Git - Source Code Verwaltung [Optional]
Da ihr im Team arbeiten werden, ich eine Source Code Verwaltung ideal. Damit könnt ihr jederzeit Nachvollziehen, wer was geändert hat und im idealen Fall können Änderungen ohne Probleme zusammengefasst werden. Wenn es dann doch mal einen Konflikt gibt, dann wird GIT euch den entsprechenden Bereich markieren und ihr könnte bequem (abhängig vom Editor) entscheiden welche Änderung übernommen werden soll. 

* Download: [https://git-scm.com](https://git-scm.com)
* Anleitung: [tryGit - learn git in 15 minutes](https://try.github.io/levels/1/challenges/1)
* MOOC: [Wie man Git und GitHub nutzt](https://de.udacity.com/course/how-to-use-git-and-github--ud775)

## Tutorials & Anleitungen

- Phaser
    - [http://phaser.io/](http://phaser.io/)
    - [Examples](http://phaser.io/examples)
- Babylon.js
    - [https://www.babylonjs.com/](https://www.babylonjs.com/)
    - [Tutorials](http://doc.babylonjs.com/tutorials)
- Three.js
    - [https://threejs.org/](https://threejs.org/)
    - [Examples](https://threejs.org/examples/)
- Javascript [ECMAScript 2017] 
    - [Grundlagen_der_Programmierung](https://wiki.selfhtml.org/wiki/JavaScript/Tutorials/Grundlagen_der_Programmierung)
    - [ECMAScript 6 (2015) Tutorial](http://ccoenraets.github.io/es6-tutorial/)
    - [ES2017 async/await to the rescue](https://medium.com/@tmvvr/ecmascript-async-await-to-the-rescue-fc379ff89146)
- Typescript [https://www.typescriptlang.org/](https://www.typescriptlang.org/)
    - [Typescript in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
    - [Playground](https://www.typescriptlang.org/play/index.html)
- HTML5
    - [Tutorial](https://wiki.selfhtml.org/wiki/HTML/Tutorials/HTML5-Grundger%C3%BCst)
- Massiv Open Online Courses (MOOC) zu Gamedesign und Gamedevelopment
    - [edX : 5 teiliger Kurs zu Gamedesign & -development](https://www.edx.org/xseries/video-game-design)
    - [studyToLearn: Kurs zu Konzepten im Gamedesign](https://www.open2study.com/courses/concepts-in-game-development)
    - [coursera: Game Design and Development Specialization](https://www.coursera.org/specializations/game-development)
    - [coursera: Game Design Art and Concepts Specialization](https://www.coursera.org/specializations/game-design)
    - [und natürlich: ExtraCredits](https://www.youtube.com/user/ExtraCreditz)
- Tools
    - [Jesse Schell: A book of lense (Android App)](https://play.google.com/store/apps/details?id=com.schellgames.deckoflenses&hl=de)
    - [MDA Framework: A Formal Approach to Game Design and Game Research](http://www.cs.northwestern.edu/~hunicke/MDA.pdf)
    - [High Concept Document Template](https://www.dropbox.com/s/cit5rsx8f5d5o6b/HighConceptTemplate.pdf?dl=0)
    - [One Page Game Design Document Template](https://www.dropbox.com/s/xfmzl2d64teinre/OnePageGameDesignDocument.pdf?dl=0)
    - [Game Story Bible Template](https://www.dropbox.com/s/hapw4l0bev115r5/GameStoryBibleTemplate.pdf?dl=0)
- Software
    - [Autodesk 3ds Max (Educational)](http://www.autodesk.com/education/free-software/3ds-max)
    - [Autodesk Maya (Educational)](https://www.autodesk.com/education/free-software/maya)
- Texturen
    - [CG Textures](http://www.cgtextures.com/)
    - [Texture King](http://www.textureking.com)
    - [Stock Textures](http://stocktextures.com/)
- Audio Assets
    - [Flashkit](http://www.flashkit.com/soundfx/)
    - [Indie Game Music](http://indiegamemusic.com/)
    - [Jamendo](http://www.jamendo.com/)
    - [Free Sound Effects](http://www.freesoundeffects.com/)
    - [Free Sound Project](https://freesound.org/)
- Models
    - [TurboSquid](http://www.turbosquid.com/Search/?KEYWORD=Free)
    - [Archive 3d](http://www.archive3d.net)
    - [3d Xtras](http://www.3dxtras.com/index.asp)
    - [Artist-3d](http://www.artist-3d.com/)
    - [Exchange 3d](http://www.exchange3d.com/FreeModels/cat_35.html)
    
    


