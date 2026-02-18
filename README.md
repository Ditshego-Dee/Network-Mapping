# Network Mapping and Ping Test Report

## 1. Introduction

This project documents my work network connection, IP configuration, and ping test results as part of the course *The Bits and Bytes of Computer Networking*. The goal of this task is to understand how my device connects to the network, the router, and the internet, and to test connectivity using the ping command.

## 2. Network Description

I am connected to my workplace Wi-Fi network. The network consists of:
- A work router (default gateway)
- My Windows PC
- The internet

My PC connects to the router, and the router provides access to the internet.

## 3. Network Diagram

        [ Internet ]
             |
       [ Work Router ]
             |
        [ My PC ]
      IP: 172.20.7.253

## 4. IP Configuration

I used the `ipconfig` command in Command Prompt to check my network settings.

- IPv4 Address: 172.20.7.253  
- Subnet Mask: 255.255.254.0  
- Default Gateway: 172.20.6.1  

The default gateway is the router that connects my PC to the rest of the network and the internet.

## 5. Ping Test Results

### 5.1 Ping to Router (Default Gateway)

Command used:

Result:  
Packets sent = 4, received = 4, lost = 0 (0% loss)  
Average time = 4ms  

This shows that my PC can successfully communicate with the router.

### 5.2 Ping to Internet (Google DNS)

Command used:

Result:  
Packets sent = 4, received = 4, lost = 0 (0% loss)  
Average time = 12ms  

This shows that my PC can successfully reach the internet.

### 5.3 Ping to Website (DNS Test)

Command used:

Result:  
Packets sent = 4, received = 4, lost = 0 (0% loss)  
Average time = 8ms  

This shows that DNS is working because the domain name google.com was successfully resolved to an IP address and reached.

## 6. Conclusion

This task helped me understand how my computer connects to the router and the internet. Using the `ipconfig` and `ping` commands, I was able to test my local network, internet connection, and DNS. All tests were successful, which means my network connection is working correctly.
