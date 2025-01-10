# Simple Port Scanner using sockets in Python
This Port Scanner will work for both the Web Applications as well as remote Host. This tool has been created to provide the basic functionality of a Port Scanner. The general concept of Sockets had been used to provide the functionality. Port Scanner is built on Python 3. Perform a quick compile online at https://www.online-python.com/

To run simple port scanner:   
```
python simple_port_scanner.py
```
To run fast port scanner:
```
python fast_port_scanner --help
```
**Output:**
```
usage: fast_port_scanner.py [-h] [--ports PORT_RANGE] host

Simple port scanner

positional arguments:
host                  Host to scan

optional arguments:
-h, --help            show this help message and exit
--ports PORT_RANGE, -p PORT_RANGE
                        Port range to scan, default is 1-65535 (all ports)
```
For example, if you want to scan the ports from 1 to 1024 of your router (**192.168.1.1**):
```
python3 fast_port_scanner.py 192.168.1.1 --ports 1-1024
```
