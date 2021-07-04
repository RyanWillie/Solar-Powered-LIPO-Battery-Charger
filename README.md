# Solar-Powered-LIPO-Battery-Charger
Circuit design and construction of Lithium Polymer Battery Charger based on the LM317 adjustable voltage regulator. This was completed as the final design project of the course 3312ENG. The circuit is aimed to charge a 2S Lithium Polymer battery safely from a 12V solar panel, the below outlines the design steps and construction of the circuit. 

## Background
Lithium Polymer (Li-Po) batteries are a lower-cost version of traditional Lithium-Ion (Li-ion) Batteries. Their internal chemistry is similar to that of Li-ion in terms of energy density but instead uses a dry solid polymer electrolyte resembling a non-conductive plastic like film. The dry polymer is more cost effective during fabrication, also resulting in a design that is rugged, safe and thin. With cell thickness as small as 1mm, possible applications of these batteries are small communications devices, personal electronics, Electric Vehicles and Radio-Controlled Equipment. The voltage of a single LiPo cell can vary but ranges from about 4.2V(Fully Charged) to 2.7-3V (Fully Discharged) with a nominal voltage of 3.7V.

Li-Po Batteries require special current and voltage-limiting recharging devices, the typical safety threshold is set to 4.3V per cell with a current rating of 1-C, where the C rating is the capacity of the battery. E.g. a 5000MaH battery can be charged at 5A safely. Full Charge is attained when the voltage has reached the upper voltage threshold and the current has dropped to 5-10% of the nominal charge current. The typical charge time is approximately three hours with variance depending upon the charging current. The charging is conducted in two separate phases, the first being a constant current charge phase at 1C until the battery voltage is 4.2V per cell, followed then by a constant voltage charge phase where the current is slowly reduced until the full charge 

![Charging Chart](https://raw.githubusercontent.com/RyanWillie/Solar-Powered-LIPO-Battery-Charger/main/Images/Charging.jpg)


## Design Steps
The overall design process is broken down into three categories:
    - __Circuit Design__ - Designing the charging circuitry
    - __Solar Panel Regulator__ - Regulating the output of the solar panel
    - __Modelling and Construction__ - Creating a base for the solar panel and housing for the circuitry.

## Circuit Design
Many designs are possible to achieve the desired charging characteristics, however the LM317 Adjustable voltage regulator will be used. The specific details of why this was chosen along with the full circuit design breakdown can be seen within the Final Project Report.

![Circuit Diagram](https://raw.githubusercontent.com/RyanWillie/Solar-Powered-LIPO-Battery-Charger/main/Images/CircuitDiagram.png)


## Final Product
The designed circuit was assembled and prototyped on a breadboard as well as a veroboard. The circuit was tested in realistic conditions to verify its operation. The below image shows the working circuit successfully charging a LIPO Battery.

![Built Circuit](https://raw.githubusercontent.com/RyanWillie/Solar-Powered-LIPO-Battery-Charger/main/Images/BuiltCircuit.jpg)