# PLD "Python - Network #0 & AirBnB clone - Deploy static & HTTPs & Load balancer & Firewall & Web stack debugging #2"

This file will cover mostly topics related web-server infrastucture and devops concepts.

## Participants

784 **Miguel Antonio Cortes Munoz [Github](https://github.com/miguel-dev) / [Twitter](https://twitter.com/Heuristicas)**
945 **Jose Guerra [Github](https://github.com/arq-gabo) / [Twitter](https://twitter.com/prototipo3d)**
972 **Laura Peralta [Github](https://github.com/LauraPeraltaV85) / [Twitter](https://twitter.com/darkmagier)**
931 **Edward Ortiz [Github](https://github.com/edward0rtiz) / [Twitter](https://twitter.com/edward0rtiz)**
922 **Daniel Rodriguez [Github](https://github.com/dr2d4) / [Twitter](https://twitter.com/dr2d4)**
940 **Paulo Morillo [Github](https://github.com/PauloMorillo) / [Twitter](https://twitter.com/PAULOMORILLO39)**

### Objectives

- _Define the concept of a load balancer?_
- _Search for HA Proxy and other load balancers_
- _Understand What is Roundrobin algorithm?_
- _Understand What is HTTPS SSL 2 main roles_
- _Identify the purpose of encrypting traffic_
- _Define SSL_
- _Clarify the firwall concept and if the ports are closed when it's installed the first time_
- _Understand Fabric_
- _Define deployment code to a server_
- _Understand a tgz archive_
- _Execute Fabric command locally_
- _Execute Fabric command remotely_
- _Transfer files with Fabric_
- _Manage Nginx configuration_
- _Understand Curl and OPTIONS_
- _Understand is the difference between root and alias in a Nginx configuration_

### Activities
**Concept socialization**  
**Whiteboarding** 

### Bottleneck
**Run Nginx with a non-privilege user**
**Configuration of the firewall**

### Conclusions
Be carefull when you are running software as root/superuser, test your bash scripts in a container before trying them in your server. 

It is always useful to encrypt your data, by having a SSL certificate. 
