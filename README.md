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
### Click on the Windows Start menu, then type `Control Panel`, press Enter
<p>
<img src="https://github.com/user-attachments/assets/2a62857d-8997-42d4-90a6-d22163a4666f" width="350" alt="Disk Sanitization Steps"/>
</p>

### Inside of the Control Panel, view the icons as `Large icons` then click on `Network and Sharing Center`
<p>
<img src="https://github.com/user-attachments/assets/3d5f736d-0a80-4d4e-8035-c4b938a22e9d" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to `Change adapter setings`
<p>
<img src="https://github.com/user-attachments/assets/c455b7bf-bfa9-4b71-9328-13cf5bcedabe" width="550" alt="Disk Sanitization Steps"/>
</p>

### Double-click on the network device
<p>
<img src="https://github.com/user-attachments/assets/1cabbbff-7fcb-4965-bd36-791b39084a01" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click on `Properties`
<p>
<img src="https://github.com/user-attachments/assets/06469c76-0be5-48d3-9a7a-db40f1f223be" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>

### Double-click the `Interent Protocol version 4 (TCP/IPv4)` option to set an IP address for the network
<p>
<img src="https://github.com/user-attachments/assets/79ea004c-54aa-4d20-8e8f-b120418e1c78" width="550" alt="Disk Sanitization Steps"/>
</p>

### Input the following settings then click Ok
<p>
<img src="https://github.com/user-attachments/assets/8ec3eaa7-10fc-45bb-a54f-ba147b296c3c" width="550" alt="Disk Sanitization Steps"/>
</p>

### Check that the settings have been saved via command line
<p>
<img src="https://github.com/user-attachments/assets/efb295a7-1cdf-4b7c-ab04-61ccbd4d67d9" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project
