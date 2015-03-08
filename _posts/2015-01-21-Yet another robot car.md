---
layout: post
title: Yet another robot car
---

### Motivation

In my senior year of University I was programming a [Darwin-Op](http://www.robotis.com/xe/darwin_en) robot. It was a really nice and fun experience. After my graduation I feel a little dissapointed because I had to be sepparated from my first chilbot :(. But after a while I found a solution: I built my own baby bot, actually two.

### Having fun with robots

First I spent some time looking where to buy the necessaries robot parts. The best option that I found to my budget was [Aliexpress](http://www.aliexpress.com). 


Additionally to my ChipKit Max32 board (a pretty nice gift I received while I still was at University). I bought these parts:

* 1 Arduino UNO board
* 2 Bluetooth modules
* 2 Ultrasonics sensors
* 1 Full H bridge
* 4 Line Sensors
* 4 Rechargeable Batteries 18650
* 2 Battery Holders
* Dupont wires, screws and nuts.
* 1 Caster wheel (I prefer the spanish name: rueda loca!)
* 1 Robot car chassis
* 1 Robot tank chassis

With the above parts I finally built a robot car and a robot tank. There are a lot resources about the assembling process, maybe I going to write my own guide later.

### Robot car

It is controlled by the Arduino board.  You can watch the code that operates it visit  [Robotcar-Arduino](http://ozos.github.io/robotcar-arduino) project. Some pictures and video:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

![Car front view](/public/images/car1.jpg)

![Car front view](/public/images/car2.jpg)

### Robot tank

It is controlled by the Arduino board.  You can watch the code that operates it visit  [Robotcar-Arduino](http://ozos.github.io/robotcar-chipkit) project. The code had to be modified because Chipkit provides a very old library who lacks of functionality required by the original project. Some pictures and video:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

![Car upper view](/public/images/tank1.jpg)

![Car front view](/public/images/tank2.jpg)

### ArduinoRC

A android app  that allows to control the robots over bluetooth. For more information about this project visit  [ArduinoRC](http://ozos.github.io/arduinoRC) project. Some screenshot: 

![Main Activity](/public/images/arduinoRCmain.jpg)

![Turn on Bluetooth](/public/images/arduinoRCbton.jpg)

![Device scan](/public/images/arduinoRCsearch.jpg)

![List of devices](/public/images/arduinoRClist.jpg)



Thanks for reading!
