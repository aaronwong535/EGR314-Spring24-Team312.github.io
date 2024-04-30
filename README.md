# Team312 - Weather Car Kit
### Arizona State University | EGR314 Embedded Systems Design Project II (Spring 2024) | Dr. Nichols
#### Created: 4/28/2024

Team Folder: https://drive.google.com/drive/u/0/folders/1KPCw2cV3fNMRF2c39YbxHCWmRoh7PTGd


## Team Members
*  Baowen (Aaron) Huang


## Introduction
Weather stations data collection has been a tool that has benefited many outdoor uses for identification of surrounding environments for even many more applications. With high demands in its use, demands for higher quality data and precision only continue to evolve. Hence, the team identified that applications of these increasingly improving technologies could be applied more towards indoor uses. This project follows such applications, specifically from inspirations from humidifiers.


## Team Organization
### Team goal
* Create a durable and functional prototype that would satisfy the projected clients.
* Learn from and quickly adapt to failures or unexpected changes throughout the development.
* Communicate ideas within the group successfully and respectfully that can accommodate everyone's interests as best possible.
* Better understanding the engineering process from start to finish with an actual stakeholder.
* Delivering a final product on time that we can showcase on our portfolio and resume
* Creating a device that will be used for years.

### Mission Statement
Bringing a kit car with a sensor detecting the weather. It’s meaningful for children to have a kit like that for engineering and astronomy education. 

Since there's only me in the team, so I would take response for every role. More information about the team will be present in Appendix 1.

## User Needs and Benchmarking
We begin developing ideas by identifying the voice of the customer and benchmarking most of those aspects to explicit and latent needs. The list of researched products in Appendix (B)  incorporates seven products we found interesting and gathered feedback from those users.

During our brainstorming sessions, we used both mind mapping and Jamboard to gather and record all the user needs for our weather station project. We began by creating a mind map to explore different aspects of the project and generate ideas. Then, as ideas flowed, we transferred them onto the Jamboard, which allowed us to collaborate in real-time and visually organize our thoughts. Each team member contributed their insights, and together, we evaluated the importance of each user's needs. By combining mind mapping with Jamboard, we ensured that we thoroughly explored all possibilities and captured every important aspect of the project. This approach helped us create a comprehensive list of user needs, which became the foundation for our design and development process.
![Figure 1](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Figure%201.png)

_Figure 1: Organized needs_

In planning our weather station, we grouped the things users wanted into different categories. One category focused on making the station easy to move around, like putting it in a car or using it while hiking. Another category was about the information the station collects, making sure it's accurate and can be used for different purposes. We also looked at how the station is built, making sure it's stable and resistant to things like dust and bad weather. Lastly, we thought about why people would use the station and made sure it meets their needs, like being educational or affordable. These groups helped us understand what users want and guided how we designed our weather station to meet those needs. 

![Figure 2](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20004318.png)

![Figure 3](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20004505.png)

To rank the needs for our weather station project, we first gathered all the things users wanted. Then, we had a meeting with our team to talk about each need. We discussed which ones were most important based on how they would affect users and how hard they were to do. We also asked other people for their opinions to make sure we didn't miss anything. We used a system to give each need a score to show how important it was. This helped us focus on the most important things first, making sure we met the most critical requirements for our project to succeed. More details in Appendix B. These ranking processes allowed us to create a Product Requirements Document for guidance in developing a product.


## Product Requirements 
### Introduction
In the quest for the car kit for children, ease to assemble, safety and accuracy are key. It has a very simple structure that children can easily to build it. While professional weather stations have highly precise sensors for weather forecasting, there's a chance to bring similar accuracy and ease to the toy like this. Mobile apps help us understand outdoor weather and control the car to move. In that case, children can detect the weather data while they’re driving.

### Objective
The project plans to involve the development of a weather station for these demands to a wider public. With the inclusion of 1 sensor for a mobile weather station, the product is intended to collect and transfer data over WiFi using the MQTT protocol. The project also intends to include at least 1 actuator in the form of a motor and communicate commands over a I2C or SPI-based protocol. Functionality of the motor controlled actuator will remain of high importance in this project for successful sensor readings. We aim to maintain similar accuracy to competitors in the weather sensing market which includes the durability they are known for as well. 

### Stakeholders
#### Target group
Children, or people who's interested in engineering, weather detecting, etc. 

#### Customer service
It would be a durable and simple interface as well as user friendly and safe design.

#### Marketing
A lot of kids are interested in engineering field and astronomy, which is a good choice to start.

### Use Cases
User Story #1: Mark
Mark is a 45 year old farmer a few hours from the city of Phoenix. Storms and especially in the monsoon season are aspects in weather he needs to be immediately aware of for the optimal care of his crops and ease of his work. Some information may get to him later than others due to his distance. The new weather station our team develops allows for immediate access to environmental data to his current surroundings rather than approximations.

User Story #2: Sarah
Sarah, a 35-year-old architect in Denver, faces dry climate challenges in her home office. Living a bit away from the city center, she lacks immediate weather updates. Our team's smart humidifier provides real-time, location-specific humidity data, helping her maintain comfort and focus without relying on generalized forecasts.

User Story #3: Jake
Introducing Jake, a 45-year-old farmer situated just outside Phoenix. For Jake, swift access to precise weather data is essential, especially during the monsoon season, to effectively manage his crops and workload. Our team's innovative weather station ensures Jake receives real-time updates tailored to his location, enabling him to make informed decisions promptly for optimal farm care and productivity.

### Aspects
#### 1. Hardware/Product Design
1.1 The product will be durable to withstand indoor conditions, reasonable impacts and ensure longevity.

1.2 The product will have a user-friendly design for ease of use.

1.3 The product will be able to sustain a substantial amount of force for durability.

1.4 The product will be designed to prevent water damage and ensure safety during operation, providing peace of mind for indoor use.

#### 2. Software/Functionality
2.1 Environmental data will be transferred over WiFi using the MQTT protocol.

2.2 The product will include at least one motor controlled by a motor controller using I2C or SPI-based protocol.

2.3 The product can be controlled manually and automatically.

#### 3. Interactivity & User Interactivity
3.1 The main user interface will be reasonably operational.

3.2 The product will have armor that can be easily maintained by the user.

3.3 The product will be easily cleaned and maintained by the user.

3.4 Battery powered models will have batteries replaceable/rechargeable by the user.

3.5 The humidifier will feature intuitive controls and a user-friendly interface for effortless operation and personalized comfort.

#### 4. Manufacturing
4.1 The product will remain within the course budget.

4.2 The product’s case should be easily assembled and removable by the user for replaceability.

#### 5. Safety
5.1 The product will remain safe for pets and children to approach safely.

5.2 All wiring will remain enclosed and water resistant.

5.3 Temperature conditions should not affect or compromise the encasing of the product.


## Design Ideation
![Figure 4](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20005606.png)

In this assignment, we have organized those ideas in a brainstorm session, where we listed sticky notes. First, we brainstormed on our own, then we shared our ideas in a discussion and generated more ideas. Together, we have generated around 100 different ideas for features on our product, which can be seen in Figure 4. Then I generate some drawings in following design concepts. More details are in Appendix C.


### Concept 1: Rotating Weather Station
![Figure 5](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010127.png)

This is the first design concept, which is a rotating weather station. It has a plastic plate that casing the wires and PCB into it. Under the plate, the motor is located in the middle of the plate so that it would be able to rotate the plate. The key point of this concept is this product would be detecting Wind speed and temperature in different spots every other 10 minutes. Every 10 minutes, the motor rotates the plate and the sensors would be moved to the other spot. As a result, the sensors would be detecting the wind speed and temperature with each different spot in the air and get more accurate information about weather.

### Concept 2: Moving Weather Station
![Figure 7](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010140.png)

This device is designed for children. The device is designed to be easy to install, or to move to another location. To achieve this, the design will be small and light, and will not require complex installation. The device detects the temperature, as well as the ambient humidity. The device has a humidity sensor and temperature sensor to detect the weather data. The purpose of this device is to give users a more accurate description of the weather, because weather apps and official weather reports use readings from stations that may be far away from the user, resulting in inaccurate reports.

### Concept 3: Automatic Water sprayer
![Figure 8](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010147.png)

This concept is a water dispenser that waters surroundings that are dependent on optimal atmospheric conditions, temperature and humidity. This concept measures the temperature and humidity and once the temperature is too high or it is dry in the air, the mixture is dispersed. This concept also uses a focus on mobility since this is considered to be used on a larger land of planting or growing. With the possible use of a planting on the ground, the device can be placed on different parts of the dirt for a larger coverage. This would require a power source just as mobile. Since it is meant to be outside a solar system alongside a battery seems optimal. Since we intend to cover a larger range, connectivity between multiple devices is also considered to be appropriate for this concept.


## Selected Design
The final selected design is concept 2. Because the moving weather station is easiest and most friendly for children. It just contains 3 parts and don’t have any components too heavy or too small to assemble. Besides, children are more interested in playing a movable car rather than a fixed weather station.
![Figure 9](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010241.png)

However, since this project starts 5 weeks before this report, I don’t have time to learn about more sensors except for hall effect sensor, which I used to finish the advanced serial communication assignment. So I decided to use only a hall effect sensor on the car, and simulate the wind speed detection with a turning magnet upon the sensor.


## Block Diagram
![Figure 10](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010301.png)

The block diagram above incorporates all required components including the MQTT server connection, a Hall Effect Sensor, a motor and accompanying driver for our actuating system and the PIC18 as our microcontroller. The combination of these devices ultimately allow for a responsive Kit car that can output the wind speed value through the microcontroller as seen in the SDA/SCL I2C connection which ultimately displays through the MQTT wireless connection. Communication between the motor driver and the micro controller is SPI, while the connection to MQTT server is more specifically through the ESP32's capabilities of publishing and subscribing to the data. The motor driver is controlled by MQTT. In this case, children can easily control the motor by mobile phone or PC, as well as read the wind speed data.


## Components Selection
Selected Components:
### Hall Effect Sensor: AS5600-ASOM
![image](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010356.png)

The AS5600-ASOM Hall Effect sensor was chosen for its high accuracy, wide operating range, compact design, and robust construction. It offers reliable performance across various humidity levels, is durable in harsh environments, and is supported by comprehensive technical documentation and reputable manufacturer support. These factors make it the optimal choice for the intended application.


### Motor: 711
![ ](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010403.png)

The 711 motor pump was chosen due to its compact size, sufficient power for effective vapor dispersion, quiet operation, energy efficiency, availability, and cost-effectiveness, meeting project requirements efficiently.


### Motor Driver: IFX9201SGAUMA1
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010408.png)

We decided to use the IFX9201SGAUMA1 primarily because we already have several of it, so we will not need to purchase any for our prototype. It is also large enough to solder by hand without damaging the component. It also can handle a much higher voltage and current than our product will use, so there is no risk of overloading the driver.


### Voltage Regulator: LM2575-3.3WU-TR
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010415.png)

The LM2575-3.3WU-TR was selected for its efficiency, reliability, and ability to provide a stable 3.3-volt output, crucial for powering various electronic components. Its surface-mount TO-263 package and tape and reel packaging make it suitable for automated assembly processes, simplifying manufacturing. Overall, it meets the project requirements effectively and efficiently.


### Power Supply: ZEUS 9V
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010419.png)

Although option 2 is rechargeable that seems to be more convenient, the lack of capacity (250mAh) is an issue, especially when it works in the rural area with lack of charge points. Option 1 and 3 have almost exactly the same data as each other, but option 3 is less expensive.


### Microcontroller Selection
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010452.png)
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010519.png)
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010529.png)

Link to product page: [PIC18F46K22](https://www.microchip.com/en-us/product/PIC18F46K22)

Link to Datasheet: [PIC18F46K22](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18%28L%29F2X-4XK22-Data-Sheet-40001412H.pdf)

Link to Application Notes: [PIC18F46K22](https://www.microchip.com/en-us/application-notes/an1921)

Link to Code examples: [PIC18F46K22](https://simple-circuit.com/pic18f46k22-adc-7-segment-display-ccs-c/)

Link to External Resources: [PIC18F46K22](https://youtu.be/gXaTH2KL0nE?si=ppkfv8kwARrZ3ML-)

When it comes to choosing the microcontroller for the team 309, we decided to use PIC18F46K22 because of several advantages.The PIC18F46K22 microcontroller was chosen for the project due to its balance of processing power, memory capacity. With its 8-bit architecture, the PIC18F46K22 provides sufficient computational capability to handle sensor data processing, motor control algorithms, and MQTT protocol implementation without being overly complex. Its ample flash program memory and RAM ensure that there's enough space for storing program code, sensor data, and MQTT message buffers. The microcontroller's rich set of built-in peripherals, including UART, SPI, and I2C interfaces, are essential for interfacing with serial sensors and motor controllers. Additionally, its low-power operation modes make it suitable for battery-powered or remote applications. Microchip's extensive documentation, libraries, and development tools further support development, debugging, and troubleshooting. Finally, the PIC18F46K22's compatibility with MQTT libraries and WiFi modules enables the implementation of MQTT protocol for broadcasting environmental data over the internet. Overall, the PIC18F46K22 offers a cost-effective solution with the necessary features and performance for the project's requirements.

### Power Budget
Regarding the power budget, the estimated operation time of product is approximately 1.9 hours. By examining the power consumption of key components like the sensor, microcontroller, motor, and motor driver, we gained insights into factors affecting device runtime. The critical roles of these components significantly impact overall power usage, aligning with our projected operational time. To address this, we prioritized selecting power-efficient components and implementing optimization techniques to extend operational lifespan within the specified timeframe. Leveraging insights from the power budget, we aimed to balance functionality and energy efficiency, ensuring sustained performance while meeting operational requirements. 

![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20014313.png)

_Table 3: Power Budget Table_


## Hardware Implementation
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010550.png)

Voltage regulation consists 3.3 V rail. The battery voltage (9V) satisfies the voltage requirement for the motor power while the 3.3V rail powers the rest of the product components. The voltage regulator also consists of a fuse. The inclusion of a fuse and the separation of voltage regulators should allow for a safer design for users to avoid using drop voltage methods that may heat up more than anticipated. This also adds an additional separation that may avoid a power surge between those two rails.

The hall effect sensor is applied with recommendations from the developers themselves. Following their I2C set up helps create a closer resemblance to the intended company design for safer applications while the I2C limits our main data uses ae limited to the two input data rails I2Cs use.

Two motor drivers consist of a motor separately that has a motor powered by 9V and a driver powered by 3.3V. By using 2 different motor drivers, I may adjust different speeds for motors in order to make a turn. 

The ESP32 system has a design that allows for simple connection set up that will ultimately allow users to edit the parameters via wi-fi. Along with an LED, the system allows for debugging that helps maintain reliable connection and function for continuous use.

Most components used are recommendations from datasheets of the main drivers and sensors. A list of the bill of materials is listed in Appendix D.

![Figure 13](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010640.png)

If I can create the second version of hardware design, I will：
* Switch to a microcontroller with more spacing between pins
* Add a switch to turn on and off the device
* Move the ESP32 pads further than this and manage circuit to make sure ESP32 module would not burn out when attached on pads
* Add more sensors in order to detect more data
* Add more paths between ESP32 and microcontroller to control motor better
* Add a camera in front of the car to collect data in front of the car for machine learning


## Software Implementation
![](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20010538.png)

Initially at the main function, an initialize system is required to initialize the starting variables.  Under the initialize system, we require initializing a starter value for the temperature and humidity user settings. These will change depending on the user inputs. Then, initializing the actual humidity and temperature raw data in order to store the receiving data from the sensor. Finally the motor state will also be initialized in order to account for the output of when it will be activated.
Interrupts are then enabled into the continuing loop that will mainly read any changes from user inputs to the sensor data itself. Then the data would be converted into the actual wind speed and output to MQTT. Meanwhile, MQTT server also controls the motors to move the car, achieving moving front and back, and turning around by 2 different groups of 4 bottoms (left motor forward and backward, and right forward and backward).
This design is straightforward so that children can play and have fun with it easily.
The MQTT Topic Table, C code and MCC configuration are attached to Appendix G.

Here’s 5 biggest challenge for software design:
* Every sensor and motor driver has different types of special pointers to control, so I have to check the data sheet on coding
* The limitation of microcontroller limits the functionality of product
* The microcontroller has a huge different from the curiosity nano used in class, so I spended a lot of time for setting up and in-circuit programming
* The motor system can’t be controlled the way I expected.
* The ESP32 module is also hard to set up

If I can create the second version of software design, I will：
* Switch to a more functionable and user-friendly microcontroller
* Continue to improve the code for controlling the motors, for ex., using PWMs to achieve different motor speed
* Develop more sensors to detect more data
* Apply machine learning (ML) to achieve autopilot


## Lesson Learned
* Learn about how to use GitHub to post a website like this
* Flux is a good friend when soldering, especially with surface-mount small pads 
* Code in MPLAB, it’s easier to use than PSoC and I can save a lot of time on top design, but be careful for all settings
* Use Cadence to do circuit building and PCB, although it’s very complicated and a lot of errors happens, it’s a powerful app
* Apply interrupts in programing, which makes product more efficiency
* Learn how to use digital sensor and motor driver controlled by SPI and I2C
* Select a microcontroller that fix with product, which needs a lot of time for reading datasheet, comparing and making sure it meets the requirements and easily-used
* Use ESP32 to upload data into MQTT server, as well as control the components by ESP32
* Use a snap to do in-circuit programming
* Leave the team that I’m not feeling comfortable
* Work on the project with all subsystems by myself in 5 weeks


## Recomendation for Future Students
* Read datasheets carefully, since they contain all the information that you would need to design your circuit around that component, and pay attention to special pointers.
* Don't be afraid to ask questions to either the professor, the TAs, or even other students. This is a difficult class and you’re not expected to know everything at the start; you are here to learn.
* If you can buy your own soldering kit that has a finer point than the ones in class. The finer point makes soldering your PCB board worlds easier; it helps to get into those smaller areas.
* It’s impossible to get a perfect PCB board by just manufacturing it once. If you doesn't have enough time to get it remanufactured, don’t worry,  you'll find some errors on the PCB, just try to bridge some ports to make it work as possible
* Every assignment and lab is important, they give you knowledge of how to make components work. It’s recommended to start early rather than close to due. If you brush over an assignment, it's going to cost you later on.
* Take your time with making symbols and footprints because manufactured PCBs take time to remanufacture, little mistakes will cost you heavily.
* Team is very important for this project class. Meet and communicate with your engineering team as often as possible and make sure that team is on the same page when going through the project. Don’t be lazy in the team, and don’t blame others usually, which will get trouble with the project.
* If you feel uncomfortable with the team, talk with teammates and professors to see any improvements. If no improvements, quit out or switch the team before selecting components that all things can be changed easily.
* Select a microcontroller comfortable to use, which save a lot of time for programming
* When you get everything working in the last week, don’t take a risk to make significant changes, no matter in code or circuit. Bugs at least don’t prevent program working
