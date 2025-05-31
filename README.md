<p align="center">
<img src="https://github.com/user-attachments/assets/2d5d287e-078f-4e4e-90d4-317f3ff5c740" width="650" alt="Microsoft Active Directory Logo"/>
</p>



<h1>Static IP Address</h1>
This project outlines changing the Domain's IP address from DHCP to Staic.<br />


<br>


<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)


<br>


<h2>Operating Systems Used </h2>

- Windows Server 2022


<br>


<h2>High-Level Deployment and Configuration Steps</h2>

- Open the Control Panel
- Change the `View by` setting to `Large icons`
- Navigate to `Network and Sharing Center`
- Click on `Change adapter settings`
- Choose the network that needs the static IP addres:
      - Ethernet0
- Clic on `Properties`
- Select Internet Protocol Version 4 (TCP/IPv4)
- Input the IP as the following:
      - IP Address: 10.0.10.2
      - Subnet Mask: 255.0.0.0
      - Default Gateway: 10.0.10.1
- Input the following DNS servers:
      - Preferred DNS server: 8.8.8.8
      - Alternative DNS server: 127.0.0.1


<br>


<h2>Deployment and Configuration Steps</h2>

## Rename the PC to Server2022
### Rigth-click on the Windows Start Menu, then click System
<p>
<img src="https://github.com/user-attachments/assets/5da7e367-296d-455e-a5ec-3fa5a9b75862" width="350" alt="Disk Sanitization Steps"/>
</p>

### Scroll down then click on Rename this PC (advanced)
<p>
<img src="https://github.com/user-attachments/assets/0d942ec3-7665-4d27-99d4-47fa9dc3b4eb" width="550" alt="Disk Sanitization Steps"/>
</p>

### In the Computer Name tab, click on Change to change the name of the PC
<p>
<img src="https://github.com/user-attachments/assets/3c59a574-5d4a-4a1c-9ea4-069861b38792" width="550" alt="Disk Sanitization Steps"/>
</p>

### Change the computer name to `Server2022`
<p>
<img src="https://github.com/user-attachments/assets/7a1cc4a2-3c36-42ad-9239-68c2fc315ac6" width="550" alt="Disk Sanitization Steps"/>
</p>


### Apply the settings then restart the machine, the restart will be automatic
<p>
<img src="https://github.com/user-attachments/assets/ca742237-953d-4741-b3b8-3361b0fc6a2e" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/f99a8f4b-7720-4f2c-b33d-5a566837a2b4" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/21d216f0-4ade-4000-af45-d43a30a7ab56" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/07315b1f-73c6-4b02-8c34-e77eab055d34" width="550" alt="Disk Sanitization Steps"/>
</p>

### Verify the changes by right clicking on the Windows Start Menu, then click on System
<p>
<img src="https://github.com/user-attachments/assets/9faf7510-3e66-4353-aa2d-79ef2c0d58e0" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project
