# live-analytics-using-mapreduce-over-iot
A concept about live analytics using mapreduce pattern over the Internet of Things

From the time being, people's not only talking about Stream Analytics (Real-time Analytics) but also deploying solutions and products using the technology around BigData, IoT and Cloud Computing in their enterprise companies everywhere. The concept of the existing solution can explain by this diagram:
```
+----- T1 ---------------- T2 ---------------- T3 ----------------- T4 ---------------- T5 ------------+      

Confidentials  ----> +-----------+    +------------------+                       /---> Users
Sensors' Data  ----> | IoT/Data  |====| Stream/Realtime  |----> Application 1---/
Clickstreams   ----> | Ingestion |====|    Analytics     |----> Application 2--------> Machines
Social Data    ----> |    Hub    |====|  Data Processing |----> Application 3---\
Other sources  ----> +-----------+    +---||||||||||||---+        o  o  o        \---> Environments  
                                          VVVVVVVVVVVV            |  |  |
                                      +---||||||||||||---+        |  |  |
                                      |      Data OS     |o-------o--|--o
                                      |   Big Data Lake  |o-------o--o
                      +---------------+   Distributed FS +---------------------+
                      | 011000|00001|10101|10010|11101|10101|10101|10101|010010|
                      | 000100|00011|10101|10101|10101|10100|01011|11100|01010 |
```
