# raspi-hotspot_honeypot
A HotSpot Honeypot for RaspberryPi


# What is a HotSpot-Honeypot ?
Basicly i describe it as a type of open wifi network hosted by a raspberry pi, it gives a DNS server and a DHCP server.
The DHCP delivers a IP to the connecting client and the DNS server wil resolve EVERY requested domain to the Pi's webserver.
It then serves a webpage to a client (you need to insert that one yourself) and thats basicly all.
The client can see this page wich will have a scipt in background that captures evere given date from a form on the main page.

# Isn't that illegal ?
If you capture the private informations and passwords YES, i just wäit until the user submits the data and give hin back a Webpage with the message "You just tapped into a Trap HotSpot, concider checking the realness of a HotSpot next time..."
