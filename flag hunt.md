# FLAG HUNT
### PRoblem
Hunt your way through the challenge and Capture The hidden Flag!!!

Attachment 1- https://drive.google.com/file/d/1BXotCFeXqNuVC_vo_8uLss9OobIKHXnl/view

Flag Format: KCTF{S0m3th1ng_h3re}
### SOLUTION
while trying to open the zip file i learned that it was password protected so i used fcrackzip to bruteforce the password.
![Screenshot from 2024-01-24 23-43-12](https://github.com/adwait3/knight/assets/148553626/c8fdf758-6de7-4c22-9309-1ee33a2d18af)
this gave me the password "zippo123"
after unzipping the zip file i got 100s of files mostly images but one was different .
![Screenshot from 2024-01-24 23-53-28](https://github.com/adwait3/knight/assets/148553626/f1c70ffa-c7bd-45f1-9c23-f4d7aba2190a)
![Screenshot from 2024-01-25 00-03-45](https://github.com/adwait3/knight/assets/148553626/dcc4c9b7-7afd-4ff2-b744-7824560ad273)
these were not the flags i then listened to the wav file whoch was in morse for "MORSECODETOTHETESCUE!!"
after this i looked at the files  and realised most of them would just end up in me getting rickrolled. but one had to be diff i searched on how to differentiate between thes type of similar files and found file * this would be a little tedious to go through all the photos to differentiate but since all teh photos were exactly same it was easy to fine one different.

![Screenshot from 2024-01-25 00-07-45](https://github.com/adwait3/knight/assets/148553626/c1b9b825-ef73-42a9-bd3f-e954e198eca6)
so i found image 725 was diff .
so i used steghide and it asked for a password , i tried the one i got from the morse code in small letetrs morsecodetoherescue!! and sure enough that was it 
![Screenshot from 2024-01-25 00-12-14](https://github.com/adwait3/knight/assets/148553626/c5b8e183-65a7-46f3-aad3-eab62939b268)
i got a txt file cat it and got the flag
### FLAG
KCTF{3mb3d_53cr37_4nd_z1pp17_4ll_up_ba6df32ce}
