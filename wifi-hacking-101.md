Today I worked through the TryHackMe “WiFi Hacking 101” room and learned the basics of how WPA/WPA2-Personal WiFi security works in a controlled lab environment.

The biggest thing I learned is that WPA/WPA2 attacks are not about “magically breaking WiFi,” but about understanding how the 4-way handshake works. The handshake allows the client and access point to prove they both know the WiFi password without directly sending the password across the network.

I also learned the meaning of important WiFi security terms like:

SSID: the WiFi network name
BSSID: the MAC address of the access point
PSK: the pre-shared key, or WiFi password
WPA2-PSK: the common home WiFi password-based security method
WPA2-EAP: a more enterprise-style authentication method using usernames, passwords, and RADIUS servers

Another key takeaway was learning how tools from the Aircrack-ng suite are used in WiFi security testing. I learned that tools like airmon-ng, airodump-ng, and aircrack-ng are used to place a wireless adapter into monitor mode, capture packets, and test password strength using a wordlist.

One important lesson from this room is that weak WiFi passwords are a real security risk. If a WPA/WPA2 handshake is captured, attackers can try to crack the password offline using dictionary or brute-force attacks. This showed me why strong, unique, and long WiFi passwords are important.

This was a helpful hands-on introduction to wireless security. It helped me understand both the attacker’s mindset and the defender’s responsibility: only test networks I own or have permission to test, and use this knowledge to improve security, not harm others.

Key takeaway:
WiFi security is not just about having a password. It is about having a strong password, understanding how authentication works, and knowing how attackers may try to exploit weak configurations.