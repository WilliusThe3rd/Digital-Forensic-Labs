https://cyberdefenders.org/blueteam-ctf-challenges/webstrike/

This was a nice lab that tested my ability with wireshark by:

Finding the attackers user agent by examining the http requests made by the attacker
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(1).png">

Finding the webshell used by the attacker and verifying it was successful by investigating HTTP POST packets and following the HTTP stream, looking for a 200 from the server after the upload attempt
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(2).png">

To track down the directory used by the attacker to store the uploaded files by filtering by the file name
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(3).png">
flowing the stream
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(4).png">

lastly discovering the port used in the attack and the file the attacker attempted to exfiltrate
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(5).png">
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(6).png">
<img src="https://github.com/WilliusThe3rd/Digital-Forensic-Labs/blob/main/Network%20Forensic%20Labs/WebStrike/image%20(7).png">
