# Plant Tech 🌱

We're excited to have you join this course, where you'll be working with plants, Arduino boards, moisture sensors and watering systems.

The aim of Make Days is to explore and learn new thing. You don't need to achieve specific goals. The structure caters for varying levels of experience and different Makers will learn different things by playing with the same tools.

# Preparing for the Make Day

Makers that arrive well prepared get the most out of their experience. Before you attend your Make Day, there are a couple of activities to complete.

## Prep

Here's a list of things you'll need to prep before you can set up your biltong maker. 

- Install the [Arduino IDE](https://www.arduino.cc/en/main/software)
- Read the [Quick Start to Nodemcu (ESP8266) on Arduino IDE](https://www.instructables.com/id/Quick-Start-to-Nodemcu-ESP8266-on-Arduino-IDE/)

Important: if you want to use the ESP8266 WEB Server in this example you will need to downloand the following two libraries. These libraries are not available in the library manager.

### Installing the ESPAsyncWebServer library
The ESPAsyncWebServer library is not available to install in the Arduino 
Library Manager. So, you need to install it manually.

Follow the next steps to install the ESPAsyncWebServer library:

https://github.com/me-no-dev/ESPAsyncWebServer/archive/master.zip

Unzip the .zip folder and you should get ESPAsyncWebServer-master folder
Rename your folder from ESPAsyncWebServer-master to ESPAsyncWebServer
Move the ESPAsyncWebServer folder to your Arduino IDE installation libraries folder

### Installing the ESPAsync TCP Library
The ESPAsyncWebServer library requires the ESPAsyncTCP library to work. Follow the next steps to install that library:

https://github.com/me-no-dev/ESPAsyncTCP/archive/master.zip

Unzip the .zip folder and you should get ESPAsyncTCP-master folder
Rename your folder from ESPAsyncTCP-master to ESPAsyncTCP
Move the ESPAsyncTCP folder to your Arduino IDE installation libraries folder
Finally, re-open your Arduino IDE

You may also need [the driver](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers) for the usb-uart

# What will be available for you on the evening

* ESP8266 module
* Dopunt f-f wires (x10)
* Moisture sensor
* Micro usb to usb A cable
* Watering pump
* PVC tube + tie
* TIP31C Transistor

# How to get started

## Pinouts
ESP8266:
<img src="https://i1.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/05/ESP8266-ESP-12E-chip-pinout-gpio-pin.png?ssl=1" alt="ESP8266" width="250"/>

Mini Submersible 5V Water Pump:
<img src="https://potentiallabs.com/cart/image/cache/catalog/New%20Components-17/Mini%20Waterpump-800x800.png" alt="pump" width="250"/>

TIP31C Transistor:
<img src="https://www.componentsinfo.com/wp-content/uploads/2020/08/tip31c-pinout-equivalent.gif" alt="tip31c" width="250"/>

Moisture Sensor:
<img src="https://components101.com/sites/default/files/component_pin/Moisture-Sensor-Module-Pinout.jpg" alt="moisture" width="250"/>

## Manuals
- [Soil Moisture Sensor Tutorial for Arduino, ESP8266 and ESP32](https://diyi0t.com/soil-moisture-sensor-tutorial-for-arduino-and-esp8266/)
- [Soil Moisture Sensor Setup for Arduino](https://www.instructables.com/id/Arduino-Soil-Moisture-Sensor/)
- [ESP8266 smart plant irrigation system](https://iot-playground.com/blog/2-uncategorised/94-esp8266-smart-plant-irrigation-system)

## Code
If you coding isn't your strong suit, just use the code provided in the repo:
- [Moisture Sensor](https://github.com/OfferZen-Make/plant_tech_ams/blob/master/MoistureSensor.ino)
- [Complete Watering System](https://github.com/OfferZen-Make/plant_tech_ams/blob/master/plant_watering_system.ino)

# Further ideas
- Extend you project with an [RGB LED](https://howtomechatronics.com/tutorials/arduino/how-to-use-a-rgb-led-with-arduino/) to indicate moisture levels with colors.
- Send messages on [slack or telegram](http://blog.danishjoshi.com/2019/11/06/sending-messages-to-a-slack-or-telegram-channel-using-esp8266/).
- Let your system update you via text on when to water your plants with the [MessageBird API](https://developers.messagebird.com/quickstarts/sms/send-sms-curl/)
- Telling your plant to water itself - by speech! [Blogpost + code](https://codeburst.io/home-automation-using-google-assistant-dialogflow-firebase-esp8266-wemos-part-1-800c4dc15ad9)

# Useful resources
- [ ] Check out the [OfferZen Make Subreddit](https://www.reddit.com/r/offerzenmake) and upvote any answers you find useful. Feel free to add your own questions and comments! 
- [ ] Join Make Slack, introduce yourself in #meet-and-greet, and check in with your team channel
- [ ] Learn about the how, where and why of Make Days with the [Make Manifesto](https://docs.google.com/document/d/12OtTltO-ozhGd7OzDswgLoRMLtfd3_i8_Pxw1Dx551U/edit)

*Know somebody who would enjoy this course? Tell your friends to [register here.](https://forms.gle/fk8hYZLWES6fhCCg8)

