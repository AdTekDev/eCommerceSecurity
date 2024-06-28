
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

### Q-List 05
- What are false acceptance rates (FARs) and false rejection rates (FRRs)?
- For watch lists of criminals, which is worse from a security viewpoint, a false acceptance or a false rejection? Explain.
- Reusable passwords offer poor security. What do you think is holding back their replacement with other approaches?
- Create two good password reset questions. For each, explain why you think it is a good question.
- What do FRRs mean when fingerprint scanning is used to secure a PC against walk-up attacks? What might produce high FRRs? Can you think of a way that this problem could be reduced in fingerprint scanning?


### Q-List 06  
- Given the weakness of commercial WAN security, why do you think companies continue to use WAN technology without added cryptographic protections?
- What could a company do if it was using a commercial WAN and a vulnerability appeared that allowed attackers to easily find routing information and therefore be able to eavesdrop on corporate transmissions?
- Longer keys are more difficult to crack. Most symmetric keys today are 100 to 300 bits long. Why don’t systems use far longer symmetric keys—say, 1,000 bit keys?



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


### SQ.04.1   
Some airports are installing face recognition systems to identify terrorists and criminals. About one in a million people passing through the airport is a terrorist. Suppose the FAR is about 1 percent. The FRR is about 30 percent. Is this system likely to be workable? Explain using a spreadsheet analysis with reasonable assumptions. Give a short paragraph giving your conclusion.  

### SQ.04.2  
Centralizing authentication and authorization reduces cost, improves consistency, and permits rapid provisioning and changes. List the technologies on the way toward greater centralization, beginning with stand-alone authenticators through corporate metadirectory servers.  

### SQ.05.1  
The total processing speed of microprocessors (based on clock rate and number of circuits) is doubling roughly every year. Today, a symmetric session key needs to be 100 bits long to be considered strong. How long will a symmetric session key have to be in 30 years to be considered strong? (Hint: consider how much longer decryption takes if the key length is increased by a single bit.)  


### SQ.05.2  
The textbook described how public key authentication is used for message-by-message authentication in digital signatures. However, public key authentication is widely used for initial authentication. Describe the processes that the supplicant and verifier would use if public key encryption were used in initial challenge–response authentication. Draw heavily on your understanding of digital signatures, but put this information in challenge–response context.  

