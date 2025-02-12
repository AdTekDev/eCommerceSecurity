
# W07. Secure Network 

## Monitor 

### Microsoft Network Monitor
  ![image](https://github.com/user-attachments/assets/deb336bf-c038-4b14-90f9-e040c8a15626)

### netstat
```
netstat -an

netstat -an | findstr :<port_number>

```


## Scan 

### commands 
```
netstat -an | findstr LISTENING

Get-NetTCPConnection | Where-Object {$_.State -eq 'Listen'}

```

### online check
- https://dnschecker.org/port-scanner.php
- https://hackertarget.com/nmap-online-port-scanner/

## Protocols
- http/https
- SSL/TLS  -（Secure Sockets Layer）/（Transport Layer Security）
- vpn

## CA / SSL certificate

- chrome://certificate-manager/clientcerts 
![image](https://github.com/user-attachments/assets/45f3ddc0-2d3a-41a7-aaeb-9672cc13495c)

