# 🧠 Zach's IT Home Lab Journey — A+ Certification & Help Desk Practice

## Welcome to my personal IT home lab repository!

This is a living, hands-on project where I document my journey toward earning the **CompTIA A+ certification**, building foundational IT skills, and landing a **remote Help Desk or IT Support role**.

Whether you're a beginner like me or someone looking to break into tech without a degree, this repo is here to:  
- 🛠️ Share **real-world labs and troubleshooting practice**  
- 📚 Track **A+ Core 1 (220-1101) & Core 2 (220-1102)** objectives  
- 🎯 Build skills around Windows, Linux, networking, security, virtualization, and more  
- 💻 Get hands-on using free tools like VirtualBox and open-source OSes  

---

## 👇 Table of Contents

- [🛠️ Step 1: Build a Hands-On IT Lab at Home](#step-1-build-a-hands-on-it-lab-at-home-no-extra-cost)  
- [🧰 IT Home Lab Setup](#your-it-home-lab-setup)  
- [🎯 Hands-On Goal Mapping (A+ Domains)](#hands-on-goals-core-a-help-desk-topics)  
- [🥊 VirtualBox vs VMware Workstation Player](#virtualbox-vs-vmware-workstation-player)  
- [✅ VirtualBox Installation Guide](#step-by-step-download--install-virtualbox)  

---

> 🔁 This repo will be updated as I move through topics, complete labs, and learn new skills. Everything is broken, fixed, and tested on a real system — no simulations here.

Feel free to follow along, or reach out if you're on a similar path.

---

## 🛠️ Step 1: Build a Hands-On IT Lab at Home (No Extra Cost)

This is your playground to experiment, break stuff, fix it, and document the whole process.

### 🧰 Your IT Home Lab Setup  
You already have a laptop — that’s all you need to start:

✅ Install VirtualBox or VMware Workstation Player (free)  
✅ Download and install:  

- Windows 10 ISO  
- Ubuntu (Linux) ISO  
- Optionally, Kali Linux (for security practice later)  

### Hands-on Goals (Core A+ & Help Desk Topics):

| Task                                                | What It Teaches                  | Core            |
| --------------------------------------------------- | -------------------------------- | --------------- |
| Install Windows in a VM                             | OS installation + virtualization | 220-1102        |
| Install Ubuntu in a VM                              | Linux basics                     | 220-1102        |
| Create file shares between VMs                      | Networking + permissions         | 220-1101 + 1102 |
| Install a printer in Windows                        | Peripherals & drivers            | 220-1101        |
| Use Task Manager, Event Viewer, CMD                 | Troubleshooting                  | 220-1102        |
| Simulate malware infection and removal              | Security concepts                | 220-1102        |
| Practice PC disassembly/reassembly videos (YouTube) | Hardware familiarity             | 220-1101        |

---

## 🥊 VirtualBox vs VMware Workstation Player

| Feature                      | **VirtualBox** (by Oracle)                      | **VMware Workstation Player** (by VMware)         |
| ---------------------------- | ----------------------------------------------- | ------------------------------------------------- |
| 💵 Cost                      | 100% Free (open-source)                         | Free for **personal use**                          |
| 💻 OS Support                | Windows, Linux, macOS, Solaris                  | Windows & Linux only                               |
| 🧩 Integration               | More flexible with multiple OSes and extensions | Slightly more stable & polished interface          |
| 🧪 Snapshots                 | ✅ Built-in snapshot support                     | ❌ Free version does **not** support snapshots      |
| 🛠️ Ease of Use              | Slightly more complex UI                         | Smoother, more user-friendly                       |
| 📚 Community Support         | Massive open-source community                    | Also large, with more enterprise focus             |
| 🐧 Linux Compatibility       | Excellent                                       | Also excellent (VMware runs Linux better overall) |
| 🧰 Customization             | Very customizable, great for labs               | Less tweakable in free version                     |
| 💾 File sharing (host/guest) | Easy with Guest Additions                        | Easy with VMware Tools                             |

---

## 🔍 Which One Should You Use?

✅ Use VirtualBox if...  
- You want snapshots (super useful for practicing break/fix)  
- You want to spin up multiple OSes, including macOS (eventually)  
- You prefer open-source tools  
- You want more flexibility for a DIY home lab setup  

✅ Use VMware Workstation Player if...  
- You want better performance/stability out of the box  
- You're only running Windows or Linux guests  
- You don’t need snapshots or advanced lab features  

🏁 **My Recommendation for You:**  
✅ Go with VirtualBox — it’s more flexible for lab work, totally free, and widely used in IT training.  
You can always try VMware later if you want a more “commercial” experience.

---

## 🔶 Step-by-Step: Download & Install VirtualBox


1️⃣ Go to the Official VirtualBox Site:  
👉 https://www.virtualbox.org/wiki/Downloads  

You’ll see a section called "VirtualBox platform packages" — this is where you get the main program.

2️⃣ Download for Your System  
Since you’re on Windows, click:  

🔵 Windows hosts
</br>


https://github.com/user-attachments/assets/6673593d-6af8-460a-a81a-3d0979044462


</br>

This downloads a file like:  
```

VirtualBox-7.x.x-yyyy-Win.exe

```
Save it somewhere easy to find (Desktop or Downloads).

### 3️⃣ Optional but Recommended: Extension Pack  
Scroll down to:  

📦 VirtualBox Extension Pack  

Click:  
```

All supported platforms

```

This gives you extra features like USB 2.0/3.0 support, RDP, webcam passthrough, and encryption.  
</br>


https://github.com/user-attachments/assets/0b43bdd5-8fb9-4820-b75a-aaf473477b9c


</br>


It downloads a file like:  
```

Oracle\_VM\_VirtualBox\_Extension\_Pack-7.x.x.vbox-extpack

```

---

## 🖥️ Install VirtualBox

1. Run the downloaded `.exe` file.  
2. Click Next through prompts (leave defaults checked).  
3. If you see a message about temporary internet disconnection, it's normal (virtual network adapter installs).  
4. Click Install and wait.  
5. Click Finish — VirtualBox will open.
</br>


https://github.com/user-attachments/assets/87c848b5-488a-4610-85e5-8ad600cbce71


</br>
---

## 🔌 Install the Extension Pack (Optional but Recommended)

1. Open VirtualBox  
2. Go to **File → Tools → Extension Pack Manager**  
3. Click the 📂 add icon, find the `.vbox-extpack` file  
4. Follow prompts to install

---

## 🧪 Final Check  
You should see the VirtualBox Manager window:  

```

+---------------------------------------+

| VirtualBox Manager                        |
| ----------------------------------------- |
| \[ New ] \[ Settings ] \[ Start ]         |
| ---------------------------------------   |
| No virtual machines yet                   |
| +---------------------------------------+ |

````

From here, you're ready to install your first virtual machine.

---

## 🖥️ Next Steps:

- Download Windows 10 ISO  
- Download Ubuntu ISO  
- Start creating VMs for practice  

---

## ✅ Step 1: Download Windows 10 ISO

Go to the official Microsoft download page:  
👉 [https://www.microsoft.com/software-download/windows10](https://www.microsoft.com/software-download/windows10)  

Scroll to:  
**"Create Windows 10 installation media"** and click **Download tool now**.  

Run the tool:  
- Accept license  
- Choose **Create installation media (USB flash drive, DVD, or ISO file)**  
- Select defaults (English, Windows 10, 64-bit)  
- Choose **ISO file** and save it.

---

## ✅ Step 2: Create a Windows 10 VM in VirtualBox

1. Open VirtualBox, click **New**  
2. Name: `Windows 10`, Type: `Microsoft Windows`, Version: `Windows 10 (64-bit)`  
3. Set Memory Size to 4096 MB (or at least 2048 MB)  
4. Create a virtual hard disk now (64 GB recommended, VDI, dynamically allocated)  
5. Click **Create**

---

## ✅ Step 3: Mount the ISO & Start the VM

1. Select your Windows VM  
2. Click **Start**  
3. Browse and select the downloaded `Windows10.iso`  
4. Click **Start** and install Windows as usual  
- Choose "Custom install"  
- Select unallocated disk  
- Skip product key  
- Optionally skip Microsoft account sign-in  

---

## 🎉 Done! You now have a Windows 10 VM to break, fix, and experiment in.

---

## ✅ Step 4: Download & Install Ubuntu Linux VM

Follow similar steps:  

- Download Ubuntu 22.04.4 LTS ISO from [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)  
- Create VM in VirtualBox: Name it `Ubuntu 22.04`, Type `Linux`, Version `Ubuntu (64-bit)`  
- Memory: 4096 MB (minimum 2048 MB)  
- Create virtual disk: 32 GB+, VDI, dynamically allocated  
- Mount ISO, start VM, and run installation  
- Choose normal installation + 3rd party drivers  
- Select erase disk (safe inside VM)  
- Setup user and password  

---

## ✅ Step 5: Setup Kali Linux (Optional for Cybersecurity)

- Download Kali Linux VirtualBox prebuilt image from https://www.kali.org/get-kali/#kali-platforms  
- Extract `.7z` file with 7-Zip  
- Import `.ova` or `.vbox` file into VirtualBox  
- Default creds: username `kali`, password `kali`  
- Update with:  
```bash
sudo apt update && sudo apt upgrade
````

---

## 🚀 Up Next: Create file shares between VMs

Sharing files between Windows and Linux VMs teaches networking, permissions, and troubleshooting.

---

## 🧱 Prerequisites

* Windows 10 VM and Ubuntu VM installed
* VirtualBox Guest Additions installed on both (for clipboard, drivers, and seamless sharing)

---

## 🛜 Step 1: Set Both VMs on the Same Virtual Network

* Shut down both VMs
* In VirtualBox Manager, go to each VM → Settings → Network
* For Adapter 1: Enable, attach to **Host-only Adapter**, choose `vboxnet0`
* Save settings

---

## 🌐 Step 2: Confirm VMs See Each Other

* On Ubuntu VM terminal:

```bash
ip a | grep inet
```

Note IP like `192.168.56.101`

* On Windows VM cmd:

```cmd
ipconfig
```

Note IP like `192.168.56.102`

* Ping test from each VM:
  Ubuntu → Windows:

```bash
ping 192.168.56.102
```

Windows → Ubuntu:

```cmd
ping 192.168.56.101
```

---

## 🧰 Step 3: Share Folder from Ubuntu to Windows (Using Samba)

1. On Ubuntu:

```bash
sudo apt update
sudo apt install samba -y
mkdir ~/shared-folder
chmod 777 ~/shared-folder
sudo nano /etc/samba/smb.conf
```

2. Add at the bottom of smb.conf:

```ini
[SharedFolder]
   path = /home/<your-username>/shared-folder
   browseable = yes
   read only = no
   guest ok = yes
```

3. Restart Samba and allow firewall:

```bash
sudo systemctl restart smbd
sudo ufw allow samba
```

4. On Windows File Explorer, enter:

```
\\192.168.56.101\SharedFolder
```

* Username: `guest`
* Password: leave blank

You should access the Ubuntu share!

---

## 💻 Step 4: Share Folder from Windows to Ubuntu

1. On Windows VM:

* Create folder (e.g., `SharedFromWindows`)
* Right-click → Properties → Sharing →


Advanced Sharing

* Share this folder, name it `WinShare`
* Permissions → Add Everyone → Allow Read/Write

2. Find Windows VM IP:

```cmd
ipconfig
```

3. On Ubuntu:

```bash
sudo apt update
sudo apt install cifs-utils -y
mkdir ~/winshare
sudo mount -t cifs //192.168.56.x/WinShare ~/winshare -o user=YourWindowsUsername,domain=WORKGROUP
```

Replace IP and username accordingly. Enter Windows password when prompted.

---

## 📌 Optional: Auto-mount Windows Share on Ubuntu Boot

1. Create credentials file (recommended for security):

```bash
sudo nano /etc/samba/credentials
```

Add:

```
username=YourWindowsUsername
password=YourPassword
```

Save and secure:

```bash
sudo chmod 600 /etc/samba/credentials
```

2. Edit fstab:

```bash
sudo nano /etc/fstab
```

Add:

```
//192.168.56.x/WinShare  /home/yourname/winshare  cifs  credentials=/etc/samba/credentials,uid=1000,gid=1000,iocharset=utf8  0  0
```

3. Test:

```bash
sudo umount ~/winshare
sudo mount -a
```

If no errors, auto-mount works!

---

## 📝 Lab Journal Entry Example

````markdown
### 🔗 Lab: File Sharing Between Ubuntu and Windows VMs

**What I Learned:**  
- Networking between VMs using Host-only Adapter  
- File sharing using Samba from Ubuntu to Windows  
- Sharing folders from Windows to Ubuntu using CIFS  
- Configuring permissions and SMB shares  
- Using IP tools (`ip a`, `ping`, `ipconfig`)  

**Key Commands:**  
```bash
sudo apt install samba cifs-utils
mkdir ~/shared-folder ~/winshare
chmod 777 ~/shared-folder
sudo nano /etc/samba/smb.conf
sudo systemctl restart smbd
sudo mount -t cifs //192.168.56.x/WinShare ~/winshare -o user=YourWindowsUsername
````

**Troubleshooting:**

* Make sure both VMs are on the same VirtualBox network
* Disable Windows Firewall if Ubuntu can’t reach the share
* Check permissions on both Windows and Ubuntu sides


---

## 🚀 Next Steps

- Practice installing and troubleshooting software on your VMs  
- Experiment with file sharing both ways (Windows ↔ Ubuntu)  
- Explore networking commands and troubleshooting (ping, ipconfig, ifconfig)  
- Set up Kali Linux and try penetration testing tools  
- Document every step here in this repo!  

---

# Happy labbing! 🔧💻🔐

