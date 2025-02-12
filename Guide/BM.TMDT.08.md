
# W08. Access Control 


## Terms
- security identifier (SID)
- Access Control Lists (ACLs)
- Access control entries (ACEs)
- Discretionary access control list (DACL)
- System access control list (SACL)

REFs:  
  ![image](https://github.com/user-attachments/assets/f6079c6a-effb-4dbe-a35a-6f8a05c1fd16)


## commands  

```
CACLS filename [/T] [/M] [/L] [/S[:SDDL]] [/E] [/C] [/G user:perm]
        [/R user [...]] [/P user:perm [...]] [/D user [...]]


cacls  vd01.txt /L
vd01.txt NT AUTHORITY\SYSTEM:F
                        BUILTIN\Administrators:F
                        T79ADTEKDEV\tunn7:F

cacls  vd01.txt /S
vd01.txt "D:(A;;FA;;;SY)(A;;FA;;;BA)(A;;FA;;;S-1-5-21-1506185832-2176520576-3516345639-1001)"


```

## Tools

File -> Properties -> Security   
![image](https://github.com/user-attachments/assets/e4b8e68d-50e7-4386-9be3-44faeba22112)


--> Advanced  
  ![image](https://github.com/user-attachments/assets/745df860-30e3-43f0-9ba3-0a59bf983abc)




