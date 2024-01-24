# Oceanic
### Question
The ocean’s beauty is in its clear waters, but its strength lies in its dark depths.
Flag Format: KCTF{S0m3th1ng_h3re}
Attachment : [challenge.tar](https://drive.google.com/file/d/1zRNxWLBWDu7TiHAdxQrT_pRv8pR_bDqM/view?usp=sharing)

### Solution
in this challenge we had to first find the clue from the image and then the final flag from the .wav audio file.
![clue](https://github.com/adwait3/knight/assets/148553626/de65eee3-d898-42f9-8456-f31a6745699d)
i tried all , strings , and exiftool and found a encoded comment.
![Screenshot from 2024-01-24 23-13-14](https://github.com/adwait3/knight/assets/148553626/8ae62b79-17da-4e57-a04a-f6294dc77884)
then used magic on cyber ched to get the decrypted message from base 58 .
![Screenshot from 2024-01-24 23-14-04](https://github.com/adwait3/knight/assets/148553626/7bf27eae-80b4-44b8-bd35-f21b40a2109d)
which said "theoceanisactuallyreallydeeeepp"
first this clue didnt mean like much and i tried steghide , used a sound visualiser to get the spectogram , the ncame across a spoftware called deep sound , i figured that this was it as the clue said smth abt deep and indeed this was it. 
