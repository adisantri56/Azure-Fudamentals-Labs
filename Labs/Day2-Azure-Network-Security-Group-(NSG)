![Azure](https://img.shields.io/badge/Azure-Networking-blue)
![Level](https://img.shields.io/badge/Level-AZ104-green)

# 🚀 Day 1 — Azure VM with Public IP

---

## 🎯 Objective
Deploy a Linux Virtual Machine in Azure and access it from the internet using SSH.

---

## 🛠 Lab Tasks
- Create Linux VM
- Assign Public IP
- Configure Network Security Group (Allow SSH - Port 22)
- Validate remote access

---

## 🧠 Key Concept

- Public IP is attached to the VM NIC
- Inbound traffic is controlled by NSG rules
- Without NSG allow rule → VM is not reachable

---

## 🏗 Step 1 — Create Linux VM
### Azure Portal → Virtual Machines → Create VM
![](../Image/d1-created-vm1.jpg)
### Select Resource Group
![](../Image/d1-created-vm2.jpg)
![](../Image/d1-created-vm3.jpg)
### Select Disk
![](../Image/d1-created-vm4.jpg)
### For NSG we can create and choose basic or use the existing one
![](../Image/d1-created-vm5.jpg)
### Create and review
![](../Image/d1-created-vm6.jpg)
### Result
![](../Image/d1-created-vm7.jpg)
---

## 🔐 Step 2 — Access VM using Public IP
### Azure Portal → Virtual Machines → Overview
![](../Image/d1-access-vm1.jpg)
### Use Putty or other toll to access VM via SSH
![](../Image/d1-access-vm2.jpg)
### Result
![](../Image/d1-access-vm3.jpg)
> Allow inbound SSH (Port 22) from your public IP.

---

## ✅ Validation

Successfully accessed VM via SSH using public IP.

---

## 🏢 Real-World Mapping

| Azure Component | On-Prem Equivalent |
|----------------|-------------------|
| Public IP      | WAN IP |
| NSG            | Firewall / ACL |
| VNet           | VLAN |

---

## 💡 Lessons Learned

- Public IP alone is not enough
- NSG is mandatory for inbound access
- Azure security model is deny-by-default
