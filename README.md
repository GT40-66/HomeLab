<h1>Home Lab - Main </h1>


<h2>Description</h2>
This project is currently ongoing and going to be lengthy. I may end up dividing this project into "parts" and linked to this main repo. My goal for this project was three fold: <br/>
1) Create my own lab to practice for my upcoming CompTIA CySA+ exam <br/>
2) Get hands on, real world experience with basic tools and open source software for cybersecurity <br/>
3) Create a more secure home environment <br/>
This project is one that will never truly be "finished" as security is something that constantly needs to be changed and upgraded. For now, I am starting small and learning the basics. Once I have a solid foundation set in place, I will dive deeper into each system and software and use the most out of them. Continue reading to see where I currently am in the process, tools I have used, and most importantly, my troubleshooting.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Pi-Hole</b> 
- <b>docker.io</b>
- <b>prometheus.io</b>
- <b>Grafana</b>
- <b>Node Exporter</b>
- <b>Oracle VirtualBox</b>
- <b>OpenDNS</b>



<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Ubuntu Desktop-Jammy</b>

<h2>Program walk-through:</h2>

<p align="center">
<h2>Pi-Hole:</h2> <br/> 
To begin this project, I started with the open-source software "Pi-Hole". If you are unfamiliar Pi-Hole acts as a DNS filter, meaning you connect Pi-Hole to your choice of upstream DNS server and your clients connect to the Pi-Hole IP address for their DNS. For this I chose to use OpenDNS for its ability to filter out URLs in its own GUI as a preliminary "defense". Setting up Pi-Hole took me far longer than it should have for one simple reason, I had my VM network set to NAT instead of Bridged Adapter. This error cost me hours of pain and troubleshooting that resulted in a 1 minute fix. Once I correctly set the VM network type, setting up Pi-Hole took all of 5 minutes to get up and running. 

<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
