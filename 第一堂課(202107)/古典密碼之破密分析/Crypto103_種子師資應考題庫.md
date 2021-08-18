# 種子師資應考題庫
```
底下題目提供各位有意擔任未來種子師資(教老師的老師)的先進製作教學簡報與實力展示用
無意擔任種子師資的教師也歡迎試看看
```

## 補充題1
```
picoCTF-2019/13
Cryptography can be easy, do you know what ROT13 is? 
cvpbPGS{abg_gbb_onq_bs_n_ceboyrz}
```

## 補充題2
```
連豬圈裏的豬都會的密碼
```
![cipher](./pic/cipher.png)

## 補充題3
```
希伯來 Atbash 之謎

uozt{S H W 2021}
```


## 補充題4
```
AngstromCTF 2019/Classy Cipher

Every CTF starts off with a Caesar cipher, but we're more classy.

Author: defund

from secret import flag, shift

def encrypt(d, s):
	e = ''
	for c in d:
		e += chr((ord(c)+s) % 0xff)
	return e

assert encrypt(flag, shift) == ':<M?TLH8<A:KFBG@V'
```



