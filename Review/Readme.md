
# Review 

## **Q-List**

### Q-List 01

- Distinguish between OSI and ISO.
- How many layers does the OSI architecture have?
- Which of these layers are similar to the layers in TCP/IP?
- A server sends a packet with the source socket 60.32.1.79:25. What kind of server is it? Explain.


### Q-List 02

- Is an IDS a preventative, detective, or restorative control?
- What are the two types of analysis that IDSs usually do?
- What are the main alternatives for backup sites?

### Q-List 03
- Distinguish between file/directory data backup and image backup.
- What is the advantage of shadowing over file/directory data backup?
- How long must an encryption key be to be considered strong today?
- How can DLP systems be effective when placed at the gateway, on clients, and on a database server?
- How much data would you lose if your computer’s hard drive crashed right now? Could you reduce the amount of data that would be lost? How?

### Q-List 04
- What three types of hosts are placed in the DMZ?
- Why do companies put application proxy firewalls in the DMZ?
- Why do all hosts in the DMZ have to be hardened stringently?
- Create an egress ACL for an SPI firewall if policy only forbids connections to external FTP servers.
- Contrast what sniffers can learn if a company being attacked uses NAT or an application proxy server.


## **"short" Q**

### SQ.01.1
You are advising a small company.   
a) Would you recommend using a firewall? Explain.  
b) Would you recommend using antivirus filtering? Explain.  
c) Would you recommend an intrusion detection system? Explain.  

### SQ.01.2  
When IDSs generate alerts, it can send them to a console in the security center, to a mobile phone, or via e-mail. Discuss the pros and cons of each.  

### SQ.02.1
Directory DunLaoghaire has several subdirectories. Each of these subdirectories has very sensitive information that should only be accessible to a single user. What permissions would you give in the top-level DunLaoghaire directory to the group all logged-in users if you do not want to change the Allow inheritable permissions from parent to propagate to this object box default in subdirectories? (b) What would you then do in each subdirectory?

### SQ.02.2 
Critique the safety of each of the following passwords, giving your specific reasoning. (a) swordfish, (b) Lt6^, (c) Processing1, and (d) nitt4aGm^.

### SQ.03.1  
Most IP addresses are public, in the sense that they can appear on the public Internet. However, a few IP addresses have been designated as private IP addresses. One private IP address range is 172.16.0.0 to 172.31.255.255. Private IP addresses can only appear within a firm. In Figure 6-20 (textbook), internal hosts have private IP addresses except for those in the DMZ, which use public IP addresses. Explain this discrepancy if you can.  

### SQ.03.2  
A firm has the following firewall policy: Employee access to Internet servers should be unrestricted and external clients should only be able to access the firm’s public webserver, http://www.adtekdev.com. The firm also has a finance server that should only be accessible to people in the finance department. The server and the finance departments are all on the internal subnet 10.5.4.3. The firm has a single large site. How would you implement this policy? Create both a firewall architecture and ACLs for the border firewall for both internal and external connection-opening attempts.
