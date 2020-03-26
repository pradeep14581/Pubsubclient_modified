# pubsubclient_modified
 
This is the modified PubsubClient library to support QoS 1 and Qos 2 
You can find the unmodified version of PubsubClient library.https://github.com/knolleary/pubsubclient

To test the QoS1 and QoS2, run the example project testPubSub.ino. output will look like following

.......
WiFi connected
IP address: 
192.168.225.87
connected
Publish message: hello world #1
 type 80
 Publish received at QOS2
 type 144
 type 80
 Publish received at QOS2
 type 112
 Published delivered to client successfully at QOS2
 type 112
 Published delivered to client successfully at QOS2
Publish message: hello world #2
 type 80
 Publish received at QOS2
 type 112
 Published delivered to client successfully at QOS2
Publish message: hello world #3
 type 80
 Publish received at QOS2
 type 112
 Published delivered to client successfully at QOS2
Publish message: hello world #4
 type 80
 Publish received at QOS2
 type 112
 Published delivered to client successfully at QOS2
Publish message: hello world #5
 type 80
 Publish received at QOS2
 type 112
 Published delivered to client successfully at QOS2
Publish message: hello world #6
