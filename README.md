## Introduction ##
 The  scope  of  my  project “Smart  Street  Light  and  Bluetooth  Controlled  Car”  This  system  will deal   with   the   basic   robot   movement   functions,   as   well   as   user   interface,   Bluetooth communication,  serial    communication  between  the  robot and   the  Bluetooth  module.  Full implementation  of  the  code  both  for  the  robot  and  the  computer  shall  be  developed  in  this     project.  Whenever presence  is detected, the lights around it will glow at the normal (bright) mode. This would save a lot of energy     and also reduce cost of operation of the streetlights. During  this  period  the  average  population  on  the  streets  is  very  low     and  hence  the  concept  can been  implemented effectively. So,  most of the time, the  street  lights are on a dim  mode and go into     bright mode only if there is presence detected. Streetlights  are  an  integral  part  of  any  developing  locality.  They  are           present  on  all  major roadways  and  in  the  suburbs  too.  Every  day,  streetlights  are  powered  from  sunset  to  sunrise  at     full  strength, even when there  is  no one around. On a global scale,  millions of dollars are spent each  day  on  these  street         lights  to  provide  the  required electrical  energy.  The  maintenance  and replacement  costs  of  conventional  incandescent  bulbs   are  immense.  They  consume  a  lot  of electric power to function and their heat emissions are also quite high. All of this             contributes to greater demand of electricity production and consequently, more carbon dioxide emissions from powerhouses.  So,  along     with  unnecessary  light  pollution,  this  practice  causes  damage  to  our planet too. 
 
   ### What I have done in Project ###
   A simple and effective solution to this would be dimming the lights during off peak hours. Whenever presence  is detected, the lights around it will glow at the normal (bright) mode. This would save a lot of energy and also reduce cost of operation of the streetlights. The  duration  of  the  street  lights  is  from  6:00PM  to  6:00AM.During  this  period  the  average population  on  the  streets  is  very  low  and  hence  the  concept  can  been  implemented  effectively. So, most of the time, the street lights are on a off mode and go into bright mode only if there is presence detected.
 
   ### Application Instructions: ###

1. First make sure your HC-05 Bluetooth module is paired with your mobile. 
  The default password for pairing is “1234” or “0000”. Check the manual of Bluetooth module.  
![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/Capture.PNG)
  
![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/2.PNG)

2. Click on “SELECT DEVICE” icon to select paired Bluetooth module.

![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/3.PNG)

3. When  press “up  arrow”  it  sends  the  data “F”to  Bluetooth  module  connected  with  the   circuit. When microcontroller detects “F” the robot/robot car moves FORWARD.
4. When press “Down arrow”it sends the data “b”to Bluetooth  module  connected with the   circuit. When microcontroller detects “b” the robot/robot car moves REVERSE.
5. When press “LEFT ARROW” it sends the data “L”to Bluetooth module connected with the circuit. When microcontroller defects “L” the robot/robot car turns LEFT. 
6. When press “RIGHT ARROW” it sends the data “R” to Bluetooth module connected with the circuit. When microcontroller defects “R” the robot/robot car turns RIGHT.
7. When press “STOP” button which is in the centre of remote it sends the data“S” to the Bluetooth module connected with the circuit. When microcontroller defects “S” the robot/robot car gets stopped.
 
![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/4.PNG)

##  Robot Car Prototype: ## 
A  smart  phone  Android  operated  robot.  Now  here  is  a  simple  to  control  your  robot/robo  car using  Bluetooth  module  HC-06  and  Atmega8  microcontroller  with  your  android  Smartphone device.  The  controlling  devices  of  the  whole  system  are a  microcontroller.  Bluetooth  module, DC motors are interfaced to the microcontroller.  The  data  receive  by  the  Bluetooth  module  from  android  smart  phone  is  fed  as  input  to  the controller. The controller acts accordingly on the DC motor of the robot. The robot in the project can  be  made  to  move  in  all  the  four  directions  using  the android  phone.  The  direction  of  the robot is indicators using LED indicators of the Robot system. In the task the controller is loaded with program written using Embedded ‘ C’  Languages. Android smart phone controller Bluetooth robot using microcontroller.
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/5.PNG)                                                
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/6.PNG)
## Smart Street Light Prototype: ##
Streetlights are an integral part of any developing locality. They are present on all major roadways  and  in  the  suburbs  too.  Every  day,  streetlights  are  powered  from  sunset  to  sunrise  at full  strength, even when there  is  no one around. On a global scale,  millions of dollars are spent each  day  on  these  street  lights  to  provide  the  required  electrical  energy.  The  maintenance  and replacementcosts  of  conventional  incandescent  bulbs  are  immense.  They  consume  a  lot  of electric power tofunction and their  heat emissions are also quite  high.  All of this contributes to greater  demand ofelectricity production  and consequently,  more carbon dioxide  emissions  from powerhouses.  So,  along  with  unnecessary  light  pollution,  this practice  causes  damage  to  our planet too.
 ### Screenshots ###
 
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/7.PNG)
  
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/8.PNG)
  
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/9.PNG)
  
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/10.PNG)
  
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/11.PNG)
  
  ![Alt text](https://github.com/ashishrokr/smart-street-light-arduino/blob/master/12.PNG)


