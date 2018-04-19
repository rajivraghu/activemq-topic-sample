Info:
In this example, we write messages to a topic and the topic has multiple subscribers. 

Steps:
1)Start Publish App - It has a subsciber (Subscriber1)
2)Start Subscriber App - It has a subsciber (Subscriber2)

Subscriber1 Output :

Sending message: hey all1 to: topic://keyki.topic
Subscriber1 recieved message : hey all1
Sending message: hey all2 to: topic://keyki.topic
Subscriber1 recieved message : hey all2
Sending message: hey all3 to: topic://keyki.topic
Subscriber1 recieved message : hey all3
Sending message: hey all4 to: topic://keyki.topic
Subscriber1 recieved message : hey all4
Press any key to exit.

Subscriber2 
Press any key to exit.
ERROR | Could not refresh JMS Connection for destination 'topic://keyki.topic' - retrying in 5000 ms. Cause: Could not connect to broker URL: tcp://localhost:61616. Reason: java.net.ConnectException: Connection refused: connect
Subscriber2 recieved message : hey all1
Subscriber2 recieved message : hey all2
Subscriber2 recieved message : hey all3
Subscriber2 recieved message : hey all4
