# TorSubScan 

<h6>Author : RKT</h6>

![Screenshot_2020-12-28_09-01-50](https://user-images.githubusercontent.com/69615463/103188282-d1d86180-48ed-11eb-899d-6882ba04e6bd.png)


TorSubScan is a Tor Network Subdomain Scanner Tool.Its build on python program.It can help to scan any site subdomain from tor network.


### Setup ###


+ sudo apt install tor
+ sudo apt install torsocks
+ sudo pip install -r requirements.txt

### Tor Network(start) ###

+ sudo service tor start

### Terminal Command ###

+ git clone https://github.com/r3k4t/torsubscan.git
+ cd torsubscan
+ torify python3 torsubscan.py -h

### Example ###

+ torify python3 torsubscan.py -t google.com


![Screenshot_2020-12-28_09-05-53](https://user-images.githubusercontent.com/69615463/103188315-f2082080-48ed-11eb-8020-894d2c776cde.png)


+ torify python3 torsubscan.py -t google.com -o rkt.txt


![Screenshot_2020-12-28_09-09-35](https://user-images.githubusercontent.com/69615463/103188397-4d3a1300-48ee-11eb-88a9-c6c17ad33b1d.png)



### Tor Network Command(stop) ###

+ sudo service tor stop
