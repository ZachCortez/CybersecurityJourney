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

Feel free to follow along, fork the repo, or reach out if you're on a similar path.



## 🛠️ Step 1: Build a Hands-On IT Lab at Home (No Extra Cost)
This is your playground to experiment, break stuff, fix it, and document the whole process.

🧰 Your IT Home Lab Setup
You already have a laptop — that’s all you need to start:

✅ Install VirtualBox or VMware Workstation Player (free)

✅ Download and install:

🔸 Windows 10 ISO

🔸 Ubuntu (Linux) ISO

🔸 Optionally, Kali Linux (for security practice later)

Hands-on Goals (Core A+ & Help Desk Topics):
| Task                                                | What It Teaches                  | Core            |
| --------------------------------------------------- | -------------------------------- | --------------- |
| Install Windows in a VM                             | OS installation + virtualization | 220-1102        |
| Install Ubuntu in a VM                              | Linux basics                     | 220-1102        |
| Create file shares between VMs                      | Networking + permissions         | 220-1101 + 1102 |
| Install a printer in Windows                        | Peripherals & drivers            | 220-1101        |
| Use Task Manager, Event Viewer, CMD                 | Troubleshooting                  | 220-1102        |
| Simulate malware infection and removal              | Security concepts                | 220-1102        |
| Practice PC disassembly/reassembly videos (YouTube) | Hardware familiarity             | 220-1101        |



## 🥊 VirtualBox vs VMware Workstation Player

Feature	VirtualBox (by Oracle)	VMware Workstation Player (by VMware)
| Feature                      | **VirtualBox** (by Oracle)                      | **VMware Workstation Player** (by VMware)         |
| ---------------------------- | ----------------------------------------------- | ------------------------------------------------- |
| 💵 Cost                      | 100% Free (open-source)                         | Free for **personal use**                         |
| 💻 OS Support                | Windows, Linux, macOS, Solaris                  | Windows & Linux only                              |
| 🧩 Integration               | More flexible with multiple OSes and extensions | Slightly more stable & polished interface         |
| 🧪 Snapshots                 | ✅ Built-in snapshot support                     | ❌ Free version does **not** support snapshots     |
| 🛠️ Ease of Use              | Slightly more complex UI                        | Smoother, more user-friendly                      |
| 📚 Community Support         | Massive open-source community                   | Also large, with more enterprise focus            |
| 🐧 Linux Compatibility       | Excellent                                       | Also excellent (VMware runs Linux better overall) |
| 🧰 Customization             | Very customizable, great for labs               | Less tweakable in free version                    |
| 💾 File sharing (host/guest) | Easy with Guest Additions                       | Easy with VMware Tools                            |


## 🔍 Which One Should You Use?

✅ Use VirtualBox if...

🔹 You want snapshots (super useful for practicing break/fix)

🔹 You want to spin up multiple OSes, including macOS (eventually)

🔹 You prefer open-source tools

🔹 You want more flexibility for a DIY home lab setup

✅ Use VMware Workstation Player if...

🔹 You want better performance/stability out of the box

🔹 You're only running Windows or Linux guests

🔹 You don’t need snapshots or advanced lab features

🏁 My Recommendation for You:

✅ Go with VirtualBox — it’s more flexible for lab work, totally free, and widely used in IT training.

 - You can always try VMware later if you want a more “commercial” experience.

</br>

## 🔶 Let’s walk through the exact steps to download and install VirtualBox, including the correct files to get you started safely and smoothly.

✅ Step-by-Step: Download & Install VirtualBox </br>

1️⃣ Go to the Official VirtualBox Site</br>

👉 https://www.virtualbox.org/wiki/Downloads

🟢 You’ll see a section called "VirtualBox platform packages" — this is where you get the main program.

2️⃣ Download for Your System

Since you’re on Windows, click:

🔵 Windows hosts

🟢 This will download a file like:
```VirtualBox-7.x.x-yyyy-Win.exe```

✅ Save it somewhere easy to find (like your Desktop or Downloads folder).

## 3️⃣ Optional but Recommended: Extension Pack
Still on that same page, scroll down to:

📦 VirtualBox Extension Pack

Click this:

🔗``` All supported platforms```

🔸 This gives you extra features like:

🔸 USB 2.0/3.0 device support

🔸 VirtualBox RDP (Remote Desktop)

🔸 Host webcam passthrough

🔸 Encryption (for future practice)

🟢 It’ll download a file like:
```Oracle_VM_VirtualBox_Extension_Pack-7.x.x.vbox-extpack```

## 🖥️ Install VirtualBox

1. Run the downloaded ```.exe``` file.

2. Click Next through the prompts (leave defaults checked).

3. If you see a message saying you may be temporarily disconnected from the internet, it’s fine — it installs a virtual network adapter.

4. Click Install and let it run.

5. Click Finish and VirtualBox will open.

## 🔌 Install the Extension Pack (Optional but Recommended)
1. Open VirtualBox

2. Go to: File → Tools → Extension Pack Manager

3. Click the 📂 add icon, find the ```.vbox-extpack``` file you downloaded

4. Follow prompts to install

</br>

##🧪 Final Check
You should now see the VirtualBox Manager window open and ready like this:

```
+---------------------------------------+
| VirtualBox Manager                    |
|---------------------------------------|
| [ New ] [ Settings ] [ Start ]        |
|---------------------------------------|
| No virtual machines yet               |
+---------------------------------------+
```
From here, you're ready to install your first virtual machine.

 🖥️ Next steps:

🔹 Download Windows 10 ISO

🔹 Download Ubuntu ISO

Start creating VMs for practice.
</hr></br>

##Let’s get your **first virtual machines (VMs)** up and running. We’ll start with **Windows 10**, then move to **Ubuntu Linux** after.

---

## ✅ Step 1: Download Windows 10 ISO

### 🔗 Go to the official Microsoft download page:

👉 [https://www.microsoft.com/software-download/windows10](https://www.microsoft.com/software-download/windows10)

### 🖱 Scroll to:

> **"Create Windows 10 installation media"**

Click:

> **Download tool now**

This gives you a file:

```
MediaCreationTool22H2.exe
```

### 📥 Run the tool:

1. Accept the license agreement.

2. Choose:

   > ✅ **"Create installation media (USB flash drive, DVD, or ISO file)"**

3. On the next screen, leave defaults (English, Windows 10, 64-bit) checked and click **Next**.

4. Choose:

   > ✅ **ISO file**

5. Save the `.iso` file somewhere you’ll remember.

💡 The tool will download and create a file like:

```
Windows10.iso
```

Once done — you're ready to install it in VirtualBox.

---

## ✅ Step 2: Create a Windows 10 VM in VirtualBox

1. Open **VirtualBox** and click:

   > **New**

2. Name: `Windows 10`

   * Type: `Microsoft Windows`
   * Version: `Windows 10 (64-bit)`

3. Click **Next**

4. Memory Size:

   * Set **4096 MB (4 GB)** if you can spare it — or **2048 MB** minimum.

5. Click **Next**

6. Create Virtual Hard Disk:
   ✅ Select “Create a virtual hard disk now”

   * Disk size: **64 GB** recommended
   * File type: `VDI`
   * Storage: `Dynamically allocated`

7. Click **Create**

---

## ✅ Step 3: Mount the ISO & Start the VM

1. Select your new VM on the left in VirtualBox
2. Click **Start**
3. It will prompt you to select a startup disk:

   * Click the 📂 icon and browse to your downloaded `Windows10.iso`
4. Click **Start**

You’ll now enter the Windows installation process — just like installing on a real PC!

---

## 🛠 Installation Tips:

* Choose "Custom install" if it asks for install type
* Select the only unallocated disk shown
* Windows will install normally — this can take a few minutes
* You **don’t need a product key** to install — click:

  > “I don’t have a product key”
* You can skip signing in with a Microsoft account (choose offline account)

---

## 🎉 Done! You now have a Windows 10 VM to break, fix, and experiment in.

---

## 🚀 Up Next: Install Ubuntu ISO
</hr>
 Let’s set up **Ubuntu Linux** next — it’s essential for both the CompTIA A+ and IT Help Desk practice, plus it'll help you get comfortable with Linux fundamentals (which are key for cybersecurity later).

---

## ✅ Step 1: Download Ubuntu ISO

### 🔗 Go to the official Ubuntu site:

👉 [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)

### ✅ Choose:

> **Ubuntu 22.04.4 LTS** (Long Term Support – recommended for stability)

Click:

> **Download**

This will download a file like:

```
ubuntu-22.04.4-desktop-amd64.iso
```

Once downloaded, you’re ready to create the VM.

---

## ✅ Step 2: Create an Ubuntu VM in VirtualBox

1. Open **VirtualBox**, then click:

   > **New**

2. Name: `Ubuntu 22.04`

   * Type: `Linux`
   * Version: `Ubuntu (64-bit)`

3. Click **Next**

4. Memory Size:

   * Recommend **4096 MB (4 GB)** if you can
   * Minimum: **2048 MB**

5. Click **Next**

6. Create Virtual Hard Disk:

   * Choose: ✅ **Create a virtual hard disk now**
   * Disk type: `VDI`
   * Storage: `Dynamically allocated`
   * Size: **32 GB or more** recommended

7. Click **Create**

---

## ✅ Step 3: Mount the ISO and Boot the VM

1. Select your new **Ubuntu** VM

2. Click **Start**

3. You'll be prompted to select a startup disk:

   * Click the 📂 folder and select:

     ```
     ubuntu-22.04.4-desktop-amd64.iso
     ```

4. Click **Start**

---

## 🛠 Step 4: Install Ubuntu

When it boots up:

1. Click **Install Ubuntu**
2. Choose your language and keyboard layout
3. On “Updates and Other Software”:

   * Choose: ✅ **Normal Installation**
   * Check both boxes: **Download updates** + **Install 3rd party drivers**
4. For installation type:

   * Choose: ✅ **Erase disk and install Ubuntu** (only applies to the VM's virtual disk, not your real system — you're safe!)
5. Click **Continue**
6. Set your user account details and password
7. Let the installation finish (\~5–10 min)

Once done, it’ll ask to restart — let it reboot and **remove the ISO** if prompted.

---

### 🎉 You’re Done!

You now have:
✅ **Windows 10 VM**
✅ **Ubuntu Linux VM**

This gives you two systems to test networking between, practice installs, troubleshoot, and simulate real-world help desk tasks.

## 🚀 Up Next: Download Kali Linux ISO
---

Let’s get **Kali Linux** set up! Kali is the go-to distro for penetration testing, ethical hacking, and cybersecurity labs. Setting it up in VirtualBox will give you a safe environment to start experimenting.

---

## ✅ Step 1: Download Kali Linux ISO

### 🔗 Official download page:

👉 [https://www.kali.org/get-kali/#kali-platforms](https://www.kali.org/get-kali/#kali-platforms)

### Under the **Virtual Machines** tab:

> 🟢 Instead of downloading a regular ISO, you can grab the **Kali Linux VirtualBox prebuilt image**, which is faster and already configured!

Click:

> **Kali Linux VirtualBox (64-bit)** – it’s a `.7z` file (compressed)

Example file:

```
kali-linux-2024.2-virtualbox-amd64.7z
```

---

## ✅ Step 2: Extract the Files

After downloading the `.7z` file, you’ll need to extract it.

### Use a tool like:

* [7-Zip](https://www.7-zip.org/) (recommended)
* Or WinRAR

After extracting, you’ll get a folder with files like:

```
Kali-Linux-2024.2-vbox-amd64.vbox
Kali-Linux-2024.2-vbox-amd64.vdi
```

These are **already configured** — no need to go through the normal installation process!

---

## ✅ Step 3: Import into VirtualBox

1. Open **VirtualBox**

2. Click **File → Import Appliance**

3. Select the `.ova` file if you downloaded that — or if you only got `.vbox`, click:

   > **Machine → Add**, and point to the `.vbox` file.

4. Click **Open** → then **Finish**

🎉 You’ve now got Kali Linux installed!

---

## 🛠 First Run Tips:

* Username: `kali`

* Password: `kali`
  (You can change this later.)

* After logging in, run this in Terminal to update tools:

```bash
sudo apt update && sudo apt upgrade
```

---

## 🚀 What Can You Do with Kali?

Here are a few tools you’ll explore later:

| Tool              | Purpose                               |
| ----------------- | ------------------------------------- |
| `nmap`            | Network scanning                      |
| `Wireshark`       | Packet sniffing                       |
| `Metasploit`      | Exploitation framework                |
| `Burp Suite`      | Web application vulnerability testing |
| `John the Ripper` | Password cracking                     |

---

## ⚠️ Reminder: **Use Responsibly**

Kali is powerful. Never run attacks on networks or devices you don’t own or have permission to test — use **your own VMs**, lab environments, or tools like TryHackMe/HackTheBox for legal practice.

</hr>
## 🚀 Up Next: Create file shares between VMs

---
Creating **file shares between VMs** is essential for learning networking, permissions, and cross-OS file handling — all core skills for **CompTIA A+**, help desk roles, and cybersecurity.

Let’s walk through how to **set up file sharing between a Windows VM and a Linux VM (like Ubuntu)** using VirtualBox’s **host-only network** and **Samba** file sharing.

---

## 🧱 Prerequisites

You should already have:

* ✅ Windows 10 VM installed in VirtualBox
* ✅ Ubuntu VM installed in VirtualBox
* ✅ VirtualBox Guest Additions installed on both VMs (for copy/paste and drivers)

---

## 🛜 Step 1: Set Both VMs on the Same Virtual Network

1. **Shutdown both VMs**
2. Open **VirtualBox Manager**
3. For both VMs:

   * Right-click > **Settings** > **Network**
   * **Adapter 1**:

     * Enable Network Adapter: ✅
     * Attached to: **Host-only Adapter**
     * Name: `vboxnet0` (or whatever VirtualBox auto-created)
4. Click OK to save

---

## 🌐 Step 2: Start the VMs and Confirm They See Each Other

### On Ubuntu VM:

```bash
ip a | grep inet
```

You’ll see something like `192.168.56.101`

### On Windows VM:

1. Open Command Prompt:

```cmd
ipconfig
```

You’ll see something like `192.168.56.102`

🟢 Try to **ping** each machine from the other to test the connection.

From Ubuntu:

```bash
ping 192.168.56.102
```

From Windows:

```cmd
ping 192.168.56.101
```

---

## 🧰 Step 3: Share a Folder from Ubuntu to Windows Using Samba

### On Ubuntu:

1. Install Samba:

```bash
sudo apt update
sudo apt install samba -y
```

2. Create a folder to share:

```bash
mkdir ~/shared-folder
```

3. Set permissions:

```bash
chmod 777 ~/shared-folder
```

4. Edit Samba config:

```bash
sudo nano /etc/samba/smb.conf
```

Scroll to the bottom and add:

```ini
[SharedFolder]
   path = /home/your-username/shared-folder
   browseable = yes
   read only = no
   guest ok = yes
```

Replace `your-username` with your actual Ubuntu username.

5. Restart Samba:

```bash
sudo systemctl restart smbd
```

6. Allow Samba through the firewall (optional):

```bash
sudo ufw allow samba
```

---

## 💻 Step 4: Access Ubuntu Share from Windows

1. On Windows, open File Explorer
2. In the address bar, enter:

```
\\192.168.56.101\SharedFolder
```

(Use the actual IP of your Ubuntu VM)

3. If prompted for login:

   * Username: **guest**
   * Leave password blank

✅ You should now see and access the shared folder!

---

## 📓 Document This in Your GitHub Lab Journal

````markdown
### 🔗 Lab: File Sharing Between Ubuntu and Windows VMs

**What I Learned:**
- Networking between VMs using Host-only Adapter
- File sharing using Samba from Ubuntu to Windows
- Configuring permissions and SMB shares
- Using IP tools (`ip a`, `ping`, `ipconfig`)

**Commands Used:**
```bash
sudo apt install samba
mkdir ~/shared-folder
chmod 777 ~/shared-folder
sudo nano /etc/samba/smb.conf
sudo systemctl restart smbd
````

**Troubleshooting Notes:**

* Confirm both VMs are on the same subnet
* Use correct path in `smb.conf`
* Check firewall settings if Windows can't connect

Let’s do it! 🔄 This time we’ll **share a folder from your Windows VM** and **access it from your Ubuntu VM** — a perfect way to learn real-world help desk troubleshooting and cross-OS networking.

---

## 📤 Step-by-Step: Share a Folder from Windows to Ubuntu

### ✅ Step 1: Create and Share the Folder in Windows

1. On your **Windows VM**:

   * Create a folder on your Desktop or C:\ (e.g., `SharedFromWindows`)
   * Right-click the folder > **Properties**
   * Go to the **Sharing** tab > click **Advanced Sharing**
   * ✅ Check **Share this folder**
   * Name it something like: `WinShare`
   * Click **Permissions**, and:

     * Select **Everyone**
     * ✅ Allow **Read/Write**
   * Click OK > OK > Close

2. Get your Windows VM's IP address:

   ```cmd
   ipconfig
   ```

   Look for something like `192.168.56.x`

---

### 🧷 Step 2: Access the Windows Share from Ubuntu

1. On your **Ubuntu VM**, install CIFS utils (for SMB support):

   ```bash
   sudo apt update
   sudo apt install cifs-utils -y
   ```

2. Create a mount point (where you’ll access the share):

   ```bash
   mkdir ~/winshare
   ```

3. Mount the Windows share:

   ```bash
   sudo mount -t cifs //192.168.56.x/WinShare ~/winshare -o user=YourWindowsUsername
   ```

   * Replace `192.168.56.x` with your Windows IP.
   * Replace `YourWindowsUsername` with your Windows login username.
   * Enter your password when prompted.

✅ You should now see the **Windows folder's contents** inside `~/winshare` on Ubuntu!

---

## 📌 Optional: Mount the Share Automatically on Boot

1. Edit the fstab file:

   ```bash
   sudo nano /etc/fstab
   ```

2. Add this line at the bottom:

   ```
   //192.168.56.x/WinShare  /home/yourname/winshare  cifs  username=YourWindowsUsername,password=YourPassword,uid=1000,gid=1000,iocharset=utf8  0  0
   ```

   * Replace paths, IP, and credentials accordingly.
   * Save and exit (`CTRL+O`, then `CTRL+X`)

3. Test it:

   ```bash
   sudo umount ~/winshare
   sudo mount -a
   ```

🟢 If no errors, the mount works!

---

## 📝 Lab Journal Entry Example

````markdown
### 🔁 Lab: Sharing Files from Windows VM to Ubuntu

**What I Did:**
- Created a shared folder on Windows using advanced sharing
- Used CIFS to mount the share on Ubuntu
- Tested connectivity and access
- Learned basic `fstab` entry setup for persistent mounts

**Key Commands:**
```bash
sudo apt install cifs-utils
mkdir ~/winshare
sudo mount -t cifs //192.168.56.102/WinShare ~/winshare -o user=zach
````

**Troubleshooting:**

* 🧱 Make sure both VMs are on the same VirtualBox network
* 🛑 Disable Windows Firewall if Ubuntu can’t reach the share
* 🔐 If you get permissions errors, check Windows sharing settings

</hr>




