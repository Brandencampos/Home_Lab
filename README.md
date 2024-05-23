# Home_Lab

## Objective
This home lab will be used for different testing purposes for offensive and defensive security. It will be comprised of 2 VMs 1 Windows and 1 Kali Linux machine. These machines will be set to the same internal network in order for communication.


### Skills Learned

- Understanding of properly configuring a VM 
- Proficiency in analyzing and interpreting network logs.
- The home Lab project aimed to establish a controlled environment for analyzing any malware for future projects.
- Development of practical skills with VM configuration
- Use of tools such as nmap, msfvenom, metasploit to scan and create a reverse shell in order to connect to the target machine (windows machine) 

### Tools Used

- nmap was used to scan windows VM 
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/3bd5d539-71cb-43b0-b778-66d71b066d8f)
 - msfvenom was used to create the payload
 - metasploit was used to listen in on the payload

## Steps 
- Target machine info
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/bb86be5a-9cd7-4ca3-8149-202662d3bb0d)

- using msfvenom payload to create an exe file to create a reverse shell 
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/ee4711f9-0724-4fd7-a4b5-1415c532ea6e)


- now using Metasploit in order to listen in on the port we configured with the image.img.exe y using the multi handler
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/52276f0f-fa5d-4d28-b380-282c4b9fee41)

- set the payload 
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/06208311-d5b4-46ed-9194-255cfbc665a7)

- set Lhost to attacking machine Ip
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/72178f11-cde8-4541-91eb-54025d3fb921)

- now serving the image.img.exe file and used the exploit command in metasploit
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/9b46960c-17c0-46c5-9aba-6fdd1d1281d9)

- went to the IP address hosting the file 
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/83b5e356-5949-4710-b462-6352c4779184)

- After downloading the image.img.exe file the connection has been established
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/357ae1fc-9d35-4cfc-a415-539ba3c8a240)

- meterpreter was able to connect
![image](https://github.com/Brandencampos/Home_Lab/assets/62733055/2991c92a-5c1d-4f62-b3d3-43dcc2a3f786)





