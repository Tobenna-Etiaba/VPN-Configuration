<p align="center">
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

# VPN-Configuration

Here I will quickly go over how to set up a VPN(specifically Proton VPN) within a virtual machine and how to use it.

<h2>Tools Used</h2>

- Microsoft Azure
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 Pro (21H2)

<h2>Setting Up The VPN</h2>

- I started out by creating a Windows 10 virtual machine in Azure with 2vcpus & 8GB of memory to ensure that the VM ran at a reasonable speed.

<img width="1181" alt="Screenshot 2025-02-05 at 01 45 15" src="https://github.com/user-attachments/assets/a5f60d90-69cf-49d6-bd22-2504f127a0b5" />

<img width="1024" alt="Screenshot 2025-02-05 at 01 46 34" src="https://github.com/user-attachments/assets/e841f60d-e406-408b-a0df-7da463adb777" />

- From there I used remote desktop to access the virtual machine created in Azure.

<img width="1149" alt="Screenshot 2025-02-05 at 01 48 52" src="https://github.com/user-attachments/assets/1912b519-a130-4b10-87ae-6bdbcc7710c5" />

- Once I logged into the Windows VM I went to the website "*What's My IP Address*" to see my VMs IP address and IP information.

<img width="1305" alt="Screenshot 2025-02-05 at 01 53 06" src="https://github.com/user-attachments/assets/40cd3fad-82a6-4df7-b5d3-5a2ac203e6f3" />

- Seeing that I'm located in London I decided to go to McDonald's website, and from the image below, the content on the website is based on the UK's McDonalds.

<img width="1701" alt="Screenshot 2025-02-05 at 01 54 58" src="https://github.com/user-attachments/assets/ebddefe6-884a-4f0e-9685-cf34e7714c42" />

- From there I went to download and install Proton VPN.
  
<img width="1697" alt="Screenshot 2025-02-05 at 01 55 11" src="https://github.com/user-attachments/assets/85cf089b-1884-4fbb-b050-19a137ec4bba" />

<img width="599" alt="Screenshot 2025-02-05 at 01 57 14" src="https://github.com/user-attachments/assets/51513dbd-eac7-49d6-8de8-36e5ea582e62" />

<img width="600" alt="Screenshot 2025-02-05 at 02 00 02" src="https://github.com/user-attachments/assets/90b37e17-a1ad-40cc-9460-82bdf372f833" />

- After the installation was done I logged into the VPN and connected to it, and my location was changed to The Netherlands.

<img width="1298" alt="Screenshot 2025-02-05 at 02 00 50" src="https://github.com/user-attachments/assets/2bf8aff2-ddc6-48d2-80dd-a81d00d494c5" />

<img width="1295" alt="Screenshot 2025-02-05 at 02 01 19" src="https://github.com/user-attachments/assets/78c02dfd-6128-44a3-a4d7-a4e745dca4b5" />

- After connecting, I went back to *What's My IP Address* to see my new IP information and according to it my internet service provider was no longer from the U.K. but now in India.

<img width="1295" alt="Screenshot 2025-02-05 at 02 03 12" src="https://github.com/user-attachments/assets/a57a9fdc-cb41-4f94-8882-987337283f4d" />

- I then went back to the Mcdonald's website and refreshed it and the content on the website was based on the McDonalds in The Netherlands.

<img width="1697" alt="Screenshot 2025-02-05 at 02 06 00" src="https://github.com/user-attachments/assets/86d37cd3-9ddf-42c0-8214-1c576e60500f" />

- And that's it.
