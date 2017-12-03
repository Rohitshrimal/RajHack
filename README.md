# Introduction

We are using NODE-RED, a flow based development tool for wiring together hardware devices, APIs and online services as part of the Internet of Things.

Node-RED provides a browser-based flow editor, which can be used to create JavaScript functions. Elements of applications can be saved or shared for re-use. The runtime is built on Node.js. The flows created in Node-RED are stored using JSON.

# How do we use Node-Red

We deployed Node-Red to our IoT device i.e. Raspberry Pi 3. In such a way we are treating Pi as an IoT Gateway.

# IoT Echo System 

We used Ultrasonic Sensor to detect liquid level of the IV Infusion. The data coming from the sensors is processed on Node-Red(playing role Software IoT gateway) and then if something goes wrong it checks them.

The whole data is also sent to IBM Watson IoT Platform where the device is registred and the data is stored in document oriented database CloudantDb.



