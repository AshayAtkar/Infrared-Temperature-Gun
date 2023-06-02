# Infrared-Temperature-Gun
An Arduino based non - contact thermometer based on the concept of Stefan–Boltzmann law. An infrared sensor senses the amount of infrared radiations emitted by a body and conveys the information to the Arduino Pro Mini, which provides the temperature of the body towards which the laser points along with the ambient temperature on an OLED display.
# Components required and their description
1) IR Temperature sensor (MLX90614)
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/3d7c16fb-9892-4010-930a-312d8ee74f6f" alt="Image" width="250">

This is the sensing unit of our gun. It uses Infrared radiations for sensing the temperature. Every object and living being emits IR radiations and by Stefan–Boltzmann law the intensity of this emitted IR radiations is directly proportional to the fourth power of the temperature of the object or living being. Using this it converts the received IR radiations to electrical voltage which is given to Arduino Pro Mini for processing.

2) Arduino Pro Mini
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/b10eaa8a-e061-4e4f-82e5-0bca8e70f202" alt="Image" width="250">

The Arduino Pro Mini is a microcontroller board. It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, an on-board resonator, a reset button, and holes for mounting pin headers. This is the Brain of our Temperature Gun. It receives signals from the IR sensor, processes it and gives it to the OLED for displaying the ambient and object temperature to the user.

3) Organic light-emitting diode (OLED) display
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/bad2181c-84cc-4c87-ae94-5fd102829193" alt="Image" width="250">

This acts as an interface between User and Temperature gun . It converts digital signals from the Arduino to a readable form and gives information about Ambient temperature and Object temperature.

4) Battery Protector module
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/d0cfa01b-f807-4e9a-b79d-c575131404f9" alt="Image" width="250">

Battery Protector module allows us to charge battery of our Infrared temperature gun by a mobile charger. Also, it protects the battery from too high or low voltages while charging. It also protects the battery from overcharging.

5) Rechargeable Lithium Ion Battery (3.7V, 2500mAH) (To provide power to the required components) 
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/cc213078-647a-4b45-add4-69064dcad312" alt="Image" width="250">

6) Laser Diode (For pointing towards the object)
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/7328e15d-fe13-4e94-97a1-afd7ec7b3a55" alt="Image" width="250">

7) Push Switch (For switching on the Temperature Gun)
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/1edb6642-9e5e-4b9e-bc8a-1aff9683799f" alt="Image" width="250">

# Circuit diagram
<img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/f8cd8974-20cb-40f0-95a9-70ad5e1a7922" alt="Image" width="350">

# Some images of Infrared temperature gun
<table>
  <tr>
    <td align = "center">
      <img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/9d99294d-7daa-4e92-a7ac-25f46b8a6b79" alt="Image 1" style="width: 50%;" />
    </td>
    <td align = "center">
      <img src="https://github.com/AshayAtkar/Infrared-Temperature-Gun/assets/120382546/bcbd0d7e-aa4a-4888-a0ec-1ba93b492b9c" alt="Image 2" style="width: 50%;" />
    </td>
  </tr>
</table>
