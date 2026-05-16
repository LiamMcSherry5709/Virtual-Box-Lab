# Screenshots 

Below I will provide screenshots that show the step by step propcess of undertaking this project. 
before perfroming any action with Virtual box I first had to dowload a Windows 10 and Kali linux ISO.

## Virtual Machine Configuration

Below is the screenshot displaying both the Windows 10 and Kali Linux virtual Machines on VirtualBox.

<img width="1917" height="1140" alt="VMconfig1" src="https://github.com/user-attachments/assets/6404b684-94ab-4bad-9157-0b3c9f0c35d5" />

Next I assighned two different network adapters to each machine. One was an interanl network the other was a NAT. 
This was so I had both isolation from the physical network and internet access. The screen shots below show this process

&nbsp;
(internal ntework) 
<img width="1070" height="655" alt="netconfig1" src="https://github.com/user-attachments/assets/7e5918ef-1c7d-4326-966c-45ad669a81ba" />

&nbsp;
(NAT)
<img width="1072" height="657" alt="netconfig2" src="https://github.com/user-attachments/assets/c8485e55-6d8f-4141-b3aa-b2a193e82435" />

### IP configuration

After assigning the adapters i then opened up the virtual machines to assign the IP addresses for the machines on the internal network.
&nbsp;

I first assighned the IP address for the windows machine. I opened up the properties of the internal networks ethernet.
<img width="562" height="262" alt="intNetworkconfigwin1" src="https://github.com/user-attachments/assets/0b120fb9-cd56-4d2b-a27a-0e09d2217973" />

&nbsp;
Then I selecetd IPv4 and assigned it the address 192.168.20.10
<img width="757" height="456" alt="intNetconfigwin2" src="https://github.com/user-attachments/assets/298fad50-ce9c-4618-bfc1-7ae30ff70870" />

&nbsp;
Next I used the command ipconfig in the command prompt to test whether the address had be assigned.
<img width="625" height="456" alt="intNetconfigwin3" src="https://github.com/user-attachments/assets/cbaad292-d0c1-437d-9e18-479aac296eab" />

&nbsp;
Next I did the same for the Kali Linux virtual machine. I selected Wired Connection 1 for the internal network.
<img width="600" height="162" alt="Kalinetconfig1" src="https://github.com/user-attachments/assets/914eceab-5a19-4f5c-aebe-fec580f72b92" />

