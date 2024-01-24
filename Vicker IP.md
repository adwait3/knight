# Vicker IP
### PROBLEM
Hi! It's good to see you again in my networking series. There are total 18 challenges in this series & based on real life events of how can a server be compromised. Please download the attachment which will be used to answer all the questions. Don't make it too complex. Just keep it simple. Hope you'll solve them all. Wish you all a very good luck.

Scenario: Recently one of Knight Squad's asset was compromised. We've figured out most but need your help to investigate the case deeply. As a SOC analyst, analyze the pacp file & identify the issues.

So let's start with the basic.

attachment - https://drive.google.com/file/d/1UmBdh3fN3PVVMYbeMphIvM_Hs6-A4Atf/view


What is the victim & attacker ip?

Flag Format: KCTF{victimIp_attackerIp}

### SOlution
this one was fairly easy we just needed to find the victim ip and attacker ip and i used wireshark for it.
![Screenshot from 2024-01-25 01-01-06](https://github.com/adwait3/knight/assets/148553626/06ee2882-3d76-4a7d-a9e3-d0d9e43dd6e1)
attack from ip 192.168.1.7 to 192.168.1.8

### FLAG
KCTF{192.168.1.8_192.168.1.7}
