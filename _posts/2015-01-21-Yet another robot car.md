---
layout: post
title: Yet another robot car
---

### Motivation

In my senior year of University I was programming a [Darwin-Op](http://www.robotis.com/xe/darwin_en) robot. It was a really nice and fun experience. After my graduation I felt a little disappointed because I had to be separated from my first childbot :(. But after a while I found a solution: I built my own baby bot, actually two.

### Having fun with robots

First, I spent some time looking where to buy the necessary robot parts. The best option I found on my budget was [Aliexpress](http://www.aliexpress.com). 


I bought these parts:

* 1 Arduino UNO board
* 2 Bluetooth modules
* 2 Ultrasonic sensors
* 1 Full H bridge
* 4 Line Sensors
* 4 Rechargeable Batteries 18650
* 2 Battery Holders
* Dupont wires, screws and nuts.
* 1 Caster wheel (I prefer the Spanish name: rueda loca!)
* 1 Robot car chassis
* 1 Robot tank chassis
Extra:
* ChipKit Max32 board (a pretty nice gift I received while I still was at University). ***
With the above parts I finally built a robot car and a robot tank. There are a lot resources about the assembling process, I might write my own guide one day.

### Robot car

It is controlled by the Arduino board.  To watch the code that operates it, visit  [Robotcar-Arduino](http://ozos.github.io/robotcar-arduino) project. Video and pictures:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

![Car front view](/public/images/car1.jpg)

![Car front view](/public/images/car2.jpg)

### Robot tank

It is controlled by the Arduino board.  To watch the code that operates it, visit  [Robotcar-Arduino](http://ozos.github.io/robotcar-chipkit) project. The code had to be modified because Chipkit provides a very old library that lacks the functionality required by the original project. Video and pictures:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

![Car upper view](/public/images/tank1.jpg)

![Car front view](/public/images/tank2.jpg)

### ArduinoRC

A android app  that allows to control the robots over bluetooth. For more information about this project visit  [ArduinoRC](http://ozos.github.io/arduinoRC) project. Some screenshots: 

![Main Activity](/public/images/arduinoRCmain.jpg)

![Turn on Bluetooth](/public/images/arduinoRCbton.jpg)

![Device scan](/public/images/arduinoRCsearch.jpg)

![List of devices](/public/images/arduinoRClist.jpg)



Thanks for reading!
