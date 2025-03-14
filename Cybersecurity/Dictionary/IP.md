**IP**, or *Internet Protocol*, is a fundamental concept in cybersecurity that refers to the way data is transferred across networks, specifically the internet. It is a core component of the internet’s architecture and serves as the primary building block for communication between devices connected to the network. 
An IP address is a unique identifier assigned to each device connected to a network, like a computer or smartphone. It comprises a series of numbers separated by dots (e.g., 192.168.1.1). 
IP addresses can be either IPv4 (32-bit) or the newer IPv6 (128-bit) format, which provides more available addresses. They allow devices to send and receive data packets to and from other devices on the internet.

## Public IP classes range
|   |            Range            |  [[Subnet Mask]]  |
|---|-----------------------------|-------------------|
| A | 1.0.0.0 - 126.255.255.255   | 255.0.0.0         |
| B | 128.0.0.0 - 191.255.0.0     | 255.255.0.0       |
| C | 192.0.0.0 - 223.255.255.0   | 255.255.255.0     |
| D | 224.0.0.0 - 239.255.255.255 | Can't use for now |
| E | 240.0.0.0 - 255.255.255.255 | Experimental      |


## Private IP
Private IP
↓
**[[RFC 1918]]**
↓
**[[NAT]]** - Network Address Translation
↓
Public IP

|   |             Range            |  [[Subnet Mask]]  |
|---|------------------------------|-------------------|
| A | 10.0.0.0 - 10.255.255.255    | 255.0.0.0         |
| B | 172.16.0.0 - 172.31.255.255  | 255.255.0.0       |
| C | 192.168.0.0 - 192.168.255.255| 255.255.255.0     |

## Subnetting
[Cheatsheet for subnetting ipv4](https://www.cbtnuggets.com/blog/technology/networking/networking-basics-what-is-ipv4-subnetting)

## localhost
**localhost** is used to test network only on the same computer locally

|            Range            |  [[Subnet Mask]]  |
|-----------------------------|-------------------|
| 127.0.0.0 - 127.255.255.255 | 255.0.0.0         |

## loopback
**loopback** refers to a special network interface used to send traffic back to the same device for testing and diagnostic purposes. The loopback address for IPv4 is `127.0.0.1`, while for IPv6 it is `::1`.


C:\Users\theos>tracert -4 google.com

Tracing route to google.com [142.250.181.206]
over a maximum of 30 hops:

|Hop| Time 1 | Time 2 | Time 3 | IP address |
|---|--------|--------|--------|------------|
| 1 |  4 ms  |  3 ms  |  3 ms  |funbox.home [192.168.1.1]|
| 2 | 10 ms  |  10 ms |  10 ms | 192.0.0.1|
| 3 | 10 ms  |  11 ms |  17 ms | gda-r11.tpnet.pl [195.117.0.229]|
| 4 | 16 ms  |  14 ms |  13 ms | 195.116.35.198|
| 5 | 14 ms  |  13 ms |  16 ms | 72.14.214.158|
| 6 | 17 ms  |  14 ms |  15 ms | 64.233.174.229|
| 7 | 14 ms  |  17 ms |  13 ms | 192.178.99.172|
| 8 | 23 ms  |  22 ms |  24 ms | 192.178.83.135|
| 9 | 28 ms  |  25 ms |  31 ms | 192.178.80.97|
| 10| 27 ms  |  26 ms |  26 ms | 216.239.54.169|
| 11| 26 ms  |  28 ms |  26 ms | 192.178.99.229|
| 12| 29 ms  |  26 ms |  27 ms | 209.85.240.83|
| 13| 29 ms  |  27 ms |  25 ms | ham02s21-in-f14.1e100.net [142.250.181.206]|