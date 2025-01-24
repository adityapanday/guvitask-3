
1 > The port of guvi.in is 
aditya-pandey@aditya-pandey-Inspiron-15-3511:~$ nslookup www.guvi.in
Server:		127.0.0.53
Address:	127.0.0.53#53

Non-authoritative answer:
Name:	www.guvi.in
Address: 104.26.4.88
Name:	www.guvi.in
Address: 172.67.70.207
Name:	www.guvi.in
Address: 104.26.5.88
Name:	www.guvi.in
Address: 2606:4700:90ca:d255:c10c:b01:60b8:c78e


2 > To see the ndoes connectivit 
  aditya-pandey@aditya-pandey-Inspiron-15-3511:~$ ping 172.67.70.207
  PING 172.67.70.207 (172.67.70.207) 56(84) bytes of data.
  64 bytes from 172.67.70.207: icmp_seq=1 ttl=50 time=273 ms
  64 bytes from 172.67.70.207: icmp_seq=2 ttl=50 time=295 ms
  64 bytes from 172.67.70.207: icmp_seq=3 ttl=50 time=225 ms
  64 bytes from 172.67.70.207: icmp_seq=4 ttl=50 time=239 ms
  64 bytes from 172.67.70.207: icmp_seq=5 ttl=50 time=259 ms
  64 bytes from 172.67.70.207: icmp_seq=6 ttl=50 time=287 ms
  64 bytes from 172.67.70.207: icmp_seq=7 ttl=50 time=202 ms
  64 bytes from 172.67.70.207: icmp_seq=8 ttl=50 time=225 ms
  ^C
  --- 172.67.70.207 ping statistics ---
  8 packets transmitted, 8 received, 0% packet loss, time 7009ms
  rtt min/avg/max/mdev = 201.902/250.738/295.250/31.065 ms



  3>deployed an application in guvi.com:9000
    aditya-pandey@aditya-pandey-Inspiron-15-3511:~$ telnet guvi.com 9000
    Trying 2606:4700:3031::6815:4fa6...
    ^C
    Port is open but it is Blocked by firewall hence you are unable to deployee


  
    
