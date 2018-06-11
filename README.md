# ![icon](https://cloud.githubusercontent.com/assets/20374208/26214265/6b605cae-3c04-11e7-9c14-2cd59e10dd03.png)   XR3Player

> Download installer for [ Windows](https://goxr3plus.github.io/xr3player.io/) ,  Linux (not yet available )  ,  Mac (not yet available)

> Visit  [website](https://goxr3plus.github.io/xr3player.io/)


[![Latest Version](https://img.shields.io/github/release/goxr3plus/XR3Player.svg?style=flat-square)](https://github.com/goxr3plus/XR3Player/releases)
[![Join the chat at https://gitter.im/XR3Player/Lobby](https://badges.gitter.im/XR3Player/Lobby.svg)](https://gitter.im/XR3Player/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![HitCount](http://hits.dwyl.io/goxr3plus/xr3player.svg)](http://hits.dwyl.io/goxr3plus/xr3player)
<a href="https://sourceforge.net/projects/xr3player/files/latest/download" rel="nofollow"><img alt="Download XR3Player" src="https://img.shields.io/sourceforge/dt/xr3player.svg"></a>
[![Total Downloads](https://img.shields.io/github/downloads/goxr3plus/XR3Player/total.svg)](https://github.com/goxr3plus/XR3Player/releases)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![GitHub issues](https://img.shields.io/github/issues/goxr3plus/XR3Player.svg)](https://github.com//goxr3plus/XR3Player/issues)

### Show some love 

<a href="https://patreon.com/preview/8adae1b75d654b2899e04a9e1111f0eb" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a>
<a href="https://www.paypal.me/GOXR3PLUSCOMPANY" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a>

> New in Update 108 ( Huge User Interface Improvements and Bug Fixes )

![screenshot1205](https://user-images.githubusercontent.com/20374208/40893545-9baaadc4-67aa-11e8-80c0-6ff72256591e.png)



### Screenshots

| Login Screen | Main Mode 
|:-:|:-:|
| ![First](https://user-images.githubusercontent.com/20374208/41197020-b5dfe3be-6c58-11e8-87b6-6f592b04bc36.jpg) | ![Sec](https://user-images.githubusercontent.com/20374208/41197021-b603de54-6c58-11e8-8955-689d79753eb0.jpg) |

| DJ Mode | Web Browser 
|:-:|:-:|
| ![First](https://user-images.githubusercontent.com/20374208/41197022-b62635da-6c58-11e8-9988-93acdfb24422.jpg) | ![Sec](https://user-images.githubusercontent.com/20374208/41197023-b64870aa-6c58-11e8-90c4-cb884d3a174a.jpg) |

### Videos

| V.108 | Awesome Tutorial |
|:-:|:-:|
| [![First](http://img.youtube.com/vi/7xYAMcp_fsE/0.jpg)](https://www.youtube.com/watch?v=7xYAMcp_fsE)  | [![Second](http://img.youtube.com/vi/pLug--wWoak/0.jpg)](https://www.youtube.com/watch?v=pLug--wWoak) |

-------------------------------------------------------------------------------------

## Features
- **App**
  - Support fully .mp3
  - Support almost all audio formats through smart converting
  - Chromium Web Browser
  - Full Dropbox access
  - Multiple User Accounts
  - Configurable via multiple settings
  - Advanced Tag Editor
  - File Organizer and Explorer
  - Multiple Libraries/Playlists support
  - System monitor ( CPU , RAM )
   - Audio Effects and Filters
- _**Much more**_
  - _XR3Player is actively developed. More features will come!_
  - Support all audio file formats
  - Support all video file formats


## QUESTIONS
<details>
  <summary>System Requirements</summary>
  <p>
   
    1) At least 4 Cores CPU > 2.0 GHZ CPU Intel or AMD 
     
    2) A good GPU (Graphics Processing Unit) [ It requires graphic power for visualizers ]

    3) At least 4GB DDR3|DDR4 Ram [ Java Programs are known to consume a little bit more RAM ;) ]
  </p>
</details>

<details>
  <summary>License</summary>
  <p>
    https://www.google.com/search?q=GNU+LGPL+3.0&oq=GNU+LGPL+3.0&aqs=chrome..69i57j0.6247j0j4&sourceid=chrome&ie=UTF-8
  </p>
</details>

# How to fork and support this project

To build XR3Player, you will need:

* [JDK 9+]
* [Maven](http://maven.apache.org/) - Version 3.5.3++ recommended

There is are some dependencies that are not on Maven Central ( you can find those .jars on the folder called **localLibraries**) :

**JAVE** and **JAVE(for it i created a repository on github so don't worry)**
**JAVASYSMON** and **JAVASYSMON(for it i created a repository on github so don't worry)**

For them [follow this tutorial to add them to your Local Maven Repository](https://www.mkyong.com/maven/how-to-include-library-manully-into-maven-local-repository/) 

For example (**JAVE**) [Github Repository by GOXR3PLUS](https://github.com/goxr3plus/JAVE) in my computer i do the following :

> mvn install:install-file -Dfile=D:\GitHub\XR3Player\localLibraries\jave-1.0.2.jar -DgroupId=it.sauronsoftware.jave -DartifactId=jave -Dversion=1.0.2 -Dpackaging=jar

```XML
<!-- JAVE -->
<dependency>
	<groupId>it.sauronsoftware.jave</groupId>
	<artifactId>jave</artifactId>
	<version>1.0.2</version>
</dependency>
```

For example (**JAVASYSMON**) [Github Repository by GOXR3PLUS](https://github.com/goxr3plus/javasysmon) in my computer i do the following :

> mvn install:install-file -Dfile=D:\GitHub\XR3Player\localLibraries\javasysmon-0.3.6.0.jar -DgroupId=local.github.goxr3plus -DartifactId=javasysmon -Dversion=3.6.0 -Dpackaging=jar

```XML
<!-- javasysmon -->
<dependency>                                      
	<groupId>local.github.goxr3plus</groupId>     
	<artifactId>javasysmon</artifactId>           
	<version>3.6.0</version>                      
</dependency>                                     
```
---

Follow the above instructions and run ``mvn clean package`` , be sure that you are compiling with Java 9

## About JxBrowser

>XR3Player uses JxBrowser http://www.teamdev.com/jxbrowser, which is a proprietary software, owned by TeamDev Ltd. The use of JxBrowser >is governed by JxBrowser Product Licence Agreement http://www.teamdev.com/jxbrowser-licence-agreement. 
>You may not use JxBrowser separately from XR3Player project without explicit permission of TeamDev Ltd.


## Specs / Open-source libraries:


- [**Ikonli Font Icons packs**](https://aalmiray.github.io/ikonli) Ikonli provides icon packs that can be used in Java applications. Currently Swing and JavaFX UI toolkits are supported.
- [**ControlsFX**](http://fxexperience.com/controlsfx/features/) UI controls and useful API for JavaFX 8.0 and beyond .
- [**JFoenix**](http://www.jfoenix.com/)  JavaFX Material Design Library .
- [**RichTextFX**](https://github.com/FXMisc/RichTextFX) RichTextFX provides a memory-efficient text area for JavaFX that allows the developer to style ranges of text, display custom objects in-line (no more HTMLEditor), and override the default behavior only where necessary without overriding any other part of the behavior.
- [**FX-BorderlessScene**](https://github.com/goxr3plus/FX-BorderlessScene) Undecorated JavaFX Scene with implemented move, resize, minimise, maximise, close and Windows Aero Snap controls.
- [**JavaSysmon**](https://github.com/goxr3plus/javasysmon) Manage OS processes and get cpu and memory stats cross-platform in Java. 
- [**Jnativehook**](https://github.com/kwhat/jnativehook) Global keyboard and mouse listeners for Java .
- [**Sqlite-jdbc**](https://github.com/xerial/sqlite-jdbc) SQLite JDBC Driver .
- [**Commons-Validator**](https://commons.apache.org/proper/commons-validator/) A common issue when receiving data either electronically or from user input is verifying the integrity of the data. This work is repetitive and becomes even more complicated when different sets of validation rules need to be applied to the same set of data based on locale. Error messages may also vary by locale. This package addresses some of these issues to speed development and maintenance of validation rules.
- [**EasyBind**](https://github.com/TomasMikula/EasyBind) EasyBind leverages lambdas to reduce boilerplate when creating custom bindings, provides a type-safe alternative to Bindings.select* methods (inspired by Anton Nashatyrev's feature request, planned for JavaFX 9) and adds monadic operations to ObservableValue.
- [**JSoup**](https://jsoup.org/) Java library for working with real-world HTML. It provides a very convenient API for extracting and manipulating data, using the best of DOM, CSS, and jquery-like methods.
- [**JSON-Simple**](https://github.com/cliftonlabs/json-simple) Java 7+ toolkit to quickly develop RFC 4627 JSON compatible applications
- [**Java-Google-Speech-API**](https://github.com/goxr3plus/java-google-speech-api) J.A.R.V.I.S. Java Speech API: Just A Reliable Vocal Interpreter & Synthesizer. This is a project for the Java Speech API. The program interprets vocal inputs into text and synthesizes voices from text input. The program supports dozens of languages and even has the ability to auto-detect languages!
- [**JAudioTagger**](http://www.jthink.net/jaudiotagger/) Jaudiotagger is the Audio Tagging library used by Jaikoz for tagging data in Audio files.
- [**Java-Stream-Player**](https://github.com/goxr3plus/java-stream-player) Java Advanced Audio Controller Library (WAV, AU, AIFF, MP3, OGG VORBIS, FLAC, MONKEY's AUDIO and SPEEX audio formats ).
- [**JavaFX-Web-Browser**](https://github.com/goxr3plus/JavaFX-Web-Browser) Embeddable or Standalone JavaFX Web Browser.
- [**Mp3agic**](https://github.com/mpatric/mp3agic) A java library for reading mp3 files and reading / manipulating the ID3 tags (ID3v1 and ID3v2.2 through ID3v2.4).
- [**JAVE**](http://www.sauronsoftware.it/projects/jave/) The JAVE (Java Audio Video Encoder) library is Java wrapper on the ffmpeg project

Ignore this
[![Build Status](https://travis-ci.org/goxr3plus/XR3Player.svg?branch=master)](https://travis-ci.org/goxr3plus/XR3Player)
