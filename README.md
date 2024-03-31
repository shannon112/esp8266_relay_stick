# esp8266_relay_stick
#### A esp8266 based relay stick connected with google home via IFTTT
<img src="https://raw.githubusercontent.com/shannon112/esp8266_relay_stick/main/demo.png" width=400>

# Development
1.Reproduce wifi relay with Blynk app
  - Video tutorial ref: https://www.youtube.com/watch?v=G7XyRiR8pBg
  - Blynk: https://blynk.io/en/getting-started

2.Code generator
  - https://examples.blynk.cc/?board=ESP8266&shield=ESP8266+WiFi&example=GettingStarted%2FBlynkBlink
  - Blink LED: using Digital Pin 4 (D4) to trigger built-in wifi LED

3.How to install library
  - http://help.blynk.cc/en/articles/512105-how-to-install-blynk-library-for-arduino-ide
  - To install a new library into your Arduino IDE you can use the Library Manager (available from IDE version 1.6.2). Open the IDE and click to the "Sketch" menu and then *Include Library > Manage Libraries*.
  - Then the Library Manager will open and you will find a list of libraries that are already installed or ready for installation. Search for **Blynk** library and in the version selection choose the latest version to date
  - Finally click on Install and wait for the IDE to install the new library. Downloading may take time depending on your connection speed. Once it has finished, an Installed tag should appear next to the Bridge library. You can close the library manager.
  - You can now find the new library available in the Sketch > Include Library menu.
  - If "fatal error: version.h: No such file or directory", most probably you have outdated Arduino Core for ESP8266. Please update

4.Connect Blynk with google home via IFTTT
  - IFTTT: https://ifttt.com/home
  - Steps: create -> add -> if -> google assistance, then -> web hook -> ping [blynk-cloud.com](http://blynk-cloud.com/) ->
  - <img src="https://i.imgur.com/c0xYdkL.png" width=200>
  - Here Blynk D4 is GPIO2 -> use update/D2 in IFTTT

5.api.ai and google assistant: https://www.youtube.com/watch?v=Uvg0ruRkKgY  

6.add to google home add device, self-server? （not free for permanent）  
  - part1: https://www.youtube.com/watch?v=-tnYAI3mE24
  - part2: https://www.youtube.com/watch?v=0czm7VIgoZs

7.Sinric pro: https://help.sinric.pro/  

8.google home group command  

# Demo
video: https://www.youtube.com/watch?v=xkiy1Ddirzs
<img src="https://raw.githubusercontent.com/shannon112/esp8266_relay_stick/main/video_snapshot.png" width=800>
