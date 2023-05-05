Download Link: https://assignmentchef.com/product/solved-ece303-final-project-custom-protocol
<br>
This repository contains teaching material for ECE303._This API is subject to change and expansion!_

`channelsimulation.py` contains a simple API for a mock connection over an unreliable channel. `sender.py` and `receiver.py` are mock sender and receivers that use this unreliable channel. These are examples that do not properly handle the bit errors in the channel.

The channel simulator will simulate random bit errors, packet loss, and packet duplication.

## AssignmentThe goal of this project is to develop a transport layer protocol that can successfully and quickly transmit bits over this unreliable channel. The protocol will be implemented in your versions `sender.py` and `receiver.py`. Your implementations should inherit from the Bogo{Receiver,Sender} classes in from this repository and override the receive() and send() methods.

### RequirementsThe submitted sender and receiver implementations must be able to:* Sucessfully transfer data over the noisy channel* Be fast* Keep channelsimulator.py unchanged in any submitted code. You can play around with it while testing, but submissions will be rejected if you submit a changed channelsimulator.py* Can be done in up to groups of 3 people. Grading will be more difficult depending on the amount of people in the group.


