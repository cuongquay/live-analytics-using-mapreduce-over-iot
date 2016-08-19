# live-analytics-using-mapreduce-over-iot
A concept about live analytics using mapreduce pattern over the Internet of Things

From the time being, people's not only talking about Stream Analytics (Real-time Analytics) but also deploying solutions and products using the technology around BigData, IoT and Cloud Computing in their enterprise companies everywhere. The concept of the existing solution can explain by this diagram:
```
Confidentials  ----> +-----------+    +------------------+                       /---> Users
Sensors' Data  ----> | IoT/Data  |====| Stream/Realtime  |----> Application 1---/
Clickstreams   ----> | Ingestion |====|    Analytics     |----> Application 2--------> Machines
Social Data    ----> |    Hub    |====|  Data Processing |----> Application 3---\
Other sources  ----> +-----------+    +---||||||||||||---+        o  o  o        \---> Environments  
                                          VVVVVVVVVVVV            |  |  |
                                      +---||||||||||||---+        |  |  |
                                      |      Data OS     |o-------o--|--o
                                      |   Big Data Lake  |o-------o--o
+-------------------------------------+   Distributed FS +---------------------------------------------+
| 0110001000001001010101010101010010011101110101010101010101101001010101010101010100101011111100001010 |
```
