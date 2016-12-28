---
title: UF0
category: MakerPro
bzurl: https://www.seeedstudio.com/UF0-STM32F0-Cortex-M0%2C-Arduino%26-Grove-compatible-Platform-p-2257.html
oldwikiname:  UF0
prodimagename:  Arduino_IDE_BestU_dir.jpgUF0.jpg
surveyurl: https://www.research.net/r/UF0
sku:   102990172
---
![](https://github.com/SeeedDocument/UF0/raw/master/img/Arduino_IDE_BestU_dir.jpgUF0.jpg)

##   Description

UF0 is all-in-one arduino-compatible prototyping platform powered by ST STM32F051C8T6. It also integrates with Seeed Studio grove 4-pin interface, which can be connected with major grove families, making prototype easier and faster. The TSC capacitive touch controller is the unique character for you to have fun with your finger, and it has 32bit timer and 12bit DAC,I2C, UART interfaces for extension.

Integrated with DC-DC Step-down power chip, it can provide highly efficient and stable power for the shields and other modules, especially suitable for those who want to build a product.

Arduino IDE for the software development, it makes your prototype start quickly and easily. It supports [grove starter kit](http://www.seeedstudio.com/depot/Grove-Starter-Kit-for-Arduino-p-1855.html?cPath=84_13)for Arduino from Seeed studio perfectly.

[![](https://github.com/SeeedDocument/Seeed-WiKi/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png)](https://www.seeedstudio.com/UF0-STM32F0-Cortex-M0%2C-Arduino%26-Grove-compatible-Platform-p-2257.html)

##   Specification

<table width="70%">
<tr>
<td>
<div style="margin: 0; margin-top:10px; margin-right:10px; padding: 0 1em 1em 1em; align:right;">
<div style="margin-left: 25px;">
<table>
<tr>
<td> * Size L x W
</td>
<td> 83.8 x 53.4mm
</td></tr>
<tr>
<td> * Processor
</td>
<td> ST STM32F051C8T6, 48MHz 32-bit ARM Cortex-M0 MCU
</td></tr>
<tr>
<td> * Memory
</td>
<td> 8KB SRAM, 64KB Flash
</td></tr>
<tr>
<td> * Working Voltage
</td>
<td> 3.3V
</td></tr>
<tr>
<td> * Input Voltage
</td>
<td> 7V-24V
</td></tr>
<tr>
<td> * Output Voltage
</td>
<td> 5V/2A 3.3V/500mA
</td></tr>
<tr>
<td> * Digital IO
</td>
<td> 14个(6*PWM)
</td></tr>
<tr>
<td> * Analog Output
</td>
<td> 6个(3.3V, 1 *DAC output)
</td>
<td>

</td></tr></table>
</div>
</div>

##   Feature

*   ARM-base 32-bit Cortex-M0 MCU with Low power consumption and good performance

*   Capacitive touch sensor with more fun

*   7-24V DC wide range input, high efficiency and powerful power supply

*   Arduino and Grove compatible with support for a rich set of third-party expansion boards
*   Dual UART and I2C (Grove Interface) for expansion boards

##   Pin Out Description

![](https://github.com/SeeedDocument/UF0/raw/master/img/UF0_CAD_V1.jpg)

##   Machine Dimension

![](https://github.com/SeeedDocument/UF0/raw/master/img/UF0_Dimensions_V1.jpg)

##   Program Environment

Arduino IDE and UF0 BSP can help you to program UF0，Below will introduce how to set up UF0 development environment built in Arduino IDE.

###   Download and Unzip Arduino IDE package

Arduino IDE download site：[http://downloads.arduino.cc/arduino-1.5.5-windows.zip](http://downloads.arduino.cc/arduino-1.5.5-windows.zip), you will see the directory below after download and unzip.

<table width="100%">
<dl><dd><div class="floatleft">![](https://github.com/SeeedDocument/UF0/raw/master/img/Arduino_IDE_Dir.jpg)</div>
</dd></dl>
<tr><td></td></tr></table>

<font color="red">**Note:** Arduino IDE should be arduino-1.5.5 or higher version.</font>

###   Download and install UFO BSP

*   Download the ZIP package
<dl><dd>

1.  Download UF0 BSP package from the site: [https://codeload.github.com/BestU/STM32_for_Arduino_BSP/zip/master](https://codeload.github.com/BestU/STM32_for_Arduino_BSP/zip/master)

2.  Put UF0 BSP under the directory "hardware" of Arduino IDE，and rename “BestU”.
</dd></dl>

*   Using git clone the latest version
<dl><dd>

1.  In the directory "hardware" of Arduino IDE execute the following command
</dd><dd> git clone [https://github.com/BestU/STM32_for_Arduino_BSP.git](https://github.com/BestU/STM32_for_Arduino_BSP.git) BestU
</dd><dd>You can now see the following in the "hardware":
</dd></dl>

![](https://github.com/SeeedDocument/UF0/raw/master/img/Arduino_IDE_hardware_dir.jpg)

</dd></dl>
<tr><td></td></tr></table>
<dl><dd>You can now see the following in the "BestU":
</dd></dl>

![](https://github.com/SeeedDocument/UF0/raw/master/img/Arduino_IDE_BestU_dir.jpg)

</dd></dl>
<tr><td></td></tr></table>

##   Start UF0

###   Install CP2102 driver

<dl><dd>using USB cable to connect UF0 with your PC，then the power LED on UF0 lights up, go and view the corresponding equipment and port number from windows device Administrators, like the below image:
</dd></dl>

![](https://github.com/SeeedDocument/UF0/raw/master/img/CP2102_Driver_en.jpg)

<tr><td></td></tr></table>
<dl><dd><font color="red">**Note:** It may need to install CP2102 driver for the first time,CP2102 driver download site: [http://www.silabs.com/Support%20Documents/Software/CP210x_VCP_Windows.zip](http://www.silabs.com/Support%20Documents/Software/CP210x_VCP_Windows.zip)</font>
</dd></dl>

###   Open Arduino IDE, choose UF0

![](https://github.com/SeeedDocument/UF0/raw/master/img/Arduino_IDE_UF0_en.jpg)
</dd></dl>
<tr><td></td></tr></table>

###   Choose Port number

![](https://github.com/SeeedDocument/UF0/raw/master/img/Arduino_IDE_UART_en.jpg)
</dd></dl>
<tr><td></td></tr></table>

##   Work with Grove Kit

Now UF0 can work with grove starter kit.

The kit includes some modules as below:

<dl><dd>1xBase Shield
</dd><dd>1xGrove - LCD RGB Backlight
</dd><dd>1xGrove - Smart Relay
</dd><dd>1xGrove - Buzzer
</dd><dd>1xGrove - Sound Sensor
</dd><dd>1xGrove - Touch Sensor
</dd><dd>1xGrove - Rotary Angle Sensor
</dd><dd>1xGrove - Temperature Sensor
</dd><dd>1xGrove - LED
</dd><dd>1xGrove - Light Sensor
</dd><dd>1xGrove – Button
</dd></dl>

How to use those modules, please visit this link:
[http://www.seeedstudio.com/wiki/index.php?title=Main_Page#Grove](/index.php-title=Main_Page#Grove "Main_Page#Grove") get more information.

##   UF0 Examples

-  [Touch example](http://wiki.seeedstudio.com/wiki/UFO_Touch_example)



##   Resources

-   [UF0 BSP(zip)](https://codeload.github.com/BestU/STM32_for_Arduino_BSP/zip/master)

-   [UF0 Overview(pdf)](http://www.bestni.com/en/uploads/soft/document/UF0%20Overview%20-%2020150112.pdf)

-   [UF0 Schematic(pdf)](http://www.bestni.com/en/uploads/soft/document/UF0%20Schematic%20V1.0.pdf)
