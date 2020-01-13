# TCP/IP basics 



## Agenda

* The layer model
* 2nd layer (IP)
* 3rd layer (TCP/UDP)
* Advance routing
* DNS



## The layer model 

Layer | Function            | protocols
----- |:------------------- |:------------------
4     | Application level communication        | http/s ftp smtp ssl dhcp ssh
3     | Transportation      | TCP  UDP
2     | Internet            | IP (v4 and v6) ICMP
1     | Link                | MAC(Ethernet, wifi...)


![](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/UDP_encapsulation.svg/390px-UDP_encapsulation.svg.png)


### Basic principles:

* Every layer provide services to the one above her and consume services from the one below
* Every Layer communicate with the parallel layer in the responding host
* Lower layers are abstract, so every layer "feel" it talks with the peer layer
  directly.  


## 2nd layer IP protocol 


## 3rd layer and the TCP and  UDP protocol

