<h1>Creating a VLAN and Viewing its Assignment to Port Mapping</h1>


<h2>Description</h2>
In this lab, I learned to create a VLAN (virtual local area networks) and view its assignment to port mapping. VLANs are logical subdivisions of a switch that segregate ports from one another as if they were in different LANs. VLANs offer another way to add a layer of separation between sensitive devices and the rest of the network.
<br />



<h2>Environments Used </h2>

- <b>Ubuntu 20.04.2 LTS</b> 
- <b>PuTTY SSH Client</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar click PuTTY SSH Client and proceed to put in the IP address, port number, click Telnet and then click open: <br/>
<img src="https://i.postimg.cc/5yvWdv72/Screen-Shot-2022-08-13-at-9-58-55-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the IOU1 terminal window type the following commands <br/>
1. configure terminal <br/>
2. vlan 10 <br/>
3. name ucertify <br/>
4. vlan 20 <br/>
5. name phone <br/>
6. end <br/>
<img src="https://i.postimg.cc/Z5mBQx70/Screen-Shot-2022-08-13-at-10-02-55-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the IOU1 terminal window type "show vlan" command to view VLAN assignment to port mapping <br/>
<img src="https://i.postimg.cc/5ykg3kqH/Screen-Shot-2022-08-13-at-10-03-58-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />






  
  
 

  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
