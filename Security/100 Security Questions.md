###### [source : sagarr525] (https://sagarr525.wordpress.com/2013/05/08/information-security-interview-questions/)

### 100 Top Computer Security Questions


#### 1- What is TLS ?
 
 TLS is a successor to Secure Sockets Layer protocol. TLS provides secure 
 communications on the Internet for such things as e-mail, Internet faxing, and other data transfers


#### 2- Difference between Raid0 vs Raid1 .

#### 3- What is two factor authentication ?


#### 4- What is Malware?

#### 5- What is a virtual memory ?

#### 6- Advantages of Virtualization .

#### 7- Difference between encoding, hashing and encryption.

Ans– At a very high level, all these 3 terms might appear to be similar and people often confuse between them. But each of the technique is distinct and has different use case. The purpose of encoding is to transform data so that it can be properly (and safely) consumed by a different type of system, e.g. binary data being sent over email, or viewing special characters on a web page. The goal is not to keep information secret, but rather to ensure that it’s able to be properly consumed. It does not require a key as the only thing required to decode it is the algorithm that was used to encode it. 

##### Examples: ASCII, Unicode, URL Encoding, Base64.

The purpose of encryption is to transform data in order to keep it secret from others. It uses a key, which is kept secret, in conjunction with the plaintext and the algorithm, in order to perform the encryption operation. 

##### Examples: AES, Blowfish, RSA. 

The purpose of hashing is to take arbitrary input and produce a fixed-length string that has the following attributes:

The same input will always produce the same output.
Multiple disparate inputs should not produce the same output.
It should not be possible to go from the output to the input.
Any modification of a given input should result in drastic change to the hash.

##### Examples- MD5, SHA1, SHA2 etc. Hashing is often used in computer forensics to verify integrity of the digital evidence.


8- What are some of Encryption Algorithms?



9- What is nested VPN ?


10- What is Zero-day exploit?


11- Difference between a vulnerablility and exploitation?



12- Name well-known frameworks

  - Metasploit
  - Beef : Browser exploitation framework
  - 
  
  
13- Name 10 Top secuirty tools in Kali? (USED)




14- If the program connection is slowd due to LAN issues. What would you do?


15-What is Computer registtry ?


16- what is server  hardware vs worksation hardware?


17- What is AWES and Azure ?


18-What is the use of policies ?


19- What is Active Directory ?


#### 20- What is the difference between proxy, firewall, IDS and IPS?

A proxy server is a server (a computer system or an application) that acts as an intermediary for requests from clients seeking resources from other servers. A client connects to the proxy server, requesting some service, such as a file, connection, web page, or other resource available from a different server and the proxy server evaluates the request as a way to simplify and control its complexity. 

Firewall is basically meant for network traffic control/filtering mainly at layer-3. It allows/denies packets and connections based on certain pre-defined rules.

IDS- Intrusion Detection System is an application which tries to detect intrusion attempts based on attack signature database it has.

IPS- Intrusion Prevention System detects the intrusion (like IDS) and goes one step ahead to prevent it as well. It simply drops the packet it thinks suspicious (based on rules)

Examples:

- proxy – Squid

- Firewall- IPTables, CISCO Pix, ZoneAlarm, SonicWasll

- IDS- SNORT

- IPS- IBM Proventia

#### 21- Difference between symmetric and asymmetric encyprtion.

The key difference between asymmetric and symmetric encryption is that symmetric encryption uses one secret key that has to be shared among the sender and recipient of the message.

While asymmetric encryption utilizes a private key and a public key to decrypt and encrypt messages during communication
