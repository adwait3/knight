## Oceanic
&gt; The ocean&#39;s beauty is in its clear waters, but its strength lies in its dark depths.
Flag Format: KCTF{S0m3th1ng_h3re}

Attachment : [challenge.tar](https://drive.google.com/file/d/1zRNxWLBWDu7TiHAdxQrT_pRv8pR_bDqM/view?usp=sharing)

**Description**

Find the flag of wav file with using the clue image for solve the challenge

**Solve**

First we can go to [Aperisolve](https://www.aperisolve.com/), to find any interesting information of `clue.jpg`

![oceansolve](https://hackmd.io/_uploads/rJ8XLDstp.png)

We can see there a password `theoceanisactuallyreallydeeeepp` but it&#39;s for the wav file

After struggling sometime we found this [reference](https://ctftime.org/writeup/9638) which is using tool named `DeepSound`

![oceansolve2](https://hackmd.io/_uploads/S1XjIvjFa.png)

Got a flag.png after that, and i use binwalk

![oceansolve3](https://hackmd.io/_uploads/Sk0kvvsYT.png)

Open the flag.txt

![oceanflag](https://hackmd.io/_uploads/rJeZPDoF6.png)

```
KCTF{mul71_l4y3r3d_57360_ec4dacb5}
