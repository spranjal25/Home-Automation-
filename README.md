# Home-Automation


<br>
<br>


IoT based Home Automation Interface with a functioning Web-Application


a demo version (representative of the web application can be found [here](https://homieproject.github.io/), this does not need a username and password, you can just click on login and check how we have designed our web-application.

<br>
<br>


###               S P E C I F I C A T I O N S  
<br>
<br>

The system is based on Raspberry Pi and built using the RaspberryPi-3b, runs a verison of raspbian. The RPi is inturn coonected with nodes and communicate using [web-sockets](https://pusher.com/websockets) connected over the Internet using wifi.

Basic Functionalities take care of almost all the appliances in a Home, be it smart appliances (which can be directly connected via wifi) or usual appliances, for which we have interfaced a [NodeMCU](https://www.quora.com/How-does-NodeMCU-work) which makes each and every switch of your house to be connected over the internet using wifi.



the Application's Back-end takes care of the scheduling part as well, using the gerneralised clock which works in real time and is able to schedule all the connected appliances and devices successfully.



The Web Application is created using vanilla HTML5, CSS Bootstrap And Javascript functionalities and runs on a firebase server using the firebase noSQL database to store the data


<br>
<br>



###                     S C A L A B I L T Y  

<br>

future plans are to improve the security aspeccts of the System, interface with a proper authorization service.







