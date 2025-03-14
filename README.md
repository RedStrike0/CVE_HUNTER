# CVE_HUNTER

CVE Hunter is a tool designed to detect security vulnerabilities by either inputting the software version or scanning the operating system and version via an IP address, providing a list of potential vulnerabilities.

# Key Features
Detect vulnerabilities based on the input software version.
Scan the operating system and version via an IP address.
Provide detailed reports on detected vulnerabilities.

# Installation
`git clone https://github.com/RedStrike0/CVE_HUNTER.git`                                                                                                                                                                                                    


`cd CVE_HUNTER`  



`pip install -r requirements.txt`

[If you encounter an error use:]

`python -m pip install -r requiments.txt --break-system-packages`

                                                                                          



# Usage
`python redstrike.py`


```
┌──(root㉿kali)-[/home/kali/Desktop/CVE_HUNTER-main]
└─# python redstrike.py

              __ _     _ ___   _  _ _   ___  _  _____ ___ __
             / __\ \ / /| __| | || | | | | \| ||_   _| __| _ \  
            | (__ \ V / | _|  | __ | |_| | .` |  | | | _||   /  
             \___| \_/  |___| |_||_|\___/|_|\_|  |_| |___|_|_\        
                                           
                     [+] Developed by RedStrike0                      

1. Search Vulnrabiltice                  (example scan device if you enter os and version)
2. Search Vulnrabilitice For IP          (example scan device if you enter IP)                           
                                                                                                         
Enter your Choice: 1                                                                 
===============================================================                      
Enter name of the OS (example: Microsoft Windows, Linux): windows                    
Enter Version (example: 10 , 2.4.3): 10                                              
                                                           
===============================================================                      
Searching CPEs...                                                                    
===============================================================     
```


Select the specific CPE version and it will show you the vulnerabilities in it.


`python redstrike.py`


select 2 and input IP 


![Image](https://github.com/user-attachments/assets/9a52f862-1a74-48c6-8798-cb4927bfdc83)

![Image](https://github.com/user-attachments/assets/6f2ec9a1-f877-45db-8565-ae36fec6676c)




It will show you the ports, their versions, the system and its version, then choose the CPE you want and it will show you the vulnerabilities in it.'''


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
