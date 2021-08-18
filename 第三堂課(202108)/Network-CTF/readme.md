#
```
file + strings + grep
TCP/UDP Follow Stream
Wireshark
Tshark
https
usb
```
```
https://github.com/HappyHackingHigh/CTF/blob/master/MyFirstSecurity/week11_NetworkForensics.md
```
# 題型
```
1.基本題型 ==> file + strings + grep
2.Follow UDP/TCP/SSL stream + base64|ROT13|..
3.封包中資料匯出==> 圖片 | txt | word| ...
               ==> 可結合隱寫術
               ==> 連線|資料
4.https
5.USB
6.不同協定的分析
7.攻擊封包分析 ==> ICMP Tunneling | DNS Tunneling 
   攻擊模式 ==> 示意圖
   攻擊封包分析
   
8.綜合題型 ==> Network + memory + VM Forensics
```

# Network-1

>* [檔案下載](https://drive.google.com/file/d/1XSle05IGFHmEBTDFK71nS1VwpQupy0Bj/view?usp=sharing)

```
strings ws1_2.pcapng |grep CTF
```
>* 題庫來源  BITSCTF 2017 : woodstock-1-10

# Network-2


>* [檔案下載](https://drive.google.com/file/d/1uyJsGCqQhI6crFxCaBO32BEU5xzDq7yV/view?usp=sharing)

```
Follow TCP stream
https://github.com/zst-ctf/angstromctf-2019-writeups/tree/master/Solved/Paper_Trail
```
```
Something is suspicious about defund's math papers. 
See if you can find anything in the network packets we've intercepted from his computer.
```
>* 題庫來源 angstromctf-2019/Paper_Trail

# Network-3

>* [檔案下載](https://drive.google.com/file/d/18pJIJNTWrypUm9t9M0EaSkp2_x9p7ade/view?usp=sharing)


```
Follow TCP stream  + ROT 13
PicoCTF2021-Writeup/Forensics/Wireshark doo dooo do doo/Wireshark doo dooo do doo.md

https://github.com/vivian-dai/PicoCTF2021-Writeup/blob/main/Forensics/Wireshark%20doo%20dooo%20do%20doo/Wireshark%20doo%20dooo%20do%20doo.md
```
```
Can you find the flag? 
```
```
Follow TCP stream 
Gur synt vf cvpbPGS{c33xno00_1_f33_h_qrnqorrs}
 ROT 13

picoCTF{p33kab00_1_s33_u_deadbeef}
```
>* 題庫來源 PicoCTF2021/Wireshark doo dooo do doo


# Network-4


>* [檔案下載](https://drive.google.com/file/d/1p30BIo2rVotwy-uzf4HRNqZWPMKQcz8I/view?usp=sharing)
```
Follow UDP stream

We found this packet capture. 
Recover the flag.
```
```
https://zomry1.github.io/shark-on-wire-1/
```
>* 題庫來源 PicoCTF2019/shark on wire 1

# Network-5

>* [檔案下載]()
```
 base64編碼
```
```

```
>* 題庫來源 Internetwache-CTF-2016:Network Forensic(MUST)



# Network-6

>* [檔案下載](https://drive.google.com/file/d/1_I7Ob8qaMcp8Gs-m6G7Avc5Q1o1qdzVd/view?usp=sharing)


```
We can get into the Administrator's computer with a browser exploit.
But first, we need to figure out what browser they're using.
Perhaps this information is located in a network packet capture we took: data3.pcap.
Enter the browser and version as "BrowserName BrowserVersion".

NOTE: We're just looking for up to 3 levels of subversions for the browser version 
(ie. Version 1.2.3 for Version 1.2.3.4) and ignore any 0th subversions (ie. 1.2 for 1.2.0)

Hint:
Where can we find information on the browser in networking data?
Maybe try reading up on user-agent strings.
```
```

```
>* 題庫來源 PicoCTF_2017: Special Agent User(MUST)

# Network-7


>* [檔案下載](https://drive.google.com/file/d/1wxWi7PyVGYsXgyj87L6gY7a92gssIGdT/view?usp=sharing)
```
As you're bumming around the Kuiper Belt, 
you catch an incoming transmission from a distant source.
They seem to be scanning the area, looking for something...
Maybe you should try to find it first.

Can you find the author who ....
```
```

```
>* 題庫來源 PicoCTF 2013 : Second Contact
```
https://github.com/ctfs/write-ups-2013/tree/master/pico-ctf-2013/second-contact
```


# Network-8 超讚  必教
>* [檔案下載](https://drive.google.com/file/d/1MoQ7MuJKdjkoah5eqVo9IvnxlprRVKHK/view?usp=sharing)
```
將封包中的檔案存起來
https://ithelp.ithome.com.tw/articles/10194979
```
```
https

TJCTF_2018/Ssleepy/
https://www.aperikube.fr/docs/tjctf_2018/ssleepy/
```
```

```
>* 題庫來源 

# Network-9

>* [檔案下載]()
```
USB Forensics
```

```
https://github.com/DavideRoss/pico-ctf-2017-writeups/tree/master/level-2/forensics/just-keyp-trying
```
>* 題庫來源 
# Network-10
```
33c3 CTF : exfil-100

https://github.com/zbetcheckin/33C3_CTF_2k16 �==> 使用 tshark
https://0xd13a.github.io/ctfs/33c3/exfil/


https://github.com/zbetcheckin/33C3_CTF_2k16
```
```

```
>* 題庫來源 
# 各種協定封包
##  Nuit du Hack CTF Quals 2016/ (RDP 封包)
```

```
```
https://ctftime.org/writeup/3015
```
# 攻擊封包分析
## Nuit du Hack CTF Quals 2016/Trololo [malware + IRC]
```
A computer belonging to a new company has been infected by a malware. 
This is a known version of a cryptolocker software, 
that uses a irc server to received commands. 
Let's try to grab its password...

The challenge is available at : http://static.quals.nuitduhack.com/trololo.pcap
缺封包
```
```
http://ctf.publog.jp/archives/cat_1207667.html
https://ctftime.org/writeup/3015
```
## ICMP Tunneling
```
PingHexFil
https://github.com/RackunSec/pinghexfil
```
