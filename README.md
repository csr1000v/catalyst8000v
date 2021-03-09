# catalyst8000v

The purpose of this repo is to provide resources to connect a Cisco Catalyst 8000v to AnyConnect SSL VPN.



## SSL VPN Profile
The SSL VPN Profile is stored in an .xml file. This file is a template and the follow changes within the file need to be updated for a new setup:
1. The HostName in line 45 is currently `<HostName>Catalyst 8000v</HostName>`, which can be any string to name the new AnyConnect SSL VPN
<img width="428" alt="Screen Shot 2021-03-09 at 9 47 48 AM" src="https://user-images.githubusercontent.com/23649216/110514886-9e1f7200-80bc-11eb-960f-0eebcbaa5c1c.png">
2. The HostAddress in line 46 is currently `<HostAddress>52.183.63.10</HostAddress>`, which needs to be the IP address of a newly created Cisco Catalyst 8000v
