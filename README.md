# flappyPirate
Flappy Bird clone with pirate graphics and voice control

--Initially forked from https://github.com/nebez/floppybird/ - Big Thanks

NOTE
-----------
Please note that due to timeframe limitations html getUserMedia() (https://developer.mozilla.org/en-US/docs/Web/API/Navigator/getUserMedia) was used which is a deprecated function, you will need to run the game either on a secure server or disable security in chrome, otherwise the game won't be able to process audio.
You would still be able to control the game with the spacebar.

#TODO: Convert the function to MediaDevices.getUserMedia() (https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)


Original Readme:

Floppy Bird
=========
Initially, I wanted to try recreating Flappy Bird in HTML5, using a canvas and recycling the assets from the old game.

What I did instead is something way more primitive. This project uses nothing but good ol' div's for all the objects and graphics, will scale perfectly on almost any screen (mobile and desktop), is terribly unoptimized, laggy, and isn't nearly as fast as it would've been if I had just used a canvas instead. But here it is!

Live App
------------
Check out a live preview of it over here:
http://nebez.github.io/floppybird/

Cool Stuff
---------
*Some cool things other people have done with the code. Let me know about your projects and I'll link it here*
https://github.com/rukmal/FlappyLeapBird - **[Rukmal](http://rukmal.me/)** integrated LeapMotion Controller functionality! Check out his website, he's done some cool stuff.
http://chrisbeaumont.github.io/floppybird/ - **[@chrisbeaumont](https://github.com/chrisbeaumont)** made an awesome auto-pilot, check it out
http://www.lobe.io/flappy-math-saga/- **[@tikwid](https://github.com/tikwid)** made a really cool version designed to teach you times tables. really cool.
http://dota2.cyborgmatt.com/flappydota/ - flappy dota, this one is really cool.
http://tippy.gochiusa.net/ - Japanese anime inspired floppybird.

Credits
------
**[@aregowe](https://github.com/aregowe)** for optimizing all the assets

Notice
=====
The assets powering the visual element of the game have all been extracted directly from the Flappy Bird android game. I have only done the coding, not designed the visual elements.
I do not own the assets, nor do I have explicit permission to use them from their creator. They are the work and copyright of original creator Dong Nguyen and .GEARS games (http://www.dotgears.com/).
I took this Tweet (https://twitter.com/dongatory/status/431060041009856512 / http://i.imgur.com/AcyWyqf.png) by Dong Nguyen, the creator of the game, as an open invitation to reuse the game concept and assets in an open source project. There is no ill intention to steal the game, or claim it as my own. This is merely a recreation for fun.
If the copyright holder would like for the assets to be removed, let me know!


License
=====
Copyright 2014 Nebez Briefkani

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
