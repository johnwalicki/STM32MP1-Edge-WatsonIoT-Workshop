*Quick links :*
[Home](README.md) - [IoT Platform Starter](CREATEIOTP.md) - [Device Types and Devices](DISCOVERYDEVICE.md) - [Node-RED Setup](NODERED.md) - [Sensor Data](DISCOVERYIOTDATA.md) - [Node-RED Charts](DASHBOARD.md) - [Store Data in Cloud Storage](CLOUDANT.md) - [Historical Charts](HISTORY.md) - [Watson Studio](STUDIO.md) - [Jupyter Notebooks](JUPYTER.md)
***

# Send Device Environmental Sensor Data in Node-RED

## Lab Objectives

In this lab you will build a flow that sends Device environmental temperature and humidity sensor data.  You will learn:

- How to create a new Node-RED flow and configure IoT Nodes
- How to output the Device environmental temperature and humidity data.

### Introduction

In just a few nodes, Node-RED can send the STM32MP1 environmental sensor data from the edge over MQTT to Watson IoT Platform.  

### Step 1 - Enable the Send

-

### Step 2 - Configure the Watson IoT Credential

- Recall that the environmental sensor data was transmitted in a JSON object

 ```
 { "d": {"temperature":T,"humidity":H,"acc_x":X,"acc_y":Y,"acc_z":Z,"gyr_x":X,"gyr_y":Y,"gyr_z":Z} }
 ```


## Step 3 - Node-RED Debug Nodes


### Step 4 - Wire the Node-RED nodes together

**Congratulations** - Your Node-RED flow is sending sensor data from the Discovery Kit board.

Continue to the next step - [Node-RED Charts](DASHBOARD.md)
***
*Quick links :*
[Home](README.md) - [IoT Platform Starter](CREATEIOTP.md) - [Device Types and Devices](DISCOVERYDEVICE.md) - [Node-RED Setup](NODERED.md) - [Sensor Data](DISCOVERYIOTDATA.md) - [Node-RED Charts](DASHBOARD.md) - [Store Data in Cloud Storage](CLOUDANT.md) - [Historical Charts](HISTORY.md) - [Watson Studio](STUDIO.md) - [Jupyter Notebooks](JUPYTER.md)
***
