MPS-CAN Analyzer Ver 0.2
=======

MPS-CAN Analyzer: Response time analyzer for Mixed Periodic and Sporadic messages in Controller Area Network (CAN). 
It implements a number of response-time analyses for CAN addressing various queueing policies, buffer limitations in the CAN controllers, and various transmission modes implemented by higher-level protocols for CAN.

How to get started?
=======

1.	Provide the network speed in bits per second. If the intended speed is 250Kbps then 250000 should be entered.

2.	Create a new node by clicking the “New Node” button. Specify the type of transmit buffers used in the CAN controller of the node. There are six nodes in the test input. Hence, six nodes should be created with any choice of transmit buffers.

3.	After creating the nodes, create messages by clicking the “New Message” button. Enter the required parameters. Alternatively, you can also load messages from the test file “JSA-WATERS-81.dat”. This file includes 81 messages out of which 27 are periodic, 27 are sporadic, and the remaining 27 are mixed.

4.	Click the “Analyze” button to calculate the worst-case response times of messages and network utilization.
