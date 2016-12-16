# raspberrypiWithAlexa
Enable SSh: https://www.raspberrypi.org/documentation/remote-access/ssh/
Chicken Of the VNC:
When I ran the VNC Viewer on Windows, and specified the RPi IP address, I didn't realise you have to put the session ID on the end (either the :1 or the :2).

* Run Java client.
ssh pi@192.168.1.4 -X
Password: raspberry
Pass@123
cd /home/pi/Desktop/alexa-avs-sample-app/samples/javaclient
