# live-analytics-using-mapreduce-over-iot
A concept about live analytics using mapreduce pattern over the Internet of Things

From the time being, people's not only talking about Stream Analytics (Real-time Analytics) but also deploying solutions and products using this technology around BigData, IoT and Cloud Computing in their enterprise companies. The concept of the overall existing solutions can be explained by this diagram:
```
_______ T1 ______________ T2 _________________ T3 _________________ T4 __________________ T5__________

Tagging Data   ----> +-----------+    +------------------+                        |---> People
Sensors' Data  ----> | IoT/Data  |====| Stream/Realtime  |----> Application 1 ----|
Clickstreams   ----> | Ingestion |====|    Analytics     |----> Application 2 ---------> Machines
Social Data    ----> |    Hub    |====|  Data Processing |----> Application 3 ----|
Other sources  ----> +-----------+    +---oooooooooiii---+        o  o  o         |---> Environments  
                                          ||||||||||||            |  |  |
                                      +---iiiiiiiiiooo---+        |  |  |
                                      |      Data OS     |o-------o--|--o
                                      |   Big Data Lake  |o-------o--o
                     +---------------+   Distributed FS  +--------------------+
                     | 011000|00001|10101|10010|11101|10101|10101|10101|010010|
                     | 000100|00011|10101|10101|10101|10100|01011|11100|010101|
```
All the data that come from users, things, mobiles or webs will be concentrated to a single entry point that usually called as a Data Hub or IoT Hub. Then the data stream moves toward to the Stream Analytics engine where as data may be filtered, manipulated, evaluated and routed to the downstream applications or services. The end of the stream are the consumer groups which is taking out the valued information from the source data to use in different purposes (attracted information, decision making, behavior reflections or data enrichment). 

Let's say we have a real scenario of picking up a car likes Uber does. The system must find the nearest cars around the messenger and make a contract between the messenger and the matched driver. This is the local maxima function in mathematical analysis. 
