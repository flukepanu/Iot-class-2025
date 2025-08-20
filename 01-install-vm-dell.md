# 📄 Debian Installation Report for IoT, MQTT, Kafka Course

> Students must complete all sections of this form during Debian installation and submit it upon completion.

---

## 🔧 General Information

| Title                  | Value                                               |
| -----------------------| --------------------------------------------------- |
| Full Name              | Panuthep chulavech|
| Student ID              | 6510301025 |
| Installation Date      | 11/06/2568 |


---

## 🖥️ Device Information

- 💻 **Device Model / Type**: Virtual Machine
- 🧬 **Firmware Type**:  
  - [ ] UEFI  
  - [x] BIOS  
- 🏷️ **Installation Type**:  
  - [x] Physical PC  
  - [ ] Virtual Machine (VM)

---

## 🗂️ Custom Partitioning

| Partition     | Size   | Filesystem | Mount Point           | Notes              |
|---------------|--------|------------|------------------------|--------------------|
| `/boot`       | 512MB  | ext4       | `/boot`                | For boot loader    |
| `swap`        | 1GB    | swap       | -                      | Swap space         |
| `/` or others |        |            |                        |                    |



| Filesystem  | Size | Used | Avail | Use% | Mounted on       |     |
| ----------- | ---- | ---- | ----- | ---- | ---------------- | ------------------------------------ |
| `/dev/sda1` | 19G  | 2.1G | 16G   | 12%  | `/`              |   
| `udev`      | 1.9G | 0    | 1.9G  | 0%   | `/dev`           |      |
| `tmpfs`     | 392M | 464K | 392M  | 1%   | `/run`           |    |
| `tmpfs`     | 2.0G | 0    | 2.0G  | 0%   | `/dev/shm`       |  |
| `tmpfs`     | 5.0M | 0    | 5.0M  | 0%   | `/run/lock`      |    |
| `tmpfs`     | 392M | 0    | 392M  | 0%   | `/run/user/1000` | |

## 🌐 Network Configuration (Static IP)

| Title                   | Value                                               |
| ------------------------| --------------------------------------------------- |
| Network Interface Name  | ens18     |
| IP Address              | 172.30.15.38 |
| Netmask                 | 255.255.255.0 |
| Gateway                 | 172.30.15.254 |
| DNS                     | 8.8.8.8|

---

## 🖧 Hostname

- 🖥️ **Hostname Set**: FDT6510301025

---

## 👤 User Account

- 👨‍💻 **Username Created**: u6510301025
- 🔐 **Is a Root Password Set?**:  
  - [X] Yes  
  - [ ] No

---

## ✅ Additional Problems Notes (if any)

> _____________________________________________________________________  
> _____________________________________________________________________  
> _____________________________________________________________________

