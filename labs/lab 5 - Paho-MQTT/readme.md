# Prompt
- Study the GitHub [repository](https://github.com/kevinwlu/iot) Lesson 5 labs
- Install Paho-MQTT
- Change directory to the iot repository
- Update the repository with git pull
- Change directory to Lesson 5
- Run python3 subcpu.py on one Terminal
- Run python3 pubcpu.py on another
***
## Results
This was done on Raspberry Pi OS
```
$ sudo apt update
$ sudo apt install mosquitto mosquitto-clients
$ mosquitto_sub -h localhost -v -t "\$SYS/#"
```
![1A](https://github.com/LMBernal/CPE322/blob/main/labs/lab%205%20-%20Paho-MQTT/images/1A.png?raw=true)
![1B]([image_url](https://github.com/LMBernal/CPE322/blob/main/labs/lab%205%20-%20Paho-MQTT/images/1B.png?raw=true))
***
```
$ service mosquitto status
$ netstat -tln
```
![2B](https://github.com/LMBernal/CPE322/blob/main/labs/lab%205%20-%20Paho-MQTT/images/2A.png?raw=true)
***
Intall Paho and run code to subscribe on one terminal and publish on another
```
$ sudo pip3 install -U paho-mqtt
$ git clone https://github.com/eclipse/paho.mqtt.python.git
$ cd ~/iot/lesson5
$ python3 client.py
```
![3A](https://github.com/LMBernal/CPE322/blob/main/labs/lab%205%20-%20Paho-MQTT/images/3A.png?raw=true)
***
Terminal 1
```
$ python3 subcpu.py
```
Terminal 2
```
$ python3 pub.py
```
![5A](https://github.com/LMBernal/CPE322/blob/main/labs/lab%205%20-%20Paho-MQTT/images/5A.png?raw=true)






