# Awesome Assitivetech [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of 😎 awesome Assistive Technology frameworks and tools to help you develop your AT tool/system. *note: this is for tools rather than end products. For those see [OpenAssistive](https://openassistive.org/)*


- [Awesome Assistive-Tech](#awesome-assistivetech)
    - [AAC (Alternative & Augmentative Communication](#aac)
    - [Symbols](#symbols)
    - [Word/Letter Prediction](#word-prediction)
    - [Speech Recognition](#speech-recognition)
    - [Speech Synthesis](#speech-synthesis)
    - [Head/Face tracking](#headface-tracking)
    - [EyeGaze](#eyegaze)
    - [Switch Scanning](#switch-scanning)
        - [Reading material](#reading-material)
        - [Scanning on the web](#scanning-on-the-web)
- [Support](#support)
    - [Hackathons](#hackathons)
    - [Email Lists](#email-lists)
    - [AT Engineering Organisations](#AT-engineering-organisations)
- [Contributing](#contributing)

- - -

## AAC

*Tools to help you make a better Augmentative & Alternative Communication system* 

* [OpenBoardFormat](http://www.openboardformat.org). Suggested format for open source language layouts/packages for AAC systems. See also the [OBF Gem](https://github.com/CoughDrop/obf) - which works with this. 
* [AAC-Shim](https://github.com/CoughDrop/aac_shim) - a simple helper method for helping web apps that want to support being embedded inside an AAC system. Check out the [demos](https://tools.openaac.org/demo.html). 

## Symbols

*APIs and resources to support access to symbols*

* [Open Symbols](https://www.opensymbols.org/). Provides api and web front end to search through all open source symbol sets. Powers coughdrop
* [Symboliser API](https://symboliser.commtap.org/commtap-symbols-server-api/). From Commtap. Adds in synonyms and variants on top of the normal symbol information 

## Word Prediction 

*APIs and code samples to integrate word prediction into your system*

* [Asterics-Predictionary](https://github.com/asterics/predictionary). JavaScript dictionary-based word prediction library with self-learning abilities.
* [Imagineville Prediction API](https://api.imagineville.org/docs). Keith Vertanen's prediction API. 
* [Presage](http://presage.sourceforge.net). C++ based prediction engine, with Python bindings available (Python binding [doc](https://sourceforge.net/p/presage/presage/ci/master/tree/doc/python_binding.txt) and for an example see [this example](https://github.com/AceCentre/MorseWriter/blob/master/MorseCodeGUI.py#L21))

## Speech Recognition

*Tools to aid Speech Recognition*

* [Python Speech Recgonition](https://pypi.python.org/pypi/SpeechRecognition/) - Library for performing speech recognition, with support for several engines and APIs, online and offline.

## Speech Synthesis

*Tools to aid/do speech synthesis*

* [eSpeak](http://espeak.sourceforge.net) - compact open source software speech synthesizer for English and other languages, for Linux and Windows 
* [festival](http://festvox.org/festival/) - multi-lingual speech synthesis workbench that runs on multiple-platforms offering black box text to speech, as well as an open architecture for research in speech synthesis
* [flite](http://www.speech.cs.cmu.edu/flite/) -  small, fast run-time synthesis engine developed at CMU and primarily designed for small embedded machines and/or large servers. Flite is designed as an alternative synthesis engine to Festival for voices built using the FestVox suite of voice building tools. 
* [QtSpeech](https://github.com/yshurik/qtspeech) -  a cross-platform library based on Qt to provide common cross-platform API to access and use system TTS (Text-to-Speech) engines on platforms as Windows (SAPI), Mac (SpeechSynthesis) and Linux (Festival).
* [Talkify](https://github.com/Hagsten/Talkify) - A javascript text to speech (TTS) library. Originally from and used by https://talkify.net. Uses https://manage.talkify.net/ as a backend. 
* [Extra TTS](https://github.com/CoughDrop/extra-tts) - Used to offer additional speech synthesis engines in cordova apps.
* [Acapela for Electron](https://github.com/CoughDrop/acapela) - Get acapela voices working on Electron apps. 
* [ResponsiveVoice](https://responsivevoice.com) - Javascript based TTS - check site for pricing
* [Browser Speech Synthesis](https://browserspeechsupport.me) - which browsers support which voices. 

## Head/Face tracking

*Tools to face tracking*

* [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace) - an open source facial behavior analysis toolkit. See [OpenFaceIOS](https://github.com/FaceAR/OpenFaceIOS) for an iOS version.
* [Cordova-Face](https://github.com/open-aac/cordova_face) - ARkit based head tracking and basic eye tracking for Cordova platforms. Currently focused on iOS. 


## Eyegaze 

*Small and big projects to aid/support eyetracking*

* [GazeLinger](https://github.com/CoughDrop/gazelinger) - Node module to listen to eye gaze events from the eye-tracking libraries
* [EyeTab](https://github.com/errollw/EyeTab) - a 3D model-based gaze tracker - designed for Microsoft Surface.
* [GazePointer](https://github.com/MSREnable/GazePointer) -  SDK which provides an abstraction layer for interacting with a number of eye trackers. The current implementation provides support for Tobii EyeX. 

## Switch Scanning

*Using switches and scanning*

### Reading material

* [Switch Access to Technology](https://acecentre.org.uk/resources/switch-access-technology/) - a comprhensive guide to scanning and the various patterns out there. 

### Scanning on the web 

* [Switch Access for Webpages](http://leifcr.github.io/switch_access/) - is a coffeescript that enables switch/keyboard control for navigating a webpage for AAC users. Nice demos. Well implemented. 
* [switchScanJS](https://github.com/mikethrussell/switchScanJS) - a jQuery based implementation with auto-scanning. 
* [AAC-Shim](https://github.com/CoughDrop/aac_shim) - a simple helper method for helping web apps that want to support being embedded inside an AAC system. Check out the [demos](https://tools.openaac.org/demo.html). 


# Support 

## Hackathons

* [ATHack](http://assistivetech.mit.edu/athack/). Boston/MIT based hackathon pairing indviduals with disabilities with hackers
* [Hackcessible 2018](https://www.hackcessible.org). Sheffield, UK hackathon. 

## Email Lists

* [AT-Forum](http://assistive-technology.996335.n3.nabble.com) - The [RESNA](http://www.resna.org) (Rehabilitation Engineering Society for North America) forum
* [AssistTech](https://www.jiscmail.ac.uk/cgi-bin/webadmin?A0=ASSISTECH) - UK based list with a number of AT professionals from an Clincial Science/Engineering Background
* [Access Group](http://ataccessgroup.org.uk) - UK based group of Occupational Therapists and Engineeers finding solutions for people to access electronic equipment
* [Communication Maters AACForum](https://www.communicationmatters.org.uk/page/aac-forum) - UK Forum for the UK Chapter of ISAAC (International Society of AAC)

## Email / News announcements 

* [AACinfo](http://aacinfo.email) - a monthly-ish email which lists new products, technologies and strategies in AAC. Users contribute to the site and Ace centre edit it. 

## AT Engineering Organisations

* [Tetra Society of North America](http://www.tetrasociety.org) - Volunteer engineers across North America assisting people with disabilities
* [REMAP](http://remap.org.uk) - Volunteer engineers across the UK assisting people - similar to Tetra 


- - -

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/openassistive/awesome-assitivetech/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/openassistive/awesome-assitivetech/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **20**.
