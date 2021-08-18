# Crypto102
```
angstromCTF2016: artifact-20
ROT47
PicoCTF_2018-caesar cipher 2
Vigenère cipher
School CTF 2015: affine-cipher-100(教)
```
## angstromCTF2016: artifact-20
```
While exploring ancient ruins, a strange message was found.
Can you crack the message?

ciphertext.txt
```
```
"gxipzhx qs kpz ravv mbgp gxs jmgk pe lps:
gxipzhx qs kpz ravv mbgp sgsibac ramb:
gxipzhx qs aqpbh gxs rsprcs cpvg epi aks.
fzvgmjs gxs epzbnsi pe qk eauimj qposn:
gp isai qs lav gxs gavt pe rplsi nmombs,
vzrisqsvg lmvnpq, abn rimqsoac cpos.
usepis qs gxmbhv jisags lsis bpbs, vaos gxmbhv
sgsibac, abn sgsibac m vxacc sbnzis.
acc xprs auabnpb, ks lxp sbgsi xsis."

gxs ecah mv jcavvmjv_ais_aclakv_mb_vgkcs
```

## ROT47
```
你知道下列文字如何解密嗎？

qC62<p{{r%uL(92E0`D0#_%cfnm]kN
```
## PicoCTF_2018-caesar cipher 2
```
Can you help us decrypt this file message?
We believe it is a form of a caesar cipher.

ciphertext
```
```
e^Xd8I;pX6ZhVGT8^E]:gHT_jHITVG:cITh:XJg:r
```
```
https://ctftime.org/writeup/11759

x="4-'3evh?'c)7%t#e-r,g6u#.9uv#%tg2v#7g'w6gA"
s=''
for i in x:
    
    if(ord(i)<=65):
        s+=chr(ord(i)+60)
    else:
        s+=chr(ord(i)-34)
print(s)
```
## Vigenère cipher
```
Crack the cipher: vhixoieemksktorywzvhxzijqni

Your clue is:

"caesar is everything. But he took it to the next level."

Vigenère cipher

https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher

參考看看: https://www.guballa.de/vigenere-solver
Pragyan CTF 2016 : I Agree
```
## School CTF 2015: affine-cipher-100(教)
```
Decrypt the message, which was encrypted with following rules:

for each letter of cipher text its position in the alphabet is the position of the original letter 
multiplied by 4 and shifted by 15 character

shift over alphabet is cyclic, so 'z' shifted by 1 is '' and '' shifted by 1 is 'a'

aplhabet consists of letters from 'a' to 'z' and symbol '_'

letter 'a' has position 0, symbol '_' has position 26 (following 'z')

Encrypted message: ifpmluglesecdlqp_rclfrseljpkq
```

