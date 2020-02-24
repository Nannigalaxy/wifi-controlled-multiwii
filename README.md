# wifi-controlled-multiwii
Controlling Arduino based MultiWii using esp8266

Recently I made Adruino based drone <br>
Arduino nano with mpu6050 as flight controller<br>
esp8266-01 for controlling drone

Instead of traditional radio control, esp8266 can be used as cheap alternative(No to fancy drone stunts and lot of features).
I came across this https://www.instructables.com/id/Wifi-PPM-no-App-Needed tutorial by <b>Andi23456 (Andi MÃ¶senlechner)</b>, using PPM mode for drone control.
For detailed instructions on how to bulid esp8266 contoller please follow above link.

<h1>Setting PPM out pin</h1>

<ul>Default output pin 5, which is for other than esp-01</ul>
<ul>For esp-01 set within pin 0 to 2 (pin 3 for Debug)</ul>

<h1>MultiWii Flight Contoller</h1>
<ul>In <b>config.h uncomment PPM mode</b>, PWM mode is set as default.</ul>

<ul>In my case as I used Arduino, PPM input pin is <b>D2</b></ul><br>



MultiWiiConf<br>
<a href="https://imgur.com/aJTKueH"><img src="https://i.imgur.com/aJTKueH.gif" title="source: imgur.com" /></a>
