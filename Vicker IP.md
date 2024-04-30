In `pcap` analysis, first thing I do is to see `protocol hierarchy`. Then I go to `ftp` section and select it.

![Pasted image 20240122190515](Pasted%20image%2020240122190515.png)

Here we can see that `ip - 192.168.1.7` is constantly trying to login in the server of `ip - 192.168.1.8` and failing.


![Pasted image 20240122190807](Pasted%20image%2020240122190807.png)

So my guess is  `ip - 192.168.1.7` is the attacker ip and `ip - 192.168.1.8` is the victim's ip.

The flag is :

`KCTF{192.168.1.8_192.168.1.7}`.





