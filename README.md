# IOT Security & Performance comparison of cryptographic algorithms

Problem Statement
When various stand-alone IOT devices are connecting to the Internet, it brings a lot of challenges, such as scalability, naming, resource constraints, inter-operability, security and privacy etc. Connectivity between internet and everyday objects and the capability to exchange data between them arises a lot of potential privacy and security risks. As a result, potential security and privacy risks exist in a broad scope, ranging from the physical world to the Internet, and if they are exploited it can cause a lot of damages.

Justification 
As a result of the risk’s mentioned above, it is critically important to test the existing cryptographic encryption/decryption techniques on IOT devices to determine if they are efficient enough in terms of execution time/power consumption and to determine if there’s a need for a new lightweight cryptography for IOT devices. 

Objective  
To study about the importance of cryptographic ciphers.
To test the efficiency of the cryptographic ciphers on IOT devices and to do a comparative analysis on the cryptographic ciphers and IOT devices according to features like power consumption, CPU, RAM, processor etc. for execution speed for different data sizes.

lock_files.py - AES file encryption 
usage for encryption : lock_files.py -p password --lock file1.txt
Reference - https://github.com/jlinoff/lock_files

3DES.py - simple 3DES script that takes hardcoded file "to_enc.txt" and calculate the execution time 
