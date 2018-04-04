# Raspberry Pi as Man in the Middle Device

Objective: Ability to intercept HTTP/HTTPS traffic and create a HTTP proxy server on the Raspberry Pi

Members:
1. Marcus Chong
2. Alex Thompson
3. Yousong Zhang

Deliverables:
- Shared GitHub repo (due 3/28)
- README of project description, references, goals (due 3/28)
- Intercept packets with arpspoof
- Test running HTTP/HTTPS Proxy Server on the raspberry pi
- Intercept and manipulate HTTP/HTTPS packets

Hardware:
  - Raspberry Pi
  - Panda Wireless Adapter

Software:
  - Kali Linux
  - Python
  - mitmproxy
  - hostapd
  - arpspoof
  - urlsnarf

Completed:
- [Simple man in the middle attack using arpspoof](./simple-mitm.md)

Current challenges:
- Setting up dhcp server
- Setting up access point

End goal:
- Ability to manipulate packets between victim and router

References:
- MitM:
  - https://docs.mitmproxy.org/stable/
  - https://hackaday.io/project/10338-raspberry-pi-mitm#menu-description
  - https://www.adamengle.com/2016/12/08/raspberry-pi-3-mitmproxy/
  - http://www.kalitut.com/2017/11/RaspberryPi-man-in-the-middle.html
  - http://jeffq.com/blog/setting-up-a-man-in-the-middle-device-with-raspberry-pi-part-1/
  - https://ourcodeworld.com/articles/read/422/how-to-perform-a-man-in-the-middle-mitm-attack-with-kali-linux
- Proxy server
  - https://ccm.net/faq/804-installing-an-http-proxy-server-squid#2-5-authorizing-access-to-group
  - https://github.com/abhinavsingh/proxy.py