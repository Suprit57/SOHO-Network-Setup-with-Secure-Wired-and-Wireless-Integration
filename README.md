
## **💻 Project: Enterprise & SOHO Network Design and Implementation**


**🎯 1. Objective**
The goal of the project was to design and configure a **functional, secure, and scalable network** suitable for both **🏢 Enterprise** and **🏠 Small Office/Home Office (SOHO)** environments. The network needed to support **📡 wired and wireless devices**, ensure **smooth communication between departments**, and provide **centralized management** with strong security 🔒.


**🗺️ 2. Network Design**

* **🖥️ Topology**: Built in **Cisco Packet Tracer**, the network included **routers, switches, access points, and end devices** (PCs 💻, laptops 💼, printers 🖨️).
* **🔀 Segmentation**: Divided the network into **VLANs** to separate different departments (e.g., Admin, IT, Guests, Wireless Clients).
* **🌐 Routing**: Implemented **Inter-VLAN Routing** using the **Router-on-a-Stick** method — one physical router interface with multiple subinterfaces, each tagged with a VLAN ID.



**⚙️ 3. Key Configurations**

### **📂 VLAN & Inter-VLAN Routing**

* Created VLANs for logical separation of traffic 🚦.
* Assigned VLAN IDs and IP subnets to each department.
* Configured router subinterfaces with `encapsulation dot1Q` for each VLAN.
* Verified communication between VLANs using **ping** 🖧.

### **📦 DHCP**

* Configured **DHCP pools** for each VLAN 📜.
* Defined network addresses, subnet masks, default gateways, and DNS servers 🌐.
* Excluded gateway and reserved IP addresses from DHCP assignment 🚫.
* Allowed all wired and wireless clients to receive IP addresses automatically 🤝.

### **📡 Wireless Network (WLAN)**

* Added and configured **Access Points** for wireless connectivity 📶.
* Mapped Access Points to VLANs so wireless clients were part of the correct network segment.
* Created custom **SSIDs** 🏷️ for different user groups.
* Secured WLAN using **WPA2 encryption** 🔐.

### **🛡️ Security**

* **SSH**: Enabled secure remote management of routers and switches 🔑.
* **Port Security**: Restricted switch ports to specific MAC addresses 🛑 to block unauthorized devices.
* **Password Encryption**: Encrypted all stored passwords for device security 🗝️.



**🧪 4. Testing & Verification**

* Verified **DHCP** by checking if devices in all VLANs received the correct IP addresses 📥.
* Tested **Inter-VLAN communication** between devices in different VLANs 🔄.
* Connected **wireless devices** to the network and ensured they received the correct IP range 📡.
* Tested **remote login** via SSH to confirm secure management access 📲.
* Verified that **port security** blocked unapproved devices 🚷.



**🏆 5. Outcome**

* Achieved a **fully functional network** ✅ with separate VLANs for different departments.
* Automatic IP allocation through **DHCP** for both wired and wireless clients ⚡.
* **Secure wireless connectivity** 🔒 with VLAN-based SSIDs 📶.
* **Remote management** capability via SSH and enhanced device security using port security 🛡️.
* The network design can be deployed in **hotels 🏨, offices 🏢, or small business setups 🏠** with minimal changes.


This project delivered a secure and well-structured network supporting both wired and wireless environments. It included **VLAN segmentation** with **Inter-VLAN routing** and **DHCP** for automated IP management, ensuring organized traffic flow and easy device configuration. **Access Points** were configured with VLAN-based SSIDs and **WPA2 security** to provide safe and reliable wireless access. Additionally, **SSH** and **Port Security** were implemented to enable secure remote management and prevent unauthorized device connections.

