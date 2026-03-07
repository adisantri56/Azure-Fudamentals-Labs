![Azure](https://img.shields.io/badge/Azure-Networking-blue)
![Level](https://img.shields.io/badge/Level-AZ104-green)

# 🚀 Day 1 — Azure VM with Public IP

---

## 🎯 Objective
Create config NSG rule for ICMP Traffic

---

## 🛠 Lab Tasks
- Allow ICMP Traffic
- Deny ICMP Traffic

---

## 🧠 Key Concept

- NSG attached on NIC vs Subnet
- Rule Priority

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

Successfully apply allow and deny traffic from ICMP

---


## 💡 Lessons Learned

- By default NGS not allowed ICMP
- NSG is mandatory for inbound and outbound access
- NSG like firewall
