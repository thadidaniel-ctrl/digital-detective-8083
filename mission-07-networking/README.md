### Task 7.1 — Network concepts

| Concept | My explanation | Example |
|---|---|---|
| LAN | devices connected in a small areas |school or hostel's fucking wifi |
| MAN |A network covering a city or a large campus|A network linking a city’s government offices|
| WAN |A network spanning countries or continents	|the internet|
| DNS |Computers use number addresses, but people remember names, so something must translate|typing  website name insted  of the the numbers |
| Router |A device that passes data between networks|our  Wi-Fi router, connecting home to the internet which is a |
| Protocol |Agreed rules so different devices understand each others languages (http, https)|HTTP for web pages|
| Packet switching |Data is split into small pieces that travel separately and are put back together|sending a phto online is an good expample|
| Client-server |One side asks, the other side answers|Your browser (client) and a web server|


### task 7.2 - Observe network information
ping -c 4 example.com
ping sends small test messages to another computer and waits for replies.
-c 4 means send 4 and then stop. Without it, ping runs forever (stop it with Ctrl+C).
example.com is the public website being tested.



`the ouput`:

daniel@daniels-MacBook-Pro digital-detective-8083 % ping -c 4 example.com
PING example.com (172.66.147.243): 56 data bytes
64 bytes from 172.66.147.243: icmp_seq=0 ttl=54 time=18.880 ms
64 bytes from 172.66.147.243: icmp_seq=1 ttl=54 time=33.094 ms
64 bytes from 172.66.147.243: icmp_seq=2 ttl=54 time=18.219 ms
64 bytes from 172.66.147.243: icmp_seq=3 ttl=54 time=20.794 ms

--- example.com ping statistics ---
4 packets transmission


`how to see theworking of the dns `
 nslookup example.com
nslookup asks a DNS server for the address behind a name.
You’ll see the name example.com and one or more IP addresses. example.com is a public site, so its addresses are fine to write down.

Non-authoritative answer:
Name:   example.com
Address: 172.66.147.243
Name:   example.com
Address: 104.20.23.154


### task 7.3 -short note on the dns and protocol

`dns`
DNS is the "phonebook of the Internet." It translates human-friendly domain names (like google.com) into IP addresses (like 142.250.183.46) that computers use to find each other.

Why it exists: Humans remember names, not numbers. DNS does the translation automatically.
How it works: Your device asks a DNS server → the server looks up the name → returns the IP address → your browser connects.
Example: Typing example.com → DNS resolves it to 93.184.216.34 → browser loads the site.

reallife examle:
when you dial your mom's number you can see her name this also similar only 


`protocol`
A protocol is a set of rules that defines how data is sent, received, and interpreted between devices on a network. Both sides must follow the same rules to communicate.
Why it exists: Without agreed rules, devices would send data in incompatible ways — like two people speaking different 


Examples:

HTTP/HTTPS — transferring web pages

TCP/IP — core rules for sending data across the Internet

DNS — resolving domain names to IP addresses

FTP — transferring files

SMTP — sending email



















