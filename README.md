# Project Title :- #
## "Low Cost IV Monitoring And Warning System" 

# Discription :- #

* The major problem faced in these days for every hospital that is fighting towards COVID-19 pandemic is, dealing with the intravenous infusion (IV) bottle. As there is a rise in the cases of COVID-19, the load on hospital and working medical staff has increased.

* In this situation monitoring the saline level of many patients at a time becomes a tedious and time-consuming task. Also due to increased load,  an empty saline bottle connected to the patient can cause many serious medical problems to the patient’s health. Thus, real-time monitoring of the IV bottle is required to ease the task of the hospital staff and nurses. So, in order to solve this problem, we have strongly proposed a feasible solution that monitors the saline levels and warns the user if the level of fluid in any infusion bottle is low.

* The user of the system can see the data of many infusion sets at a time on a single screen along with a low level warning. Such a real-time monitoring system will be helpful to the hospital staff while dealing with many infusion bottles at a time. This is highly advantageous especially during night times as the staff is less compared to the daytime. Our solution can be used in the hospital, ICU, CCU, NICU, OPD, OT, and all departments of the hospital. Our solution is simple, accurate and can be also manufactured in bulk at a very short time period.

# Software Requirment :-

* [Arduino IDE](https://www.arduino.cc/en/main/software)
* [NodeMcu Library](https://www.instructables.com/id/Quick-Start-to-Nodemcu-ESP8266-on-Arduino-IDE/)
* [Hx711 Library](https://github.com/bogde/HX711)
* [Blynk Library](https://github.com/blynkkk/blynk-library)
* [Blynksimpleesp8266.h Library](https://github.com/blynkkk/blynk-library/blob/master/src/BlynkSimpleEsp8266.h)

# Hardware Requirment :-

* [Nodemcu](https://www.amazon.in/Robotbanao-NodeMcu-Development-Board-ESP8266/dp/B07D32X6GN/ref=sr_1_2?dchild=1&keywords=Nodemcu&qid=1586329342&sr=8-2)
* [Hx711 ADC or Loadcell Amp.](https://www.amazon.in/Robodo-Electronics-SEN13879-Dual-Channel-Precision/dp/B07B8SJTGW/ref=sr_1_3?dchild=1&keywords=Hx711&qid=1586329454&sr=8-3)
* [Load Sensore 5Kg](https://www.amazon.in/REES52-Load-Cell-Weighing-Sensor/dp/B07V3LZHBG/ref=sr_1_1?crid=2XETY8VRMMK9U&dchild=1&keywords=load+sensor+5kg&qid=1586329511&sprefix=5kg+load+sen%2Caps%2C317&sr=8-1)
* [Power Supply Module](https://www.amazon.in/Robodo-Electronics-OTH17-Arduino-Raspberry/dp/B07B918S9L/ref=sr_1_3?crid=1Q2UK32PPEZQB&dchild=1&keywords=power+supply+module&qid=1586330011&sprefix=power+supply+%2Caps%2C339&sr=8-3)
* [Male To Male Jumper Wire](https://www.amazon.in/ApTechDeals-Jumper-Female-breadboard-jumper/dp/B074J9CPV3/ref=sr_1_2?crid=3MY4CGDNPL03B&dchild=1&keywords=male+to+male+jumper+wires&qid=1586329561&sprefix=male+to+male+%2Caps%2C381&sr=8-2)
* [Female To Male Jumper Wire](https://www.amazon.in/ApTechDeals-Jumper-Female-breadboard-jumper/dp/B074J9CPV3/ref=sr_1_2?crid=3MY4CGDNPL03B&dchild=1&keywords=male+to+male+jumper+wires&qid=1586329561&sprefix=male+to+male+%2Caps%2C381&sr=8-2)
* [Female To Female Jumper Wire](https://www.amazon.in/ApTechDeals-Jumper-Female-breadboard-jumper/dp/B074J9CPV3/ref=sr_1_2?crid=3MY4CGDNPL03B&dchild=1&keywords=male+to+male+jumper+wires&qid=1586329561&sprefix=male+to+male+%2Caps%2C381&sr=8-2)
* [6*4 PCB](https://www.amazon.in/General-purpose-female-pinhead-connector/dp/B07X86M6V6/ref=sr_1_1?dchild=1&keywords=6*4+pcb&qid=1586329625&sr=8-1)
* [Male Bugpin](https://www.amazon.in/General-purpose-female-pinhead-connector/dp/B07X86M6V6/ref=sr_1_1?dchild=1&keywords=6*4+pcb&qid=1586329625&sr=8-1)
* [Female Bugpin](https://www.amazon.in/General-purpose-female-pinhead-connector/dp/B07X86M6V6/ref=sr_1_1?dchild=1&keywords=6*4+pcb&qid=1586329625&sr=8-1)
* [Soldering iron](https://www.amazon.in/Twisted-25-Watt-Soldering-Iron/dp/B07H7RB5Q4/ref=sr_1_9?crid=KBXHOQ60L92M&dchild=1&keywords=soldering+iron+set&qid=1586329699&sprefix=solde%2Caps%2C367&sr=8-9)
* [Soldering Flux](https://www.amazon.in/Twisted-25-Watt-Soldering-Iron/dp/B07H7RB5Q4/ref=sr_1_9?crid=KBXHOQ60L92M&dchild=1&keywords=soldering+iron+set&qid=1586329699&sprefix=solde%2Caps%2C367&sr=8-9)
* [Soldering Core](https://www.amazon.in/Twisted-25-Watt-Soldering-Iron/dp/B07H7RB5Q4/ref=sr_1_9?crid=KBXHOQ60L92M&dchild=1&keywords=soldering+iron+set&qid=1586329699&sprefix=solde%2Caps%2C367&sr=8-9)
* [wall Hook](https://www.flipkart.com/daluci-strong-adhesive-hook-wall-door-sticky-hanger/p/itmca741139c2a0d?pid=HOKFJAXHPASU9G7W&lid=LSTHOKFJAXHPASU9G7W14NOTX&marketplace=FLIPKART&srno=b_2_52&otracker=browse&fm=organic&iid=c74fbe91-e99c-4f8a-b277-abe8c267347b.HOKFJAXHPASU9G7W.SEARCH&ppt=browse&ppn=browse&ssid=4ok87mxfg00000001586329134841)

# Procces Flow Diagram :-


![p-1](https://user-images.githubusercontent.com/63282206/78758094-30922f80-799b-11ea-9b03-e073470608b7.PNG)

* First of all the IV bottle is hanged on the load cell. 
* The load cell is connected to HX711 load cell amplifier which is further connected to microcontroller (nodeMCU esp8266) unit. Now the data of the load cell is sent to the microcontroller which is uploaded to Blynk IoT platform. 
* On the mobile screen we have level indication along with low level warning notification.
* The entire system can run on mains as power supply as it inbuilt power module on circuit board and also it has a battery with long backup.

# Data Flow Diagram :-


![d-1](https://user-images.githubusercontent.com/63282206/78861396-46aef700-7a52-11ea-876e-65c6465b0877.PNG)

* First of all Load Sensor is connected with the Load cell Amp. so it is basically a 24-bit ADC converter.
* Whatever the data coming from the Load Sensor is about 24-bit, so basically Hx7111 Load cell Amp. converts data to 10-bit ADC so that the controller can read it.
* After that, data fetched from the Load Sensor is directly shown in the Blynk IoT app. this is the real time indication.
* Now controller check continuously that whether the saline level in IV bottle is low or not.
* If the level is low, then Warning will be shown along with Pop-up notification in the App even if it is closed And if level is not low then controller check continuously.

