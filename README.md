## EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
### DATE :17-04-2023

### AIM :

To write the python program for simulating Traceroute command.

### ALGORITHM :
```
1.Start the program.
2.Get the frame size from the user.
3.To create the frame based on the user request.
4.To send frames to server from the client side.
5.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
6.Stop the program
```
### PROGRAM :
```
Developed By: Vishwa Rathinam S
Reg No:212221240063
```
```py
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
### OUTPUT :

![image](https://user-images.githubusercontent.com/122860624/243070320-ea501bef-0826-4654-8c50-f3d582bc127c.png)

### RESULT :

Thus, the python program for simulating Traceroute command was successfully executed.

