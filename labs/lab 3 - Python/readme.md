# Prompt

- Study the GitHub repository [Lesson 3 labs](https://github.com/kevinwlu/iot)
- Install required Python packages such as jdcal, astral, and geopy
- Do the following:
```
$ cd ~/iot
$ cd *3
$ python3 julian.py
$ python3 date_example.py
$ python3 datetime_example.py
$ python3 time_example.py
$ python3 sun.py 'New York'
$ python3 moon.py
$ python3 coordinates.py 'SC Williams Library'
$ python3 address.py '40.74480675, -74.02532862031404'
$ python3 cpu.py
$ python3 battery.py
$ python3 documentstats.py document.txt
```

## Results
This was completed on a Raspberry Pi

#### julian.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 julian.py
Calendar Date: 2023-10-14
Julian Date: 2460231.5
Modified Julian Date: 60231.0
```

#### date_example.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 date_example.py
Date: 2023-10-14
Date: 10-14-23
Day of Week: Saturday
Month: October
Year: 2023
43 days after the first day of classes
61 days before the last day of classes
```

#### datetime_example.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 datetime_example.py
2023-10-14 19:10:39.972065
2023-10-14 19:10:39.972353
2023-10-14 23:10:39.972404
1697325039.9724414
Sat Oct 14 19:10:39 2023
2023-10-14 19:10:39.972596
2023-10-14 23:10:39.972634
```

#### time_example.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 time_example.py
Sat Oct 14 19:11:33 2023
Sat Oct 14 19:11:43 2023
Sat Oct 14 19:11:53 2023

... and so on
```

#### sun.py 'New York'
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 sun.py 'New York'
Information for New York/USA

Timezone: US/Eastern
Latitude: 40.72; Longitude: -74.00

Dawn:    2023-10-14 06:38:01.260856-04:00
Sunrise: 2023-10-14 07:06:05.889351-04:00
Noon:    2023-10-14 12:42:10-04:00
Sunset:  2023-10-14 18:17:17.672962-04:00
Dusk:    2023-10-14 18:45:20.264814-04:00
```

#### moon.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 moon.py
2023-10-14 Moon Phase: 27
2023-10-15 Moon Phase: 0
2023-10-16 Moon Phase: 1
2023-10-17 Moon Phase: 2
2023-10-18 Moon Phase: 3
2023-10-19 Moon Phase: 4
2023-10-20 Moon Phase: 5
2023-10-21 Moon Phase: 6
2023-10-22 Moon Phase: 7
2023-10-23 Moon Phase: 8
2023-10-24 Moon Phase: 9
2023-10-25 Moon Phase: 10
2023-10-26 Moon Phase: 11
2023-10-27 Moon Phase: 12
2023-10-28 Moon Phase: 13
2023-10-29 Moon Phase: 14
2023-10-30 Moon Phase: 15
2023-10-31 Moon Phase: 16
2023-11-01 Moon Phase: 17
2023-11-02 Moon Phase: 18
2023-11-03 Moon Phase: 19
2023-11-04 Moon Phase: 20
2023-11-05 Moon Phase: 21
2023-11-06 Moon Phase: 22
2023-11-07 Moon Phase: 22
2023-11-08 Moon Phase: 23
2023-11-09 Moon Phase: 24
2023-11-10 Moon Phase: 25
2023-11-11 Moon Phase: 26
2023-11-12 Moon Phase: 27
```

#### coordinates.py 'SC Williams Library'
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 coordinates.py 'SC Williams Library'
Berkeley County Library, US 52, Moncks Corner, Berkeley County, South Carolina, 44600, United States
(33.1879204, -79.9998833)
```

#### address.py '40.74480675, -74.02532862031404'
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 address.py '40.74480675, -74.02532862031404'
Stevens Institute of Technology, Hoboken Newport Walkway- Hudson River Waterfront Walkway, Hoboken, Hudson County, New Jersey, 07030, United States
(40.744809599999996, -74.0252392276461)
```

#### cpu.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 cpu.py
The number of physical cores =  4
The number of logical CPUs =  4
The utilization per second as a percentage for each CPU
[4.0, 0.0, 4.0, 0.0]
[13.1, 9.0, 13.9, 5.9]
[2.0, 7.9, 0.0, 3.0]
[4.9, 8.0, 0.0, 3.0]
[3.0, 8.9, 0.0, 4.0]
[5.9, 8.0, 0.0, 0.0]
[5.9, 8.0, 0.0, 1.0]
[4.0, 8.1, 0.0, 0.0]
[4.0, 9.0, 0.0, 0.0]
[2.0, 8.9, 3.0, 0.0]
```

#### battery.py
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 battery.py
None
```

#### python3 documentstats.py document.txt
```
lbernal@aries:~/git/iot/iot/lesson3 $ python3 documentstats.py document.txt
Word Count: 1343
Top Ten Words: [('our', 26), ('their', 20), ('has', 20), ('he', 19), ('them', 15), ('these', 13), ('have', 11), ('we', 11), ('us', 11), ('people', 10)]
```


