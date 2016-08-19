# live-analytics-using-mapreduce-over-iot
A concept about live analytics using mapreduce pattern over the Internet of Things

From the time being, people's not only talking about Stream Analytics (Real-time Analytics) but also deploying solutions and products using the technology around BigData, IoT and Cloud Computing in their enterprise companies everywhere. The concept of the existing solution can explain by this diagram:
```
Confidentials  ----> +-----------+    +------------------+                       /---> Users
Sensors' Data  ----> | IoT/Data  |====| Streaming Data   |----> Application 1---/
Clickstreams   ----> | Ingestion |====|    Analytics     |----> Application 2--------> Machines
Social Data    ----> |    Hub    |====| Machine Learning |----> Application 3---\
Other sources  ----> +-----------+    +---||||||||||||---+            o          \---> Environments  
                                          VVVVVVVVVVVV                |
                                      +---||||||||||||---+         |
                                      |      Data OS     |o--------o
                                      |   Big Data Lake  |
+-------------------------------------+   Distributed FS +----------------------------------------------+
| 01100010000010010101010101010100100111011101010101010101011010010101010101010101001010111111000001010 |
```
