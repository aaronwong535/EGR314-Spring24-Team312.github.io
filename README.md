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

### Roles and Responsibilities
![Table 1](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Table%201%20.png)

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

## Design Ideation
![Figure 4](https://github.com/aaronwong535/EGR314-Spring24-Team312.github.io/blob/main/Screenshot%202024-04-30%20005606.png)

In this assignment, we have organized those ideas in a brainstorm session, where we listed sticky notes. First, we brainstormed on our own, then we shared our ideas in a discussion and generated more ideas. Together, we have generated around 100 different ideas for features on our product, which can be seen in Figure 4. Then I generate some drawings in following design concepts.


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

