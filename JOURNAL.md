# Project Journal - Time Spent 30 hours

# Day 1 - 7/24

I researched on possible components and stuff to use on my PCB. I looked into multiple MCU's like the STM32F411 and the ESP32S3 series, but I had little success or good experience with both, because my STM32 board was extremely annoying to program, and my ESP32S3 board had very little support on configurations which lead to serial monitor to not work properly.

So this time, I wanted to start with a well supported, and new MCU to get more experience. I was thinking about doing the RP2350A, which was a very popular MCU for makers and hobbyists. Furtheremore there was a lot of support and enthusiastic users. One thing I was concerned about was the stock, but hopefully I can prorder some before they run out.

I wanted to use an IMU, and since the ICM42688 was well known for its insanely high precision and accuracy, I didnt see what was wrong with going with it. It has good specs, and lots of support, and works well for me in the past.

For the Barometer, I settled with a DPS368, but I would have to solder it on my own, because its STANDARD on JLC PCB which meant the PCB would cost around 250 dollars, instead of 130. However despite that, it still has really good specs, and very good resolution.

For the GPS I settled with a GY-NEO6MV2 Arduino GPS Module for its ultra fast refresh rates and very accurate positioning, which I need in a lot of projects.

Time Spent - 3 hours

# Day 2 - 7/25

I made the RP2350 Base Schematic today, which took way longer than usual, due to lots of part switching and redoing. In the end I ended up with this, which I am pretty satisfied with. I had some problems with the decoupling capacitors as I had lots of conflicting information, and researching for the right JLC PCB parts took a long time, as I was ensuring to only use ECONOMIC parts.

<img width="879" height="764" alt="image" src="https://github.com/user-attachments/assets/f84f78e9-e06d-4988-8aba-cc42f4697440" />

Time Spent - 4 hours

# Day 3 - 7/26

I added the battery connector, and memory today, which was pretty annoying, as there were many types of memory, QIO, QSPI, and etc. After figuring this out, I ended up with this, which took 2 hours to design. It takes me a bit of time because I am an amaetuer designer.

<img width="828" height="402" alt="image" src="https://github.com/user-attachments/assets/815422ea-1381-48d6-935d-a4f7ece72bc4" />

Time Spent - 2 hours

# Day 4 - 7/27

Today I figured out the Power Regulator, because I was going to use the AMS1117. which is a good LDO rated up to 12v, way more than the voltage this board was going to get. I had to take a lot of time researching on Power Reg maintaining things.

This is because I didnt know how to use both USB voltage and Battery voltage to power the board. Turns out, after a lot of research, that USB voltage and battery voltage can both be connected to a diode which is then conencted to VIN to the LDO, or another option is to use a 3 pole slider switch which swithces between the USB voltage and the battery voltage, even if both of them are connected. I opted for the switch version, because that would lead to no voltage drop, and have no consequences I was fearing.

<img width="828" height="402" alt="image" src="https://github.com/user-attachments/assets/cab42bfd-6352-4746-ab7d-0c5966cf8287" />

Time Spent - 4 hours

# Day 5 - 7/28

Today I worked on the IMU, Barometer, RGBW LED, and GPS Module

I was able to easily connect the IMU, and the Barometer pretty quickly.

The REGBW LED required some more research, due to some resistors placement and the Ohm value of those resistors. The GPS was easy, because there are only 4 things to connect, VCC, GND, RX, and TX. 

Time Spent - 2 hours

# Day 6 - 7/29

Today I worked on the PCB Layout. I layed out all the components in a way I was satisfied, because there is very little space, 3 cm by 3cm, and also I wanted it to be easy to route.
Doing this took a lot of time, because of the condense layout. 
<img width="866" height="854" alt="image" src="https://github.com/user-attachments/assets/bfaee842-85f7-4c67-a8ac-1a678161ec2f" />

Time Spent: 3 hours

# Day 7 - 7/30

Today was a bunch of routing the Memory Chips, and the Sensors, which was pretty time consuming.

<img width="622" height="953" alt="image" src="https://github.com/user-attachments/assets/833d6d3e-80c3-4cad-a55f-bb0babd27b66" />

<img width="680" height="621" alt="image" src="https://github.com/user-attachments/assets/66ceded2-f0b9-43f8-8ea7-03d9c0b329c1" />
<img width="689" height="500" alt="image" src="https://github.com/user-attachments/assets/e80c513c-38c8-471a-82df-1dd42a1a7e0f" />

Time Spent : 4 hours

# Day 8 - 7/31

Today I spent a bunch of time, as this was the last day, and grinded out the rest of the routing. I finished the entire board, which took me a lot of time, but this was the end result, which I am very satisfied with: <img width="881" height="835" alt="image" src="https://github.com/user-attachments/assets/6c43f195-6b03-4b84-a01b-01e2e1bdb1d7" />


I also worked on the journal today, which took like 3 hours in total so yeah.

Time Spent : 8 hours

