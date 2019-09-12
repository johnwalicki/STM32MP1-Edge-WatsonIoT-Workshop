*Quick links :*
[Home](/README.md) - [Unbox your STM32MP1 Discovery Kit](UNBOX.md) - [PowerUp](POWERUP.md) - [Connect to Node-RED](EDGE-NODERED.md) - [Send Data to QuickStart](EDGE-QUICKSTART.md)
***
# STM32MP1

The [STM32MP157C-DK2 Discovery kit](https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mcu-mpu-eval-tools/stm32-mcu-mpu-eval-tools/stm32-discovery-kits/stm32mp157c-dk2.html) leverages the capabilities of STM32MP1 Series microprocessors to allow users easily develop applications using STM32 MPU OpenSTLinux Distribution software for the main processor and STM32CubeMP1 software for the co-processor.


The Discovery Kit includes LEDs, push-buttons, one Ethernet 1-Gbps connector, one USB Type-CTM OTG connector, four USB Type-A Host connectors, one HDMI® transceiver, one stereo headset jack with analog microphone, and one microSDTM connector.
To expand the functionality of the STM32MP157C-DK2 Discovery kit, two GPIO expansion connectors are also available for ARDUINO® and Raspberry Pi® shields.
Additionally, the STM32MP157C-DK2 Discovery kit features an LCD display with a touch panel, and Wi-Fi® and Bluetooth® Low Energy capability.

There is extensive documentation available in the [ST Micro wiki STM32MP157C landing page](https://wiki.st.com/stm32mpu/wiki/Getting_started/STM32MP1_boards/STM32MP157C-DK2)

Complete [Getting Started instructions](https://wiki.st.com/stm32mpu/wiki/Getting_started/STM32MP1_boards/STM32MP157C-DK2/Let%27s_start/Unpack_the_STM32MP157C-DK2_board) are available but this page will introduce the basics.

![STM32MP1 Discovery Kit](
https://wiki.st.com/stm32mpu/nsfr_img_auth.php/thumb/a/a1/STM32MP157C-DK2_angle2.jpg/600px-STM32MP157C-DK2_angle2.jpg)

Flip over the STM32MP1
![STM32MP1 bottom](https://wiki.st.com/stm32mpu/nsfr_img_auth.php/thumb/f/f8/STM32MP157C-DK2_verso.jpg/600px-STM32MP157C-DK2_verso.jpg)

## Connect the X-NUCLEO-IKS01A2 motion MEMS and environmental sensor expansion board

Underneath the STM32MP1,line up the pins and plug in the [X-NUCLEO-IKS01A2 motion MEMS and environmental sensor expansion board](https://www.st.com/en/ecosystems/x-nucleo-iks01a2.html) to the Arduino connector layout.
![IKS01A2](https://www.st.com/bin/ecommerce/api/image.PF263919.en.feature-description-include-personalized-no-cpn-medium.jpg)

## IKS01A2 Environmental Sensor Board Key Features

- LSM6DSL MEMS 3D accelerometer (±2/±4/±8/±16 g) and 3D gyroscope (±125/±245/±500/±1000/±2000 dps)
- LSM303AGR MEMS 3D accelerometer (±2/±4/±8/±16 g) and MEMS3D magnetometer (±50 gauss)
- LPS22HB MEMS pressure sensor, 260-1260 hPa absolute digital output barometer
- HTS221: capacitive digital relative humidity and temperature

## Insert the SD Card

- Insert the SD Card
  ![SD Card](https://wiki.st.com/stm32mpu/nsfr_img_auth.php/thumb/f/f8/STM32MP157C-DK2_verso.jpg/600px-STM32MP157C-DK2_verso.jpg)

## Cabling

### Serial Monitor Cable
- Find the provided USB-A to Micro-USB cable
- Connect the USB-A to your laptop
- Connect the Micro-USB to the STM32MP157C-DK2 (1)

### Power Cable
- Find the provided USB-A to USB-C cable
- Connect the USB-A to your laptop
- Connect the USB-C to the STM32MP157C-DK2 (2)

![STM32MP1 cabling](/screenshots/STM32157C-cables.png)
