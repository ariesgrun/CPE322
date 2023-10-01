# Prompt
Go to the [IoT repository](https://github.com/kevinwlu/iot)
- Study Lessons 1 and 2
- Open a terminal and do the following:
```
  $ hostname
  $ env
  $ ps
  $ pwd
  $ git clone https://github.com/kevinwlu/iot.git
  $ cd iot
  $ ls
  $ cd
  $ df
  $ mkdir demo
  $ cd demo
  $ nano file
  $ cat file
  $ cp file file1
  $ mv file file2
  $ rm file2
  $ clear
  $ man uname
  $ uname -a
  $ ifconfig
  $ ping localhost
  $ netstat
```

## Commands

- `hostname` - Shows the name of the device
```
C:\Users\aries>hostname
LAPTOP-NH80SL0V
```

- `env` - Shows the user's environment variables
```
C:\Users\aries>env
HOMEPATH=\Users\aries
LOCALAPPDATA=C:\Users\aries\AppData\Local
LOGONSERVER=\\LAPTOP-NH80SL0V

and so on...
```

- `ps` - Shows current active processes of the system
```
C:\Users\aries>ps
      PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAND
     1475       1    1475       3468  cons0     197609 23:47:07 /usr/bin/ps
```


- `pwd` - Shows the path of the working directory
```
C:\Users\aries>pwd
/c/Users/aries
```

- `git clone https://github.com/kevinwlu/iot.git` - Clones the github repository to the machine
```
C:\Users\aries\git>git clone https://github.com/kevinwlu/iot.git
Cloning into 'iot'...
remote: Enumerating objects: 21403, done.
remote: Counting objects: 100% (2452/2452), done.
remote: Compressing objects: 100% (749/749), done.
remote: Total 21403 (delta 1373), reused 2384 (delta 1320), pack-reused 18951
Receiving objects: 100% (21403/21403), 28.21 MiB | 29.88 MiB/s, done.
Resolving deltas: 100% (14072/14072), done.
```

- `cd iot` - Changed the directory to the iot folder
```
C:\Users\aries\git>cd iot

C:\Users\aries\git\iot>
```

- `ls` - Lists files and other directories located in the current working directory
```
C:\Users\aries\git\iot>ls
README.md  cases      health  lesson1   lesson2  lesson4  lesson6  lesson8  make      special_problems  systems
apps       economics  hype    lesson10  lesson3  lesson5  lesson7  lesson9  projects  standards         tools

```

- `cd` - changed the directory to the home directory
```
C:\Users\aries\git\iot>cd
C:\Users\aries>
```

- `df` - Shows the file system information (disk space)
```
C:\Users\aries>df
Filesystem         1K-blocks      Used Available Use% Mounted on
C:/msys64/mingw64x 480551236 431594092  48957144  90% /
```


- `mkdir demo` - creates a directory named "demo"
```
C:\Users\aries\lab2>mkdir demo
C:\Users\aries\lab2>ls
demo
```

- `mkdir demo` - changed the directory to the demo directory
```
C:\Users\aries\lab2>cd demo
C:\Users\aries\lab2\demo>
```

- `nano file` - initiates the nano text editor and creates a file called "file"
- `cat file` - shows the contents of a file called "file"
- `cp file file1` - copies the contents of "file" into "file1"
- `mv file file2` - moves the contents of "file" into "file2"
- `clear` - clears the screen (removes text already displayed)
- `man uname` - shows the manual for the uname command

- `uname -a` - shows all of the system information
```
C:\Users\aries>uname -a
MSYS_NT-10.0-19045 LAPTOP-NH80SL0V 3.4.3.x86_64 2023-01-17 21:17 UTC x86_64 Msys
```

- `ipconfig` - shows all of the network interfaces of the machine
```
C:\Users\aries>ipconfig

Windows IP Configuration

Wireless LAN adapter Local Area Connection* 10:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :


Wireless LAN adapter Wi-Fi:

and so on...
```

- `ping localhost` - sends packets to your own local network of your machine
```
C:\Users\aries>ping localhost

Pinging LAPTOP-NH80SL0V [::1] with 32 bytes of data:
Reply from ::1: time<1ms
Reply from ::1: time<1ms
Reply from ::1: time<1ms
Reply from ::1: time<1ms

Ping statistics for ::1:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 0ms, Average = 0ms
```

- `netstat` - Shows network statistics which displays routing tables, connections, and more
```
Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:00000         LAPTOP-EXAMPLE:00000  ESTABLISHED

and so on...
```
