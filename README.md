# Observer_Test

- Function test software for hardware with Indoor Positioning System ESP32

Beacons work one-way and send a signal of their unique ID number approximately every 0.1 seconds. Other devices with Bluetooth technology in the shooting range also capture this signal and recognize the Beacon. Then the system determines the position taking into account the signal strength. Beacons alone cannot track and locate users. In order to do this, a special application must be installed on the device. Thanks to this application, the system established mostly uses the RSSI technique to determine the location. There are four main Beacon standards. These are Apple's iBeacon, Google's Eddystone and UriBeacon and AltBeacon. Unlike the others, the iBeacon provided by Apple includes some code classes for more detailed positioning. These are UUID, Major and Minor. If the system is used in more than one building, the UUID contains the code of which building the Beacon belongs to, which floor the Major is on, and which room Minor is in...


Design by https://www.linkedin.com/in/musacufalci/
