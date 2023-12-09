# prompt
Install and run pyang
```
$ sudo apt install libxml2-dev libxslt1-dev
$ sudo pip3 install -U lxml pyang
$ cp ~/iot/lesson9/intrusiondetection.yang ~/demo
$ cd ~/demo
$ cat intrusiondetection.yang
$ pyang -f yin -o intrusiondetection.yin intrusiondetection.yang
$ cat intrusiondetection.yin
$ pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef
$ cat intrusiondetection.uml
```

Install PlantUML

```
$ sudo pip3 install -U plantuml
```
Run PlantUML to create a sequence diagram in PNG
```
$ python3 -m plantuml intrusiondetection.uml
```

Install and run GIMP and Pinta to display a PNG file via VNC Viewer
```
$ cd
$ sudo apt update
$ sudo apt install gimp pinta
$ cd ~/demo
$ pinta intrusiondetection.png
$ gimp -h
$ gimp -a intrusiondetection.png
```

# Results

- Install and run pyang
 ![image](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image.png)
 ![image1](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image1.png)

- Install PlantUML
![image2](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image2.png)

- Install and run GIMP and Pinta to display a PNG file via VNC Viewer
![image3](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image3.png)
![image4](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image4.png)
![image5](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image5.png)
![image6](https://github.com/LMBernal/CPE322/blob/main/labs/lab%209%20-YANG/images/image6.png)
