# Network scripts

Some python scripting network hacks and network system administration for learning python the non-boring way in a familiar domain (or vv).
With many thanks to [EONRaider](https://github.com/EONRaider), [BlackHat](https://www.blackhat.com/), and [ZSecurity](https://zsecurity.org/).

## Requirements

* [A small pentesting lab](https://github.com/tymyrddin/ymrir/wiki/pentesting-lab.md) with Kali and a Windows 10 (virtual) machines. Host was an Ubuntu 20.04. 
* Most scripts only support Python 3, only a few, for learning purposes, support Python 2.7 (and also Python 3). And [Python 2.7 causes lots of bugs due to end of life](https://github.com/tymyrddin/ymrir/wiki/python-2.7-end-of-life.md).
* The scripts have defaults set for our lab. If you wish to run these, change the defaults to your context or provide argumants.

## Scripts

Into the deepest depths of an enterprise target, there are usually no tools to execute network attacks, and no means to install anything.
And in many cases, a Python install can be found ...

- [x] [MAC changer](mac_changer)
- [x] [Network scanner](network_scanner) 
- [x] [ARP spoofer](arp_spoofer) 
- [x] [Packet sniffer](packet_sniffer) 
- [x] [DNS spoofer](dns_spoofer) 
- [x] [File interceptor](file_interceptor) 
- [x] [Code injector](code_injector)
- [ ] ARP spoof detector 
- [x] [Sockets](sockets) 
- [x] [Netcat replace](netcat_replace) 
- [ ] TCP proxy - in progress
- [ ] SSH tunneling
- [ ] Decoding the IP Layer

