MPS-CAN
=======

MPS-CAN Analyzer: Response time analyzer for Mixed Periodic and Sporadic messages in Controller Area Network

How to get started?
=======

1.  Select the base analysis. Only “priority based” analysis is included in this release.

2.	Provide the network speed in bits per second. If the intended speed is 250Kbps then 250000 should be entered.

3.	Select the number of nodes. For the test inputs, there are two nodes in the system.

4.	Either click “New Message” button to enter new message or click load button to load messages from the test file “10Msgs_Prio-based.dat”. This file includes 10 messages out of which 4 are periodic, 2 are sporadic, and 4 are mixed.

5.	Click the “Analyze” button to calculate the worst-case response times of messages and network utilization.

Note: - The implementation of optional analysis is ongoing.

