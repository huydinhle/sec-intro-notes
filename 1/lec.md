# Introduction to Cryptography

## Topics
- Classification 
- Basics / setup
- Subst-cipher
- Attack

# Classification
- Modern application of crytography
  - GNU PGP: encrypt texts
  - TruCrypt
  - SecureShell
  - (plugins) for thunderbird
  - S-MIME email enc
  - cell phone
  - hdcp-multimedia prot
  - bank cards
  - VPN
  - epassport
  - ipod
  - Kindle

### Cryptology
There are 2 branches
1. Cryptography: people trying to encrypt shits
  - Symetric algorithm
  - Asymetric algorithm
  - Protocols
2. Cryptanlysis: People trying to break shits

### What is the relationship between security and crytography
- Security is the super set of cryptography

# Setup for symetric cryptography

### Example
(simple) problem: communication over insecure channel

Alice              **communicate**                  bob
                  (Insecure channel)

What is the channel example in this picture
- Internet
- Air waves GSM, wifi
- ... etc

![overall-communication](pics/lec1-pic.png)

### Rules, and notations
- In practice, never use an untested crypt algorithm
- Notations
  -  x   == plain-text
  -  y   == cipher-text
  -  e   == encryption function
  -  d   == decryption function
  -  k   == key
  - |k| == key space(number of keys)

### What is secure channel
- A way to exchange the secret key
