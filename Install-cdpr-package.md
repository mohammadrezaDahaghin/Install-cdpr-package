# Install cdpr package

Information about the package, cdpr, which is shipped with common Linux distributions. The cdpr package is designed for, Cisco Discovery Protocol Analyzer.(cdpr is used to decode a Cisco Disovery Protocol (CDP) packet, by default it will report the device ID, the IP Address (of the device), and the port number that the machine is connected to. Optionally it will decode the entire CDP packet.)

## install cdpr:

```bash
sudo apt-get update
sudo apt-get install -y cdpr

mrdex@srv1:~$ cdpr
cdpr - Cisco Discovery Protocol Reporter
Version 2.4
Copyright (c) 2002-2010 - MonkeyMental.com

1. ens33 (No description available)
2. ens37 (No description available)
3. ens38 (No description available)
4. lo (No description available)
5. bluetooth0 (Bluetooth adapter number 0)
6. bluetooth-monitor (Bluetooth Linux Monitor)
7. nflog (Linux netfilter log (NFLOG) interface)
8. nfqueue (Linux netfilter queue (NFQUEUE) interface)
9. dbus-system (D-Bus system bus)
10. dbus-session (D-Bus session bus)
Enter the interface number (1-10):
```