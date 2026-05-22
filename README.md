# Awesome Synthux Community

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

![Synthux image](SynthuxAcademy2024-500.png)

> [!IMPORTANT]
> This is an unofficial initiative contributed by the community. Readers are encouraged to comment and contribute.

## Goal / What is this list? / Why is it "awesome"?

**To share anything of interest related to Synthux and the mission of learning, building and programming synthesizers.**

**_Awesome_** lists are a repository, a collection of usefull links about a certain topic. Search GitHub and you'll find pages ranging from [puredata](https://github.com/MikeMorenoDSP/awesome-puredata) to [pen ploters](https://github.com/beardicus/awesome-plotters).

### Synthux by the community for the community - this list is unoffical

In the open‑source world, an awesome list is usually:
- community‑curated
- broad in scope
- opinionated
- not “official documentation”

→ Hosting this inside the Synthux GitHub account might be counterintuitive, but the idea of keeping it here ensures it's easier to find and reach a the whole community without a direct risk of loosing access to the original.

Community members can apply for maintenance roles, or you could simply add links or suggestions via a pull request or making an "issue". (#todo insert direct issue link)

Synthux Academy is part of Stichting PTM Academy - a registered non-profit organization based in Rotterdam, Netherlands. It's founder Roey Tsemah has started the organization and community for anyone looking to learn and connect with fellow synth-nerds. The community ranges from music maker enthousiasts, DIY makers as well as professionals. The common goal is to share our love for music and technology.

Synthux has a few of their own synths, most of which are made available as DIY kits and their source code is open source. There's a very open culture, building on the vast amount of available content in the space of music technology.

While most Synthux kits come with the Electrosmith Daisy Seed microcontroller, the Simple PCB’s do fit other microcontrollers as well.

### Synthux Community invite and code of conduct

- [join the community](https://www.synthux.academy/join) by signing up via the official website (free)
- The Synthux community adheres to the [Berlin Code of Conduct](https://berlincodeofconduct.org/).
- Contributions welcome. Add links through pull requests or create an issue to start a discussion, or join the conversation on Discord.

---

## Contents

- [Goal / What is this list?](#goal--what-is-this-list--why-is-it-awesome)
- [Official Synthux links](#official-synthux-links)
- [Community submitted code and hardware mods](#community-submitted-code-and-hardware-mods-for-synthux-instruments)
  - [General — applicable to all Simple / Daisy](#general---applicable-to-all-simple--daisy)
  - [Simple Fix](#simple-fix)
  - [Simple Touch 2](#simple-touch-2)
  - [Simple Designer](#simple-designer)
- [Documentation / guides (Electrosmith Daisy)](#documentation--guides-electrosmith-daisy)
- [Electrosmith — Daisy](#electrosmith---daisy)
  - [Arduino / DaisyDuino](#arduino---daisyduino)
  - [General Arduino related](#general-arduino-related)
  - [CPP / C++](#cpp--c)
  - [Plugdata](#plugdata)
- [Social](#social)
- [General hardware info](#general-hardware-info)
  - [DIY tips / tricks](#diy-tips--tricks)
  - [Components for Simple PCBs](#components-for-simple-pcbs)
  - [Manufacturing](#manufacturing)
  - [3D Software](#3d-software)
  - [Circuit & PCB Design Software](#circuit--pcb-design-software)
  - [PCB Design resources / lessons and best practices](#pcb-design-resources--lessons-and-best-practices)
  - [Design, UI, UX](#design-ui-ux)
  - [Laser cutting](#laser-cutting)
- [Synthux community members](#synthux-community-members)
- [Sound and music — made with Synthux related gear](#sound-and-music---made-with-synthux-related-gear)

---

## Official Synthux links

[synthux.academy](http://www.synthux.academy/) - main website

[synthux.academy/shop](http://synthux.academy/shop) - Beginner friendly kits with video course included

[simple resources](https://www.synthux.academy/simple-synth) - instrument firmware downloads and tutorials for Simple Instruments. Touch 2, Simple Designer and Simple Fix.

[Synthux GitHub](https://github.com/Synthux-Academy) - official Synthux Github with all the official firmware and shared hardware files

[Discord community and newsletter](https://www.synthux.academy/join) - where the community comes together to share code, ask and offer help, show off and find like minded synth-heads.

---

## Community submitted code and hardware mods for Synthux instruments

Synthux instruments are genuinely fun to hack on. Simple Touch and Audrey II have gotten new looks, extra jacks, and all kinds of personal touches. Simple Fix is a popular first step before people go off and build something entirely their own. Everyone brings their own tools, parts, and ideas — and that's kind of the point.

### General — applicable to all Simple / Daisy

#### troubleshooting 
- #todo

[Expanded pins list / spreadsheet with Synthux numbering](https://docs.google.com/spreadsheets/d/1xtg_s1tk8tm-6qNkBLFc6V1L_Mpmu-PCOvv7qEyr9mU/edit?usp=drivesdk) - made by jonwtr, living document, different tabs, handy to pinpoint pins of Daisy and their corresponding numbers and functions in Synthux hardware and code.

[Electrosmith libDaisy pinout list](https://github.com/electro-smith/libDaisy/blob/master/doc/Daisy_Seed_Rev4_Pinout.csv) - CSV pinout table for Daisy Seed Rev4

---

### Simple Fix

[Official Synthux YouTube channel “Fix” query](https://www.youtube.com/@SynthuxAcademy/search?query=fix) - search query with “fix” on the Synthux academy channel, spot the 25 min video 

---

### Simple Touch 2

#### Code / instruments

[SimplePlaits](https://github.com/JorgeVelez/TallerSimple/tree/main/SimplePlaits) - Mutable instruments Plaits by Jorge Velez

- `.bin` shared; no code (yet); [discord thread](https://discord.com/channels/802197755442626590/1252740022755528775/135310798104218845)

[Selfdistort Touch](https://github.com/jonwaterschoot/Synthux-Simple-Touch-Plugdata/tree/main/FX/selfdistort_touch) - Selftriggering distortion FX - by jonwtr - inspired by Audrey, can function as a regular distortion or as a droning fx. Made with plugdata - patch and instructions available.

- [`.bin` shared; code / pd patch on Github](https://github.com/jonwaterschoot/Synthux-Simple-Touch-Plugdata/tree/main/FX/selfdistort_touch); [demo](https://www.youtube.com/watch?v=csmBTfaORss) video YouTube; [discord thread](https://discord.com/channels/802197755442626590/1359248570913394829)

[FM BleepBloop](https://github.com/jonwaterschoot/Synthux-Simple-Touch-Plugdata/tree/main/FX-Instruments/FM_bleepbloop_touch) - randomized sequencer for a complex FM oscillator Made with plugdata - patch and instructions available. - by jonwtr

- [`.bin` shared; code / pd patch on Github](https://github.com/jonwaterschoot/Synthux-Simple-Touch-Plugdata/tree/main/FX-Instruments/FM_bleepbloop_touch); [discord thread](https://discord.com/channels/802197755442626590/1393384183602086020)

#### Hardware

#### Simple Touch case

[Simple Touch case - markotardito](https://discord.com/channels/802197755442626590/1249745829053468692/1250867297728462968) - shared on [Synthux Discord](https://discord.com/channels/802197755442626590/1249745829053468692/1250867297728462968) - based on design for Plinky

[Synthux-Simple-Touch-2-case](https://github.com/jonwaterschoot/Synthux-Simple-Touch-2-case) - jonwtr with and without bottom, holes at back for TRS CV jacks - based on design from markotardito

- discord discussion thread

#### CV / Clock / mods

[Clock sync](https://discord.com/channels/802197755442626590/1249745829053468692) - first thread on the Synthux discord on adding clock and or CV to Simple Touch

[PCB breakout - battery + CV + clock + midi](https://discord.com/channels/802197755442626590/1379746221543129149) - thread on Discord to build a breakout, just a concept.

---

### Simple Designer

A few of the Synthux and community made instruments are made on top of the Designer PCB, Audrey is probably the most spread and officially sold in the Synthux shop. Therefore Audrey has it’s own section.

[simple-front-face-midi](https://github.com/lucblender/simple-front-face-midi) - a PCB front panel for the simple kit with midi - by discord user helixbyte - [discord thread](https://discord.com/channels/802197755442626590/1039072802956918844/1051486326840623244)

[Simple Canvas](https://github.com/Synthux-Academy/simple-designer-instruments/tree/main/official/canvas) - The Canvas is a cordless patchable West Cost Synthesizer. This synthesizer is born from a collaboration with the Synthux Academy. Its design is inspired by the famous Easel by Buchla. design in coöperation with community member Helixbyte

#### Audrey (II)

Audrey was first shared / made as a diy project on top of the Simple Designer PCB board. Later Synthux started selling the updated kit and standalone unit.

The code of version one and two is the same, the main difference is that V2 has a dedicated enclosure and front plate option.

#### Audrey hardware mods

[Gate input, audio input and other Audrey modifications](https://discord.com/channels/802197755442626590/1366503223124561983/1366503223124561983) - Discord thread - by Bruce

[Adding Gate switch to the Audrey II](https://discord.com/channels/802197755442626590/1351119656009863259) - Discord thread - by wireheadinstruments

#### Audrey Case / Looks

[Black Limba tilted stand for Audrey II](https://discord.com/channels/802197755442626590/1390880501782413492) - Discord thread - by Nick "Walker" Grimshaw

[Black walnut case for Audrey II](https://discord.com/channels/802197755442626590/1383964174429851688) - Discord thread - by faasdnb

[Custom skin: Feedback Gardenscapr](https://github.com/jonwaterschoot/Feedback-Gardenscpr-for-Synthux-Audrey-II) - GitHub - Custom top plate, lasercut case and 3d printed knobs built on top of the Synthux Designer Simple kit - files shared - by jonwtr

[Audrey II 3D Printed Case](https://discord.com/channels/802197755442626590/1353943474998743140/1355504016129527878) - Discord thread - .stl shared - by kurt

[Just in case … bamboo enclosure](https://discord.com/channels/802197755442626590/1350821391401877575) - Discord thread - by KHAGEmusik

---

## Documentation / guides (Electrosmith Daisy)

Synthux instruments are mostly made with **Daisy**, though other boards can fit the Simple PCB's. Therefore some info or guides may be in full about Synthux, some partly.

Note Synthux also has paid-for courses (and/or included with bying kits). Do check out the official website for more info. Here we're trying to link to freely available info.

Daisy can be programmed with **Arduino**, **CPP** and **Plugdata** (puredata), **Max** (oopsy)

Some guides will have info about hardware and adding circuits, where possible mention this.

---

## Electrosmith - Daisy

[Electrosmith](https://electro-smith.com/) - official website

[Daisy Forum](https://forum.electro-smith.com/) - Forum run by Electrosmith ranging topics about all their products 

[Daisy Discord Server](https://discord.gg/ByHBnMtQTR) - contains useful topics from troubleshooting hardware and software to showcases

[Daisy Support Site](https://daisy.audio/) - the main portal linking to documentation for hardware and software, community and the shop

[Daisy Web Programmer](https://flash.daisy.audio/) - web based tool to program the Daisy microcontroller (simple blink test; examples; upload `.bin`; set the bootloader)

[Electrosmith YouTube Channel](https://www.youtube.com/@electrosmithco) - official video tutorials and hardware showcases

[Daisy Pinout Table (libDaisy Docs)](https://github.com/electro-smith/libDaisy/blob/master/doc/Daisy_Seed_Rev4_Pinout.csv) - CSV pinout reference for Daisy Seed Rev4

[Daisy Bootloader (libDaisy Docs)](https://github.com/electro-smith/libDaisy/blob/master/doc/md/_a7_Getting-Started-Daisy-Bootloader.md) - guide for setting up and using the Daisy bootloader

---

### Arduino - DaisyDuino

DaisyDuino is very similar to the library for C++, libDaisy, though there are differences, and are not interchangeable.

Note that it is also possible to use e.g. VSCode to program Arduino’s - though following the most tutorials you’ll use the dedicated Arduino IDE. Follow the guidelines to setup your environment as you’ll need to 1: install the **STM32CubeProg**, and 2: install the official DaisyDuino library from within the IDE.

[arduino.cc](http://arduino.cc) - main website

[Arduino IDE](https://www.arduino.cc/en/software/#ide) - download the official Arduino software

[Arduino setup instructions from Electrosmith](https://daisy.audio/tutorials/arduino-dev-env) - Note that uploading / compiling and flashing with Arduino to Daisy will require the additional steps laid out in this guide

[Zadig Driver](https://www.notion.so/PD-Daisy-docs-meeting-notes-17a26099464b80b5ac96e25f4994e508?pvs=21) - Reset instructions (Windows Only)

[Synthux Simple Fix](https://github.com/Synthux-Academy/simple-fix-instruments) - DaisyDuino Arduino based instruments

[Synthux Simple Touch DaisyDuino](https://github.com/Synthux-Academy/simple-touch-instruments/tree/main/daisyduino) - note that the parent folder also contains cpp libDaisy code

- All the Simple Touch 2 instruments are made with Arduino code split into handy blocks. - you will also find the `.bin` versions you could upload with the webprogrammer.

---

### General Arduino related

[Getting Started with Arduino IDE 2](https://docs.arduino.cc/software/ide-v2/tutorials/getting-started-ide-v2/) - An introduction to the software and workflow

---

### CPP / C++

[Electrosmith documentation](https://daisy.audio/tutorials/cpp-dev-env/) - Toolchain and VSCode installation

[libDaisy Electrosmith documentation](https://daisy.audio/software/) - libDaisy is a C++ hardware support library for the Electrosmith Daisy platform.

[libDaisy Github](https://github.com/electro-smith/libDaisy) - official Electrosmith repository

---

### Plugdata

Plugdata is a visual programmer based on PureData; though patches made with this method cannot be uploaded as is, HVCC is integrated into Plugdata; it converts pd to compiled code that can be uploaded to Daisy (as well as other formats from full plugins to game related code). HVCC is the Heavy compiler maintained by one of the members who have joined the community: dreamer, aka Wasted Audio. 

[Plugdata.org](http://Plugdata.org) - official plugdata website, stable and nightly releases

[hvcc](https://wasted-audio.github.io/hvcc/) - Heavy compiler collection — a Python-based dataflow audio programming language compiler that generates C/C++ code and a variety of specific framework wrappers.

- [Getting Started (hvcc docs)](https://wasted-audio.github.io/hvcc/getting-started/)
- [Patching Guide & Known Limitations (hvcc docs)](https://wasted-audio.github.io/hvcc/getting-started/#patching-guide)
- [Plug Data – Compiling Patches with heavy](https://plugdata.org/docs/CompilingPatches.html)
- [Plug Data and Heavy - Wasted Audio YouTube Channel](https://www.youtube.com/@Wasted-Audio)
- [Supported Vanilla Objects (hvcc docs)](https://wasted-audio.github.io/hvcc/reference/supported_objects/)
- [Unsupported Vanilla Objects (hvcc docs)](https://wasted-audio.github.io/hvcc/reference/unsupported_objects/)
- [Daisy Section in the hvcc docs](https://wasted-audio.github.io/hvcc/generators/daisy/)

[Daisy Seed and plugdata](https://jasperkempf.github.io/DIY-Synth-DaisySeed-and-PlugData/) - guide by **Jasper Kempf** that goes over all the basics, useful for all Daisy related designs

[Beginners guide to programming Daisy with Plugdata](https://jonwaterschoot.github.io/plugdata-daisy-simple/) - unfinished guide started by jonwtr as he was learning plugdata while using Synthux boards

- can be applied to general Daisy seed - geared towards Simple boards and Simple Touch
- contains examples on how to implement components like potentiometers and switches

[Hardware test patches](https://github.com/jonwaterschoot/Synthux-Simple-Touch-Plugdata/tree/main/HW_test-patches) - a list of simple troubleshooting patches to test components (also contains `.bin` files that can be used for non PD specific testing)

[Awesome Puredata](https://github.com/MikeMorenoDSP/awesome-puredata) - list of Pure Data documentation and other useful resources

#### Pure Data / Plug Data lessons

[QCGInteractiveMusic - Realtime Music and Sound with Pure Data Vanilla](https://youtu.be/SLx7kjuFheY?si=Al6hmUHhqnK8-pkg) - YouTube series

[Sound Codex - Plug Data Introduction](https://www.youtube.com/watch?v=EoOEZYn4xdA) - YouTube intro

[Sound Simulator - Pure Data Tutorial Series](https://youtu.be/1o5Wasmd8yU?si=8Cyid-OEyHV6KcKr) - YouTube series

---

## Social

### Discord servers

[Join the Synthux community and Discord server](https://www.synthux.academy/join) - by signing up via the official website (free) 

[Daisy electrosmith](https://discord.gg/ByHBnMtQTR) - official Electrosmith Discord server

[HVCC](https://discord.gg/fmxJveg) - The heavy hvcc compiler for Pure Data patches.

---

## General hardware info

### DIY tips / tricks

#### Soldering

Roey has a few tips on soldering in these videos:

[Overview of tools to get started](https://youtu.be/2UCG4jI6atU?si=QVxos6U0raJAYQDd) - learn about basic tools like the soldering gear

[Soldering Simple Fix](https://youtu.be/YEbMJKAfjao?t=215&si=qbOT8vYWN7qf_taG) - Demo of soldering Daisy and the components like jacks

[Soldering Simple Designer](https://youtu.be/3HX0H36eN_A?si=NKhLZckNGSWlJS0-) - a demo of soldering components onto the Simple Designer PCB

#### Other tutorials

[How to get perfect solder joints](https://youtu.be/jz67KgHzXVw?si=X0Zl9I1Bv41mLVkE) - another great rundown on soldering technique

[Adafruit soldering guide](https://learn.adafruit.com/adafruit-guide-excellent-soldering/tools) - a written guide with clear illustrations 

Soldering + electronics tools:

- Soldering iron:
    - [Pinecil](https://pine64.org/documentation/Pinecil/) - a small but extremely powerful iron, it has a small screen with customizable settings, you will need an additional power source, either a strong USB charger (USB-C PD65W, 3.25A, 20V) or a DC barrel supply up to 24V. (check docs)
    - [Weller WE1010](https://www.weller-tools.com/eu/gb/industrial-soldering/products/soldering-stations/we1010-set-230v) - a complete kit with a station, soldering iron and safety rest
- flux
- soldering tin
- desoldering: wick -
- desoldering pump
- multimeter
- helping hands
    - [omnifixo](https://omnifixo.com/en-eu/products/omnifixo-m4-makers-third-hand) - third helping hand, has some nifty features like option to connect power through or isolate, uses clamps and magnets.

### Components for Simple PCBs

- list of components compatible with Synthux PCB's
- sensors included in Daisy libraries
- link to Electrosmith docs
- non supported / custom components - e.g. the faders that come in the kits can be used in a ‘hacked’ way

### Manufacturing

### 3D Software

[FreeCAD](https://www.freecad.org/) - is an open-source parametric 3D modeler made primarily to design real-life objects of any size.

[Blender](https://www.blender.org/) - open source 3D modeling and animation tool, though not CAD, can be used to create STL and other physical modeling formats, plugins with CAD like abilities exist.  

### Circuit & PCB Design Software

[KiCad](https://www.kicad.org/) - is a free software suite for electronic design automation (EDA). It facilitates the design and simulation of electronic hardware for PCB manufacturing.

[CircuitMaker](https://circuitmaker.com/) - free-to-use schematic and PCB design tool for the Open Source Hardware community.

[Falstad](https://www.falstad.com/circuit/) - Circuit Simulator applet

[Cirkit Designer](https://www.cirkitstudio.com/) - online free breadboarding tool (they have Daisy as a component) - Design, Simulate and Prototype Circuits. They have a built in AI assistant.

[Fritzing](https://fritzing.org/) - is an open-source hardware initiative, no longer a free (gratis) download, still available via GitHub

[Tinkercad](https://www.tinkercad.com/) - available for free with account - by Autocad; contains a breadboard, circuit and simple 3D application

[circuito](https://www.circuito.io/) - online app that generates instant and accurate schematics and code for your electronic circuit.

### PCB Design resources / lessons and best practices

- list

### Design, UI, UX

[Front Panel UI Kit](https://discord.com/channels/802197755442626590/1044290461772304424) - Discord thread - Affinity Designer Template + SVG - by felix | mindful devices

### Laser cutting

[Makercase](https://www.makercase.com/#/) - MakerCase is a web-based application for designing boxes or project cases for laser cutters and CNC routers. (options to add kerf, fingers, etc …)

[Boxes.py](https://boxes.hackerspace-bamberg.de/?language=en) - plain boxes and other things like shelving, stands, …  an Open Source box generator written in Python. It features both finished parametrized generators as well as a [Python API](https://hackaday.io/project/10649-boxespy) for writing your own. 

---

## Synthux community members

- **Roey Tsemah** - Founder of Synthux 
  - main force behind all of Synthux, including hardware, software, webdesign, video, tutorials, courses, ... 
  - musician, designer, teaching product design in academies in The Netherlands. 
  - [Personal Instagram](https://www.instagram.com/roey.tsemah) - 
  - [Official Synthux Instagram](https://www.instagram.com/synthux.academy) - own content and reposts of community content
  - [TravellingSynths YouTube](https://www.youtube.com/c/TravellingSynths) - personal synth and music channel


- **Nick Donaldson** - made the original Audrey code, main developer for the Spotykach hardware
  - currently at [WMD](https://wmdevices.com/) (modular synthesizers, eurorack and guitar pedals)
  - made his own line of eurorack gear: 
    - [Infrasonic Audio currently indefinetly on hold](https://infrasonicaudio.com/blogs/news/discontinuing-all-modules)
    - [Interviexw on electrosmith website "Developer Profile: Infrasonic Audio (Nick Donaldson)"](https://electro-smith.com/blogs/seeds-n-circuits/daisy-in-the-wild-warp-core)

- **Vlad / Vladislav Litvinenko / aka Bleeptools** - worked on Simple Touch, author of all the official Simple Touch firmwares (except Audrey Touch), author of the official firmware for Spotykach. 
  - Spotykach - a collaboration between Roey Tsemah and Vlad
  - [Bleeptools on Instagram](https://www.instagram.com/bleeptools)


- **Helixbyte** - worked on Canvas, one of the first big projects built on top of the Simple Designer board.

- **Conatus Modulari / Fabio Bartali** - musician and designer
  - Active meber at the Synthux headquarters 
  - Spotykach - manual design and allround help in soldering, building, testing etc.
  - [Conatus Modulari on YouTube](https://www.youtube.com/@ConatusModulari) - jams and soundscapes
  - [Conatus Modulari on Instagram](https://www.instagram.com/conatusmodulari)


Spotykach prerelease supporters 
- 
- 

## Sound and music - made with Synthux related gear:

- list
- list


