=======
MPS-CAN Analyzer
=======
MPS-CAN Analyzer is a response time analyzer for Mixed Periodic and Sporadic messages in Controller Area Network (CAN). 
It implements a number of response-time analyses for CAN addressing various queueing policies, buffer limitations in the CAN controllers, and various transmission modes implemented by higher-level protocols for CAN. It also integrates the response-time analysis for Ethernet AVB and CAN-to-Ethernet AVB Gateway.

=======
MPS-CAN Analyzer Ver. 1.1
=======
How to get started?
=======
1.	Provide the network speed for CAN in bits per second. If the intended speed is 250Kbps then 250000 should be entered.

2.	Select one of the two network speeds (10 Mbit/s or 100 Mbit/s) for Ethernet.

3.	Select the percentage bandwidth reservation for Class A and Class B traffic in Ethernet AVB.

4.	Create a new node by clicking the “New Node” button. Specify various parameters such as CAN node, Ethernet node or a gateway.

5.	After creating the nodes, create CAN messages by clicking the “New CAN Message” button. Enter the required parameters. Alternatively, Test-Input-for Version1.1.dat can also be loaded that contains a set of 50 CAN messages from one of the case studies.

6.	Create Ethernet messages by clicking the “New Ethernet Message” button. Enter the required parameters. 

7.	Click the “Analyze” button to calculate the worst-case response times of CAN messages, Ethernet messages, CAN-to-Ethernet global messages and the network utilization.

=======
MPS-CAN Analyzer Ver. 0.2
=======
How to get started?
=======

1.	Provide the network speed in bits per second. If the intended speed is 250Kbps then 250000 should be entered.

2.	Create a new node by clicking the “New Node” button. Specify the type of transmit buffers used in the CAN controller of the node. There are six nodes in the test input. Hence, six nodes should be created with any choice of transmit buffers.

3.	After creating the nodes, create messages by clicking the “New Message” button. Enter the required parameters. Alternatively, you can also load messages from the test file “JSA-WATERS-81.dat”. This file includes 81 messages out of which 27 are periodic, 27 are sporadic, and the remaining 27 are mixed.

4.	Click the “Analyze” button to calculate the worst-case response times of messages and network utilization.
