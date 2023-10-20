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

1A 1B add screent shots here
***
```
$ service mosquitto status
$ netstat -tln
```
2A add screen shot here
***
Intall Paho and run code to subscribe on one terminal and publish on another
```
$ sudo pip3 install -U paho-mqtt
$ git clone https://github.com/eclipse/paho.mqtt.python.git
$ cd ~/iot/lesson5
$ python3 client.py
```

3A
***
Terminal 1
```
$ python3 subcpu.py
```
Terminal 2
```
$ python3 pub.py
```







