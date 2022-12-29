# Incubator-embeded-system<br>
![image](https://user-images.githubusercontent.com/62056954/209951417-58534234-2cee-4f2e-9969-c3de2112df74.png)
An egg incubator has the following modules:
<br>1.Temperature and Humidity sensors (DHT11  modules)
  <br> 2. circulation fan.(dc Fan motor)
  <br> 3.Egg turner.(servo)
  <br> 4.Real time Clock.
  <br> 5.Display(oled 12c screen and leds)
  <br>6.Input buttons.
  <br> 7.Heater control either using a relay or triac.
  <br> 8.Humidity control.<br>
Aim of the code is to design an automatic incubator embeded system to do the following.
<br>1.Maintain a temperature of 37.5 degree celsius and 50% humidity from day 1 to day 17 and turn the eggs 10 times daily 180 degrees.
  <br>To maintain temperature sensor temparature reading is used as feedback for a control loop to turn on /off the heater.
  <br> maintain humidity the temperature humidity sensor is also used to control the fans and the humidifier.
<br>2.From day 18-21 temperature control should be sustained at 37.5 while humidity should be increased to 70% and egg turning should stop.
<br>3.The system should display on the OLED Display the temperature ,humidity and day count all the time not unless there is a failure where by it should display the word "ERROR" There are also two  leds when one lights blue means the eggs are being turned and the rest BIRG LED during normal operation should  be green except where theres failure it should display red . ![7f106eaa-8ecf-4c61-b420-a786ca8d8d95](https://user-images.githubusercontent.com/62056954/209956589-47cc6659-9137-4fe2-92b0-4af5c59b0f90.jpg)
![fab6836a-3611-4572-908a-388306ae1be3](https://user-images.githubusercontent.com/62056954/209956597-47e11138-3e24-4e48-bdbc-0854aeff6642.jpg)
