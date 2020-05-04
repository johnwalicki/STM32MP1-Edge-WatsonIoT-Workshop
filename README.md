# STM32MP1-Edge-WatsonIoT-Workshop
STMicroelectronics STM32MP1 Discovery Kit and IBM Edge / Watson Hands-On Workshop

## STM32MP1 Discovery Kit and IBM Edge / Watson Hands-On Workshop

Learn how to connect your next IoT Edge design to the Cloud using IBM Watson IoT Platform and the STM32MP1 Discovery Kit.  The STM32MP1 features a Cortex A7 multiprocessor and a ultra-low-power STM32L4 Cortex® -M4 MCU and wireless connectivity. In this workshop we will attach an IKS01A2 sensor expansion board to showcase cloud connectivity features.  By running OpenSTLinux on the A7 processor, we will run Node.js and Node-RED on the Edge device.  The program will send sensor data to the IBM Watson IoT Platform, where Node-RED running in a Node web application in IBM Cloud will display a Dashboard.  The data will be saved to a Cloudant time series database.  We will then use Watson Studio, IBM's data science portal, to create a machine learning model by ingesting the temperature / humidity sensor data. The model parameters will be sent from IBM Cloud to the STM32MP1 edge device.  Node-RED running local on the device will then score the incoming data and detect when you place your finger on the sensor.

**Presenters:** STMicroelectronics team with **John Walicki**, IBM Developer Advocate, CTO IoT Advocacy

This hands-on workshop will show you how to integrate sensors, wireless connectivity, a multiprocessor edge device, a low-power microcontroller and sensor libraries into your next IoT Edge design. You’ll then learn to connect the Discovery Kit to IBM Cloud and Watson IoT Platform to create a new application in minutes using Node-RED.  Watson Studio will create a machine learning model.  This model will be deployed to the edge.

The hands-on training is a working session – please bring your laptop. Note: Administrator rights is needed for software and driver installation. ST will provide the required STM32 development boards and software. SPACE IS LIMITED FOR THIS SESSION – FIRST COME, FIRST SEATED.

**The STM32MP1 Discovery kits must be returned after the session.**

## Learning Objectives:
In this workshop, you will learn how to:

### Part 1

- Learn about the [STM32MP1 Discovery Kit](https://www.st.com/en/evaluation-tools/b-l475e-iot01a.html) development board
- Power up OpenSTLinux on the STM32MP1, detect the WiFi IP address and connect to the device via ssh
- Run the Environmental Sensor programs to observe temperature, humidity, acceleration and gyroscope information
- Connect your browser to Node-RED running on the STM32MP1 OpenSTLinux
- Send STM32MP1 Discovery Kit data to [Watson IoT Quickstart](https://quickstart.internetofthings.ibmcloud.com/#/)

### Part 2
- Create an IoT Starter Kit application running in IBM Cloud
- Launch the Watson IoT Starter application
- Open the Watson IoT Platform so that you can send/receive data from the STM32MP1 device
- Create a STM32MP1 device type and device
- Configure the Node-RED visual programming editor
- Secure your Node-RED Editor in IBM Cloud
- Install additional Node-RED nodes
- Import a prebuilt flow from GitHub
- Create a new Node-RED flow and configure IoT Nodes
- Output the ST Microelectronics STM32MP1 temperature and humidity data
- Work with JSON data and observe the sensor results in the Debug sidebar
- Create a Node-RED Dashboard
- Experiment with Chart types
- Plot Real Time sensor data
- Trigger alerts when the real-time sensor data exceeds a threshold value
- Create a Node-RED flow that uses the Cloudant node
- Format a time series database record
- View Cloudant databases
- Read datasets from a Cloudant database
- Create a chart of historical data

### Part 3
- Set up a new Watson Studio Project
- Create a Jupyter Notebook
- Create Training Data for our machine learning mode
- Read data from a Cloudant DB into Spark
- Use a Logistic Regression algorithm to calculate model coefficients
- Use Node-RED in the cloud to send the model coefficients to Node-RED on the edge
- Node-RED on the edge will apply the model to incoming sensor data and make a prediction if the sensor is being held.

## Prerequisites
This tutorial can be completed using an IBM Cloud Lite account.

* Create an [IBM Cloud account](https://ibm.biz/BdzgST)
* Log into [IBM Cloud](https://cloud.ibm.com/login)

## Part 1

### Section 1 - Unbox the STM32MP1 Discovery Kit development board

This section shows you how to unpack the STM32MP1 Discovery Kit development board and connect the Sensor expansion board. Then insert the provided SD Card with the OpenSTLinux image.

- Instructions : [Unpack the STM32MP1 Discovery Kit](part1/UNBOX.md)

### Section 2 - Power up OpenSTLinux and connect to the STM32MP1

This section shows you how to power up OpenSTLinux on the STM32MP1, detect the WiFi IP address and connect to the device via ssh

- Instructions : [Connect to the STM32MP1](part1/POWERUP.md)

### Section 3 - Run the Environmental Sensor programs

This section shows you how to run the Environmental Sensor programs to observe temperature, humidity, acceleration and gyroscope information

- Instructions : [Environmental Sensor Data](part1/SENSORDATA.md)

### Section 4 - Connect to Node-RED running on the STM32MP1 OpenSTLinux

This section shows you how to connect your browser to Node-RED running on the STM32MP1 OpenSTLinux

- Instructions : [Node-RED on the STM32MP1](part1/EDGE-NODERED.md)

### Section 5 - Send STM32MP1 Discovery Kit data to Watson IoT Quickstart

This section shows you how to send STM32MP1 Discovery Kit data to [Watson IoT Quickstart](https://quickstart.internetofthings.ibmcloud.com/#/)

- Instructions : [Send Sensor Data to Quickstart](part1/EDGE-QUICKSTART.md)

## Part 2

### Section 6 - Create an Internet of Things Platform Starter application

- Instructions : [Create an Internet of Things Platform Starter application](part2/CREATEIOTP.md)

### Section 7 - Create a Watson IoT Platform Device Type and Device

- Instructions : [Create a Watson IoT Platform Device Type and Device](part2/DISCOVERYDEVICE.md)

### Section 8 - Node-RED Set up and Configuration in IBM Cloud

- Instructions : [Node-RED Set up and Configuration in IBM Cloud](part2/NODERED.md)

### Section 9 - Send Sensor Data from Node-RED Edge to Node-RED Cloud

- Instructions : [Send Sensor Data from the Edge to IBM Cloud](part2/SENDEDGE.md)

### Section 10 - Receive Discovery Kit Environmental Sensor Data in Node-RED

- Instructions : [Receive Discovery Kit Environmental Sensor Data in Node-RED](part2/DISCOVERYIOTDATA.md)

### Section 11 - Node-RED Dashboard Charts - Plot Environmental Sensor Data

- Instructions : [Node-RED Dashboard Charts - Plot Environmental Sensor Data](part2/DASHBOARD.md)

### Section 12 - Store Data in Cloud Storage for Historical Data Analytics

- Instructions : [Store Data in Cloud Storage for Historical Data Analytics](part2/CLOUDANT.md)

### Section 13 - Node-RED Charts of Historical Sensor Data

- Instructions : [Node-RED Charts of Historical Sensor Data](part2/HISTORY.md)

## Part 3

### Section 14 - Watson Studio Set up and Configuration in IBM Cloud

This section shows you how to deploy the Watson Studio service and how to create your first Jupyter Notebook.

- Instructions : [Watson Studio Set up and Configuration in IBM Cloud](part3/STUDIO.md)

### Section 15 - Create training data

This section shows you how to create the training data needed to create a model so you will be able to determine what is happening from the sensor data.

- practical [Training Data](part3/TRAINING.md)

### Section 16 - Jupyter Notebook Analytics - Create model

This section shows you how to use the training data to create a model that can then be used to classify actions.

- practical [Jupyter Notebook - STM32MP1](part3/JUPYTER.md)

### Section 17 - Send and Run the model on the STM32MP1 Edge device

This section takes the output from the Jupyter Notebook and implements the trained model on the STM32MP1 Edge device.

- practical [Implement model on STM32MP1](part3/MODEL.md)

## Workshop summary

This section summarizes what the workshop covered and also provides some useful links for further exploration of Edge, IoT and Data Science

- [Summary and links](part3/SUMMARY.md)

## License

This workshop and code examples are licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](http://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)

*Quick links :*
[Home](/README.md) - [Part 1](../part1/README.md) - [Part 2](../part2/README.md) - [Part 3](../part3/README.md)
***
