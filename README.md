$ python3 arpspoof.py -h
usage: arpspoof.py [-h] [-i INTERFACE] -t TARGETS -g GATEWAY

Do ARP poisoning between a gatway and several targets

optional arguments:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        interface to send from
  -t TARGETS, --targets TARGETS
                        comma-separated list of IP addresses
  -g GATEWAY, --gateway GATEWAY
                        IP address of the gateway
