# Multi-LAN
Multi LAN Discription

A multi-LAN setup was implemented using a single router to interconnect two networks: 192.168.0.0/24 and 192.168.1.0/24. The router was configured with separate interfaces/sub-interfaces for each LAN, enabling routing between both network segments and ensuring proper connectivity for all devices in the two areas.


# CLI - COMMANDS

Router # enable

Router # config terminal

Router (config) # int gig 0/0/0

Router (config - if) # ip address 192.168.0.1 255.255.255.0

Router (config) # no shutdown

Router (config) # int gig 0/0/1

Router (config - if) # ip address 192.168.1.1 255.255.255.0

Router (config) # no shutdown
