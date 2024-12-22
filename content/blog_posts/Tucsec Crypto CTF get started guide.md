---
title: Crypto CTF guide
date: 2024-12-19
draft: false
tags:
  - Crypto
  - Guide
  - CTF
---

!![Alternate Text](/images/intro.png)

##  Cryptography (crypto)

* **[ Overview ]**

Discover and exploit vulnerabilities in the implementations of cryptographic algorithms and protocols.

* **[ Tools ]**
	
	I would suggest building your own crypto ctf environment via virtual environments such as Mamba and conda, it would be easier to install python packages and specific versions of them as well as other cryptographic tools such as sage.

 * [PyCryptodome](https://www.pycryptodome.org) - A very fundamental python library to solve many crypto ctfs
 * [SageMath](https://www.sagemath.org/) - A fully functional framework to solve mathematical problems and crypto ctfs,
 * [Cyberchef](https://gchq.github.io/CyberChef/) - A great web app for quick encryption and encoding of well known algorithms.
 * [RSA CTF tool](https://github.com/RsaCtfTool/RsaCtfTool) - A great tool in your arsenal to solve quickly and easy standard RSA challenges.
 * [Crypto Attacks](https://github.com/jvdsn/crypto-attacks) - A library of many crypto attacks.

* **[ Challenges ]**
 * [Level 0 - Entry level]

 	* [Base64] (https://cryptohack.org/courses/intro/enc3/)
 	* [caesar](https://play.picoctf.org/playlists/17?m=133)
 	* [interencdec](https://play.picoctf.org/playlists/17?m=135)
 	* [Number Sequence](https://mysterytwister.org/challenges/level-1/number-sequence)
 	* [Beaver Code](https://mysterytwister.org/challenges/level-1/beaver-code)


 * [Level 1 - Beginner level]
 	* [New Caesar](https://play.picoctf.org/playlists/17?m=136)
 	* [Mind your Ps and Qs](https://play.picoctf.org/playlists/17?m=138)
 	* [Favorite Byte](https://cryptohack.org/courses/intro/xorkey0/)
 	* [Xor Key](https://cryptohack.org/courses/intro/xorkey1/)
 	* [krypton level 3-7](https://overthewire.org/wargames/krypton/krypton3.html)

 * [Level 2 - Medium level]

 	* [Mini RSA](https://play.picoctf.org/playlists/17?m=139)
 	* [rsa_oracle](https://play.picoctf.org/playlists/17?m=140)
 	* [ECB Oracle](https://cryptohack.org/courses/symmetric/ecb_oracle/)



* **[ References ]**
 * [CryptoHack](https://cryptohack.org/) - A great way to start your journey in cryptography and crypto ctf. It has dedicated courses to teach you the fundamentals about crypto.
 * [PicoCTF](https://picoctf.org/) - 
 * [CTF Primer](https://primer.picoctf.com/#_cryptography)
 * [OverTheWire](https://overthewire.org/wargames/krypton/) - The wargame krypton is a great start for substitution ciphers and frequency analysis technique.
 * [MysteryTwister](https://mysterytwister.org/) - A bit more difficult than the previous, it contains 4 levels of difficulty.


* **[ Friendly Advices ]**
 * Better to create a virtual environment (using mamba,conda)
 * The most important thing in crypto challenges is understanding the math behind the algorithm (Not the whole theory, only the necessary properties)
 *  In many cases, the vulnerability doesn't lie on the algorithm instead it is in the implementation of it.